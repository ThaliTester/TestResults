#### Test 797638307ede68b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 15:28:36.838  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:28:36.846  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 15:28:36.848  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 15:28:36.895  1494  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 15:28:36.895  1494  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 15:28:36.895  1494  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:28:36.896  1494  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 15:28:36.924  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 15:28:36.925  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 15:28:36.925  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-30 15:28:37.463  3753  3753 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 15:28:37.468  3753  3753 D AndroidRuntime: CheckJNI is OFF
08-30 15:28:37.511  3753  3753 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 15:28:37.566  3753  3753 I Radio-JNI: register_android_hardware_Radio DONE
08-30 15:28:37.587  3753  3753 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 15:28:37.592   873  1683 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 15:28:37.653  2052  2417 W SearchService: Abort, client detached.
08-30 15:28:37.660  2052  2336 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@dd09d7d
08-30 15:28:37.660  2052  2052 I HotwordDetector: Closing mic
08-30 15:28:37.660  2052  2345 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 15:28:37.682  3753  3753 D AndroidRuntime: Shutting down VM
08-30 15:28:37.707   873  2021 I ActivityManager: Start proc 3766:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 15:28:37.732   376  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 15:28:37.734   376  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 15:28:37.743   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 15:28:37.746  2052  2343 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 15:28:37.747  2052  2344 I MicroRecognitionRnrImpl: Detection finished
08-30 15:28:37.796  3766  3766 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 15:28:37.820  3766  3766 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 15:28:37.827  3766  3766 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8972-8975)
08-30 15:28:37.828  3766  3766 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:28:37.840  3766  3766 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27064ca}
08-30 15:28:37.841  3766  3766 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:28:37.841  3766  3766 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 15:28:37.847  3766  3766 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 15:28:37.849  3766  3766 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 15:28:37.868  3766  3766 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 15:28:37.879  3766  3766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 15:28:37.879  3766  3766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 15:28:37.879  3766  3766 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 15:28:37.879  3766  3766 I Adreno  : Build Date                       : 10/20/15
08-30 15:28:37.879  3766  3766 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 15:28:37.879  3766  3766 I Adreno  : Local Branch                     : M14
08-30 15:28:37.879  3766  3766 I Adreno  : Remote Branch                    : 
08-30 15:28:37.879  3766  3766 I Adreno  : Remote Branch                    : 
08-30 15:28:37.879  3766  3766 I Adreno  : Reconstruct Branch               : 
,08-30 15:28:37.961   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d0486:true
,08-30 15:28:37.990  3766  3766 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 15:28:38.003  3766  3766 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 15:28:38.068  3766  3805 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 15:28:38.079  3766  3792 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 15:28:38.114  3766  3805 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 15:28:38.193   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +509ms
,08-30 15:28:38.196  1890  1890 I Keyboard.Facilitator: onFinishInput()
,08-30 15:28:38.294  3766  3766 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3766
,08-30 15:28:38.416  3766  3766 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 15:28:38.538   873  2004 I ActivityManager: Killing 2990:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 15:28:38.564   873  2004 I ActivityManager: Killing 3109:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-30 15:28:38.657  3766  3808 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1696728784
,08-30 15:28:38.666  3766  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 15:28:38.666  3766  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 15:28:38.666  3766  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 15:28:38.666  3766  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 15:28:38.666  3766  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 15:28:38.666  3766  3808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bdba2e added. We now have 1 listener(s)
,08-30 15:28:38.670  3766  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 15:28:38.671  3766  3808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:28:38.672  3766  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:28:38.672  3766  3808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 15:28:38.675  3766  3808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4589265 added. We now have 1 listener(s)
08-30 15:28:38.676  3766  3808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:28:38.679   873  1306 D WifiService: New client listening to asynchronous messages
08-30 15:28:38.680  3766  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:28:38.680  3766  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 15:28:38.681  3766  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 15:28:38.681  3766  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-30 15:28:38.681  3766  3808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 15:28:38.683  3766  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:28:38.683  3766  3808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 15:28:38.690  3766  3808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:38.691  3766  3808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:28:38.691  3766  3808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 15:28:38.691  3766  3808 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:28:38.692  3766  3808 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 15:28:38.865  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:38.871  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:38.875  3766  3766 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 15:28:39.528  3766  3817 W jxcore-log: Initializing JXcore engine
,08-30 15:28:39.528  3766  3817 W jxcore-log: JXcore engine is ready
,08-30 15:28:39.565  3817  3817 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 15:28:39.565  3817  3817 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10723]" dev="sockfs" ino=10723 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 15:28:39.565  3817  3817 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 15:28:39.565  3817  3817 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23206]" dev="sockfs" ino=23206 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 15:28:39.580  3766  3817 W jxcore-log: Starting JXcore engine
,08-30 15:28:39.662  3766  3817 W jxcore-log: Platform android
08-30 15:28:39.662  3766  3817 W jxcore-log: 
08-30 15:28:39.662  3766  3817 W jxcore-log: Process ARCH arm
08-30 15:28:39.662  3766  3817 W jxcore-log: 
,08-30 15:28:39.899  3766  3817 I jxcore-log: JXcore Cordova bridge is ready!
08-30 15:28:39.899  3766  3817 I jxcore-log: 
08-30 15:28:39.900  3766  3817 W jxcore-log: JXcore engine is started
,08-30 15:28:39.916  3766  3808 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 15:28:39.922  3766  3766 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 15:28:43.178   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 15:28:45.923  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:28:45.928  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:28:45.972  1494  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 15:28:45.973  1494  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 15:28:45.973  1494  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:28:45.973  1494  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:28:46.013  3008  3825 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 15:28:46.013  3008  3825 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jdm.a(PG:82)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jcs.o(PG:406)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jcn.a(PG:1379)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jcs.i(PG:143)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at blb.a(PG:3937)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at czp.a(PG:18188)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at czp.a(PG:9081)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at czq.run(PG:1686)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 15:28:46.013  3008  3825 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jdj.a(PG:4091)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jdj.a(PG:1125)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jdm.a(PG:77)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	... 12 more
08-30 15:28:46.013  3008  3825 E HttpOperation: Caused by: faj: BadAuthentication
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at fal.a(PG:38)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	at jdj.a(PG:4089)
08-30 15:28:46.013  3008  3825 E HttpOperation: 	... 14 more
,08-30 15:28:46.086  1494  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-30 15:28:46.086  1494  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-30 15:28:46.086  1494  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:28:46.086  1494  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:28:46.109  3008  3825 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 15:28:46.109  3008  3825 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jdm.a(PG:82)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jcs.o(PG:406)
,08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jcn.a(PG:1379)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jcs.i(PG:143)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at hec.a(PG:42)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at hee.a(PG:102)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at czr.a(PG:65)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at kka.a(PG:108)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at czp.a(PG:19176)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at czp.a(PG:9081)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at czq.run(PG:1686)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 15:28:46.109  3008  3825 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jdj.a(PG:4091)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jdj.a(PG:1125)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jdm.a(PG:77)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	... 15 more
08-30 15:28:46.109  3008  3825 E HttpOperation: Caused by: faj: BadAuthentication
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at fal.a(PG:38)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	at jdj.a(PG:4089)
08-30 15:28:46.109  3008  3825 E HttpOperation: 	... 17 more
08-30 15:28:46.110  3008  3825 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 15:28:46.110  3008  3825 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at hec.a(PG:42)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at hee.a(PG:102)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at czr.a(PG:65)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at kka.a(PG:108)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at jdj.a(PG:1125)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	... 15 more
08-30 15:28:46.110  3008  3825 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	at fal.a(PG:38)
08-30 15:28:46.110  3008  3825 E Exp,erimentLoader: 	at jdj.a(PG:4089)
08-30 15:28:46.110  3008  3825 E ExperimentLoader: 	... 17 more
,08-30 15:28:46.243   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126824, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-30 15:28:49.777  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 15:28:49.777  3766  3817 I jxcore-log: 
,08-30 15:28:49.780  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 15:28:49.780  3766  3817 I jxcore-log: 
,08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:49.791  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:28:49.797  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:28:49.800  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 15:28:49.800  3766  3817 I jxcore-log: 
,08-30 15:28:49.802  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 15:28:49.802  3766  3817 I jxcore-log: 
,08-30 15:28:50.290  3766  3817 D executeNativeTests: Running unit tests
,08-30 15:28:50.347  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:28:50.347  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e added. We now have 2 listener(s)
08-30 15:28:50.348  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:28:50.348  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:28:50.349  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:28:50.349  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:28:50.349  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf added. We now have 2 listener(s)
08-30 15:28:50.349  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:28:50.349  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:28:50.352  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:50.378  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:28:50.382  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:28:50.383  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:28:50.385  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 15:28:50.385  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:28:50.385  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:28:50.386  3766  3817 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 15:28:50.386  3766  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 15:28:50.387  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:28:50.387  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:28:50.387  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:28:50.387  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.387  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.387  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.387  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.388  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.388  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.388  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:28:50.388  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:28:50.388  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e removed from the list
08-30 15:28:50.388  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.388  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf removed from the list
,08-30 15:28:50.396  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.397  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:28:50.398  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.400  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.400  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.402  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:28:50.403  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.403  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.403  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.406  3766  3817 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 15:28:50.408  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.408  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.409  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.409  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.409  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.409  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.409  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.410  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.410  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.410  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.410  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.410  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.410  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.411  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.412  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:28:50.412  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.413  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.413  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:28:50.424  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:28:50.425  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:28:50.426  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:28:50.426  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:28:50.426  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:28:50.426  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:28:50.426  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:28:50.426  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:28:50.426  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:28:50.426  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.426  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:28:50.426  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.426  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.426  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.426  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.426  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.427  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.427  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.427  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.427  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.427  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.427  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.427  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.428  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.428  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.428  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.428  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.429  3766  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:28:50.430  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:50.437  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:28:50.441  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:28:50.441  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:28:50.442  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:28:50.442  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:28:50.442  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:28:50.442  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:28:50.443  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:28:50.444  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.446  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.450  3766  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 15:28:50.450  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:28:50.459  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:28:50.463  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 15:28:50.463  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:28:50.467  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 15:28:50.470  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 15:28:50.471  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 15:28:50.472  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 15:28:50.475  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:28:50.478  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:28:50.489  2676  2819 D BtGatt.GattService: registerClient() - UUID=211dc2c4-21c2-4b77-be34-7a8475655666
,08-30 15:28:50.491  2676  2696 D BtGatt.GattService: onClientRegistered() - UUID=211dc2c4-21c2-4b77-be34-7a8475655666, clientIf=5
,08-30 15:28:50.492  3766  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 15:28:50.494  2676  2820 D BtGatt.GattService: start scan with filters
,08-30 15:28:50.501  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:28:50.501  2676  2701 D BtGatt.ScanManager: handling starting scan
,08-30 15:28:50.502  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 15:28:50.502  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 15:28:50.503  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 15:28:50.504  2676  2701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:28:50.508  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:28:50.508  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:28:50.509  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:28:50.511  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 15:28:50.513  2676  2696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 15:28:50.513  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.514  2676  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 15:28:50.517  3766  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 15:28:50.522  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:28:50.522  3766  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 15:28:50.522  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:28:50.523  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:28:50.523  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.523  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:28:50.523  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:28:50.523  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 15:28:50.523  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:28:50.523  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:28:50.524  2676  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:28:50.524  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.524  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:28:50.524  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:28:50.525  2676  2701 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:28:50.525  3766  3817 D BluetoothAdapter: STATE_ON
08-30 15:28:50.525  2676  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 15:28:50.526  2676  2688 D BtGatt.GattService: stopScan() - queue size =1
08-30 15:28:50.528  2676  2819 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 15:28:50.529  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:28:50.530  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 15:28:50.530  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:28:50.530  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:28:50.530  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:28:50.533  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:28:50.534  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 15:28:50.534  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:28:50.535  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:28:50.536  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:28:50.538  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:28:50.538  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:28:50.539  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:28:50.539  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:28:50.539  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.539  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:28:50.539  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
,08-30 15:28:50.539  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:28:50.539  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.539  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.540  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.540  3766  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:28:50.541  2676  2696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 15:28:50.541  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.543  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:50.548  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:28:50.551  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:28:50.552  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:28:50.552  2676  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 15:28:50.552  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:28:50.553  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:28:50.552  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.553  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:28:50.553  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:28:50.553  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:28:50.555  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.557  3766  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 15:28:50.557  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:28:50.558  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.563  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:28:50.564  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 15:28:50.564  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:28:50.565  2676  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:28:50.565  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.565  2676  2701 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:28:50.568  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:28:50.569  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:28:50.569  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 15:28:50.569  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:28:50.572  2676  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 15:28:50.572  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.573  2676  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:28:50.573  2676  2688 D BtGatt.GattService: registerClient() - UUID=0281a578-4dbb-4a48-8f42-851f612080ae
08-30 15:28:50.574  2676  2696 D BtGatt.GattService: onClientRegistered() - UUID=0281a578-4dbb-4a48-8f42-851f612080ae, clientIf=5
08-30 15:28:50.574  3766  3778 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 15:28:50.575  2676  2820 D BtGatt.GattService: start scan with filters
,08-30 15:28:50.579  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:28:50.579  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:28:50.579  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:28:50.579  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:28:50.581  2676  2696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:28:50.582  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.583  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:28:50.584  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:28:50.584  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:28:50.584  2676  2701 D BtGatt.ScanManager: handling starting scan
,08-30 15:28:50.586  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:28:50.589  3766  3817 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 15:28:50.592  2676  2696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 15:28:50.592  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.592  2676  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 15:28:50.594  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.594  3766  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:28:50.594  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:28:50.594  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:28:50.594  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.594  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 15:28:50.595  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:28:50.595  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:28:50.595  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:28:50.595  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 15:28:50.595  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:28:50.595  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:28:50.596  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:28:50.597  2676  2688 D BtGatt.GattService: stopScan() - queue size =1
08-30 15:28:50.598  2676  2687 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:28:50.598  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:28:50.598  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 15:28:50.598  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:28:50.598  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:28:50.598  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:28:50.599  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:28:50.599  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:28:50.600  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 15:28:50.600  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:28:50.600  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:28:50.602  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:28:50.602  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:28:50.602  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:28:50.602  2676  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:28:50.602  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.602  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.602  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.602  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:28:50.602  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.602  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.603  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.603  2676  2701 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:28:50.603  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.603  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.603  2676  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 15:28:50.603  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.603  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.605  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.605  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.605  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:28:50.605  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.606  3766  3817 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:28:50.608  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:50.614  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:28:50.617  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.617  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:28:50.618  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:28:50.618  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:28:50.618  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:28:50.618  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:28:50.618  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:28:50.620  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.622  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.625  3766  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 15:28:50.625  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:28:50.626  2676  2696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 15:28:50.626  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.631  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:28:50.632  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 15:28:50.632  2676  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-30 15:28:50.633  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:28:50.633  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.638  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:28:50.638  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 15:28:50.638  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:28:50.639  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:28:50.641  2676  2820 D BtGatt.GattService: registerClient() - UUID=a8c5ee88-1836-47dc-8872-fe0adfc18ec4
,08-30 15:28:50.642  2676  2696 D BtGatt.GattService: onClientRegistered() - UUID=a8c5ee88-1836-47dc-8872-fe0adfc18ec4, clientIf=5
08-30 15:28:50.642  3766  3778 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 15:28:50.642  2676  2687 D BtGatt.GattService: start scan with filters
08-30 15:28:50.643  2676  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:28:50.643  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.643  2676  2701 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:28:50.645  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:28:50.646  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:28:50.646  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:28:50.646  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:28:50.649  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:28:50.649  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:28:50.649  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:28:50.651  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:28:50.652  2676  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 15:28:50.652  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.653  2676  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 15:28:50.656  3766  3817 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:28:50.656  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:28:50.656  3766  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 15:28:50.656  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.657  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:28:50.657  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.657  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:28:50.657  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:28:50.657  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 15:28:50.658  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:28:50.662  2676  2696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:28:50.658  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:28:50.665  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.665  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:28:50.666  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:28:50.667  2676  2701 D BtGatt.ScanManager: handling starting scan
,08-30 15:28:50.667  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:28:50.668  2676  2819 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:28:50.669  2676  2688 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 15:28:50.670  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 15:28:50.670  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 15:28:50.670  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 15:28:50.671  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 15:28:50.671  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:28:50.672  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:28:50.673  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 15:28:50.673  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 15:28:50.673  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:28:50.674  2676  2696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 15:28:50.674  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.674  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:28:50.674  2676  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 15:28:50.677  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:28:50.677  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:28:50.677  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:28:50.678  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:28:50.678  3766  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 15:28:50.678  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:28:50.678  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:28:50.678  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:28:50.678  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.678  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:28:50.679  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
,08-30 15:28:50.679  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:28:50.679  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.679  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:28:50.679  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.680  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.680  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.681  2676  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,08-30 15:28:50.681  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.681  2676  2701 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 15:28:50.681  2676  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 15:28:50.681  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:28:50.681  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.681  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.681  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.682  3766  3817 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 15:28:50.683  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.683  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.683  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.683  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.683  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.683  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.683  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
,08-30 15:28:50.684  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.684  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.684  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.684  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.684  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.684  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.684  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.686  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.686  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:28:50.686  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.687  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.688  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:28:50.688  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:28:50.688  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:28:50.688  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.688  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.688  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.689  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.689  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.689  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.689  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.689  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.689  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.689  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.689  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.689  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.690  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.690  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.691  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.691  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.691  3766  3817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 15:28:50.692  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.692  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.692  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.692  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.692  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.692  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.692  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.692  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.692  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.692  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.692  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not ,exist in the list - probably already removed
08-30 15:28:50.693  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.693  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.693  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.694  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.694  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.694  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.694  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.694  3766  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 15:28:50.695  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.695  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.695  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.695  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.695  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.695  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.695  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.695  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.695  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.696  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.696  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.696  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.696  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.696  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.697  2676  2696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 15:28:50.697  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.698  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.698  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.698  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.698  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.699  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:28:50.701  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:28:50.701  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:28:50.701  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:28:50.701  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:28:50.701  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:28:50.702  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.702  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.702  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.702  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.702  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.702  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.703  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.703  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.703  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.703  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.703  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.703  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.703  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.703  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.703  2676  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 15:28:50.704  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.704  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.704  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.704  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.704  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.705  3766  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:28:50.705  3766  3817 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:28:50.705  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:28:50.713  3766  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:28:50.713  3766  3817 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 15:28:50.713  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:28:50.713  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:28:50.713  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:28:50.713  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:28:50.713  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:28:50.713  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:28:50.714  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:28:50.715  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:28:50.716  3766  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 15:28:50.716  3766  3817 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:28:50.716  2676  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:28:50.716  3766  3817 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 15:28:50.716  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.716  3766  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:28:50.716  3766  3817 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:28:50.716  2676  2701 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:28:50.716  3766  3817 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 15:28:50.716  3766  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:28:50.717  3766  3817 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:28:50.717  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 15:28:50.721  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 15:28:50.722  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 15:28:50.722  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 15:28:50.723  2676  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 15:28:50.723  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:28:50.723  2676  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:28:50.724  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 15:28:50.724  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 15:28:50.725  3766  3817 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 15:28:50.725  3766  3817 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:28:50.725  3766  3817 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 15:28:50.726  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.726  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.726  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.726  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.726  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.726  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.727  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 15:28:50.727  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.727  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.728  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.728  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.728  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.728  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.728  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.728  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.731  2676  2696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:28:50.731  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.731  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.731  2676  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:28:50.731  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.731  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.731  3766  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
08-30 15:28:50.732  3766  3817 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 15:28:50.732  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.732  3766  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-30 15:28:50.732  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.732  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.732  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.733  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.733  3766  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
08-30 15:28:50.733  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.733  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.733  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.733  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.733  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.733  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.733  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.733  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.733  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.734  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.734  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.734  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.734  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.735  3766  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 15:28:50.735  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.735  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.735  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.735  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.735  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.735  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.736  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.736  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.736  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.736  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.736  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.736  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.736  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.736  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.737  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.737  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.737  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.737  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.738  3766  3817 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 15:28:50.738  3766  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 15:28:50.738  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:28:50.738  3766  3817 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 15:28:50.738  3766  3817 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:28:50.738  3766  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 15:28:50.739  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:28:50.739  3766  3817 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 15:28:50.739  3766  3817 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:28:50.739  3766  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:28:50.739  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:28:50.739  3766  3817 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 15:28:50.739  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.739  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.739  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.739  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.739  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.739  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.739  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.739  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.740  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.740  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:28:50.740  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.740  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.740  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.740  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.741  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.741  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.741  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.741  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.741  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.742  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.742  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.742  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.742  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.742  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.742  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.742  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.742  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.742  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.742  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.742  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.742  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.742  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.742  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.742  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.743  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.743  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.743  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.743  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.743  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.743  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
,08-30 15:28:50.743  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:28:50.743  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.743  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:28:50.743  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.743  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.743  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.743  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.744  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.744  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.744  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.744  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.746  3766  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 15:28:50.746  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:28:50.746  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 15:28:50.747  3766  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 15:28:50.747  3766  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 15:28:50.747  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 15:28:50.747  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:28:50.747  3766  3766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 15:28:50.747  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.748  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 15:28:50.748  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 15:28:50.748  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 15:28:50.748  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.748  3766  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 15:28:50.748  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.748  3766  3766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 15:28:50.748  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.748  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:28:50.748  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:28:50.748  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:28:50.748  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.749  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.749  3766  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 15:28:50.749  3766  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 15:28:50.750  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:28:50.750  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.750  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:28:50.750  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.750  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.750  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.750  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.750  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.750  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.750  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:28:50.750  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
,08-30 15:28:50.750  3766  3766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 15:28:50.750  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.750  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.750  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.750  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.750  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.750  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.750  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:28:50.751  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.752  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.752  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.752  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.752  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.753  3766  3817 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 15:28:50.753  3766  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:28:50.753  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:28:50.753  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:28:50.753  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.753  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.753  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.754  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.754  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.754  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.754  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.754  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.754  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.754  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:28:50.754  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.754  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.754  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.754  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.755  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:28:50.755  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.755  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.755  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.758  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.758  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.758  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:28:50.758  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:28:50.758  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.758  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.758  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
,08-30 15:28:50.758  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.758  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.758  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:28:50.758  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.758  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.758  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.758  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.759  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.759  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.759  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:28:50.759  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.760  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:28:50.760  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:28:50.760  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:28:50.760  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:28:50.760  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.760  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.760  3766  3817 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de8a97e not in the list
08-30 15:28:50.760  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:28:50.760  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
,08-30 15:28:50.760  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:28:50.761  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:28:50.761  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:28:50.761  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:28:50.761  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:28:50.761  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:28:50.761  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:28:50.762  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 15:28:50.762  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528bedf not in the list
08-30 15:28:50.762  3766  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-30 15:28:50.763  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:28:50.763  3766  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 15:28:50.763  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 15:28:50.763  3766  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 15:28:50.763  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:28:50.764  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:28:50.765  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 15:28:50.765  3766  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 15:28:50.765  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 15:28:50.765  3766  3817 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 15:28:50.765  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 15:28:50.765  3766  3817 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 15:28:50.765  3766  3817 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-30 15:28:50.766  3766  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 15:28:50.766  3766  3817 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 15:28:50.767  3766  3817 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 15:28:50.767  3766  3817 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-30 15:28:50.767  3766  3817 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 15:28:50.767  3766  3817 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 15:28:50.768  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:28:50.768  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9558a9 added. We now have 2 listener(s)
,08-30 15:28:50.768  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:28:50.769  3766  3817 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 15:28:50.769   873   884 D WifiService: setWifiEnabled: true pid=3766, uid=10000
08-30 15:28:50.770   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:28:50.770  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:28:50.770  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2506e2e added. We now have 3 listener(s)
08-30 15:28:50.770  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:28:50.773  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:28:50.773  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3651dcf added. We now have 4 listener(s)
08-30 15:28:50.774  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:28:50.774  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:28:50.775  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3cf35c added. We now have 5 listener(s)
08-30 15:28:50.775  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:28:50.776   873  1385 D WifiService: setWifiEnabled: false pid=3766, uid=10000
08-30 15:28:50.776   873  1385 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:28:50.780  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:28:50.780  2676  2691 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 15:28:50.780  2676  2691 D BluetoothAdapterProperties: Setting state to 13
08-30 15:28:50.780  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:28:50.780  2676  2691 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 15:28:50.781  2676  2691 I BluetoothAdapterState: Entering PendingCommandState
08-30 15:28:50.782  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:50.782  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:28:50.783  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.783  2676  2676 D BluetoothMapService: onReceive
,08-30 15:28:50.783  2676  2676 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:28:50.783  2676  2676 D BluetoothMapService: STATE_TURNING_OFF
08-30 15:28:50.783  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.783  2676  2676 D BluetoothMapService: MAP Service closeService in
08-30 15:28:50.783  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:28:50.783  2676  2676 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 15:28:50.783  2676  2676 D ObexServerSockets0: shutdown(block = true)
,08-30 15:28:50.784  2676  2676 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 15:28:50.784  2676  2676 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 15:28:50.784  2676  2821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 15:28:50.784  2676  2822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 15:28:50.785  2676  2796 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 15:28:50.785  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.787  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.788  2676  2676 I BtOppRfcommListener: stopping Accept Thread
08-30 15:28:50.788  2676  3457 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 15:28:50.788  2676  3457 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 15:28:50.791  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:50.791  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:28:50.792  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.792  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:50.792  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:28:50.793   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 15:28:50.793   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 15:28:50.793   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:28:50.793   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:28:50.795  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.796   873   886 I ActivityManager: Start proc 3838:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 15:28:50.797  2676  2696 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:28:50.797  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 15:28:50.800  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.801  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.803  2676  2676 D HeadsetService: Received stop request...Stopping profile...
08-30 15:28:50.805   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 15:28:50.805   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 15:28:50.805  1955  2105 D BluetoothHeadset: Proxy object disconnected
08-30 15:28:50.806   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 15:28:50.806  1351  2108 D BluetoothHeadset: Proxy object disconnected
08-30 15:28:50.806  2676  2676 D A2dpService: Received stop request...Stopping profile...
08-30 15:28:50.806  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-30 15:28:50.806  2676  2814 D A2dpStateMachine: Exit Disconnected: -1
,08-30 15:28:50.808   873   873 D BluetoothA2dp: Proxy object disconnected
08-30 15:28:50.808  1351  1351 D BluetoothA2dp: Proxy object disconnected
08-30 15:28:50.809  2676  2676 D HidService: Received stop request...Stopping profile...
08-30 15:28:50.809  2676  2676 D HidService: Stopping Bluetooth HidService
08-30 15:28:50.809   873  2276 D DhcpClient: Clearing IP address
08-30 15:28:50.810  2676  2676 D HealthService: Received stop request...Stopping profile...
08-30 15:28:50.810   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:28:50.811  2676  2676 V BluetoothAdapterState: isTurningOff()=true
08-30 15:28:50.811  2676  2676 V BluetoothAdapterState: isTurningOn()=false
08-30 15:28:50.811  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:28:50.811  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:28:50.811  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-30 15:28:50.811  1351  1351 D HidProfile: Bluetooth service disconnected
08-30 15:28:50.812  2676  2676 D PanService: Received stop request...Stopping profile...
08-30 15:28:50.813   372   871 D CommandListener: Setting iface cfg
,08-30 15:28:50.814  2676  2676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:28:50.815  2676  2781 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:28:50.815  2676  2781 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:28:50.815  2676  2781 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:28:50.816  1494  2548 V NativeCrypto: Read error: ssl=0x9afae800: I/O error during system call, Connection timed out
08-30 15:28:50.817  1494  2548 V NativeCrypto: SSL shutdown failed: ssl=0x9afae800: I/O error during system call, Broken pipe
08-30 15:28:50.815  2676  2696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 15:28:50.819  2676  2696 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-30 15:28:50.819  2676  2676 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:28:50.819   873  1974 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-30 15:28:50.819  2676  2676 D BluetoothMapService: Received stop request...Stopping profile...
08-30 15:28:50.819  2676  2676 D BluetoothMapService: stop()
08-30 15:28:50.819   873  2274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-30 15:28:50.820  2676  2676 D BluetoothMapAppObserver: deinitObservers()
08-30 15:28:50.820  2676  2676 D BluetoothMapAppObserver: removeReceiver()
,08-30 15:28:50.815  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:28:50.820  1351  1351 D PanProfile: Bluetooth service disconnected
08-30 15:28:50.821  2676  2676 V BluetoothAdapterState: isTurningOff()=true
08-30 15:28:50.821  2676  2676 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:28:50.821  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:28:50.821  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:28:50.822  1351  1351 D BluetoothMap: Proxy object disconnected
08-30 15:28:50.822  1351  1351 D MapProfile: Bluetooth service disconnected
08-30 15:28:50.822  2676  2781 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:28:50.822  2676  2781 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:28:50.822  2676  2781 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:28:50.822  2676  2781 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:28:50.822  2676  2781 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:28:50.822  2676  2781 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 15:28:50.822  2676  2696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 15:28:50.823  2676  2676 V BluetoothAdapterState: isTurningOff()=true
08-30 15:28:50.823  2676  2676 V BluetoothAdapterState: isTurningOn()=false
08-30 15:28:50.823  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:28:50.823  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:28:50.823  2676  2676 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 15:28:50.823  2676  2696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 15:28:50.824  2676  2676 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:28:50.824  2676  2676 V BluetoothAdapterState: isTurningOff()=true
08-30 15:28:50.824  2676  2676 V BluetoothAdapterState: isTurningOn()=false
08-30 15:28:50.824  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:28:50.824  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:28:50.824  2676  2676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 15:28:50.824  2676  2696 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 15:28:50.824  2676  2676 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:28:50.825  2676  2676 V BluetoothAdapterState: isTurningOff()=true
08-30 15:28:50.825  2676  2676 V BluetoothAdapterState: isTurningOn()=false
08-30 15:28:50.825  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:28:50.825  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:28:50.826  2676  2676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:28:50.826  2676  2676 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:28:50.827  2676  2676 D BluetoothMapService: MAP Service closeService in
,08-30 15:28:50.827  2676  2676 V BluetoothAdapterState: isTurningOff()=true
08-30 15:28:50.827  2676  2676 V BluetoothAdapterState: isTurningOn()=false
08-30 15:28:50.827  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:28:50.827  2676  2676 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:28:50.828  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 15:28:50.828  2676  2691 D BluetoothAdapterProperties: Setting state to 15
08-30 15:28:50.828  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 15:28:50.829   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:28:50.829  1351  2032 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:28:50.829  2676  2691 I BluetoothAdapterState: Entering BleOnState
08-30 15:28:50.830  2676  2676 D BluetoothMapService: cleanup()
08-30 15:28:50.830  2676  2676 D BluetoothMapService: MAP Service closeService in
,08-30 15:28:50.830  1955  2151 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:28:50.831   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 15:28:50.831   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 15:28:50.832   873  2274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-30 15:28:50.832  1351  2108 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:28:50.833   403   403 E Parcel  : Reading a NULL string not supported here.
08-30 15:28:50.834   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:28:50.835   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 15:28:50.836   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:28:50.836  1351  1363 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 15:28:50.837   873  2289 D DhcpClient: Receive thread stopped
08-30 15:28:50.839  1351  2108 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:28:50.841   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:28:50.843   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 15:28:50.845  1351  2032 D BluetoothPan: onBluetoothStateChange on: false
08-30 15:28:50.850  1351  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:28:50.850   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 15:28:50.850   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:28:50.850   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 15:28:50.851  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:28:50.851  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:28:50.851  2676  2691 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 15:28:50.852  2676  2691 D BluetoothAdapterProperties: Setting state to 16
08-30 15:28:50.852  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 15:28:50.852  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.852  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:28:50.853  2676  2691 D BluetoothAdapterProperties: onBleDisable
08-30 15:28:50.853  2676  2691 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:28:50.853  2676  2693 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 15:28:50.854  2676  2696 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:28:50.854  2676  2781 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 15:28:50.854  2676  2781 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:28:50.854  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:28:50.855  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:28:50.855  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:50.855  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:28:50.857  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.857  1849  2281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:28:50.857  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.858  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.858   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:28:50.859  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:50.880   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:28:50.890  3838  3838 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-30 15:28:50.897   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 15:28:50.898   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-30 15:28:50.898   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:28:50.901   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:28:50.903  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.904  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:50.904  3391  3391 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2bdba2e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 15:28:50.910  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:28:50.915   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d748ecd:true
,08-30 15:28:50.915  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:28:50.927   873  1961 I ActivityManager: Start proc 3858:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-30 15:28:50.935  3838  3838 D LocalBluetoothProfileManager: Adding local MAP profile
,08-30 15:28:50.939  3838  3838 D BluetoothMap: Create BluetoothMap proxy object
,08-30 15:28:50.943  3838  3838 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 15:28:50.948   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-30 15:28:50.949   873  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 15:28:50.949   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 15:28:50.958  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:28:50.964  3858  3858 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 15:28:50.967   873  1385 I ActivityManager: Killing 3211:com.google.android.gm/u0a78 (adj 15): empty #17
,08-30 15:28:51.062  2676  2696 I bt_hci  : shut_down
,08-30 15:28:51.062  2676  2702 D bt_hwcfg: hw_epilog_process
,08-30 15:28:51.070  2676  2702 I bt_vendor: low_power_mode_cb
,08-30 15:28:51.095  2676  2702 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 15:28:51.095  2676  2702 I bt_vendor: epilog_cb
,08-30 15:28:51.095  2676  2702 I bt_hci  : epilog_finished_callback
,08-30 15:28:51.100  2676  2696 I bt_hci_h4: hal_close
,08-30 15:28:51.102  2676  2696 I bt_userial_vendor: device fd = 51 close
,08-30 15:28:51.148  3858  3858 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.148  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.149  3858  3858 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244),
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.149  3858  3858 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.149  3858  3858 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.149  3858  3858 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.149  3858  3858 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.149  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.150  3858  3858 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.150  3858  3858 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.150  3858  3858 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.150  3858  3858 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:28:51.150  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 15:28:51.182   873  1960 I ActivityManager: Start proc 3889:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 15:28:51.183   873  1960 I ActivityManager: Killing 3391:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 15:28:51.237  2676  2693 D bt_stack_manager: event_shut_down_stack finished.
,08-30 15:28:51.238  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 15:28:51.239  2676  2691 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 15:28:51.239  2676  2676 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:28:51.240  2676  2676 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:28:51.240  2676  2676 D BtGatt.GattService: stop()
08-30 15:28:51.240  2676  2676 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 15:28:51.241  2676  2676 V BluetoothAdapterState: isTurningOff()=false
08-30 15:28:51.241  2676  2676 V BluetoothAdapterState: isTurningOn()=false
08-30 15:28:51.241  2676  2676 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:28:51.241  2676  2676 V BluetoothAdapterState: isBleTurningOff()=true
08-30 15:28:51.241  2676  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 15:28:51.241  2676  2691 D BluetoothAdapterProperties: Setting state to 10
08-30 15:28:51.241  2676  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 15:28:51.242  2676  2691 I BluetoothAdapterState: Entering OffState
,08-30 15:28:51.243   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 15:28:51.251  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:28:51.261  2676  2676 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 15:28:51.261  2676  2676 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 15:28:51.261  2676  2676 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 15:28:51.262  2676  2693 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 15:28:51.264  2676  2693 D bt_stack_manager: event_clean_up_stack finished.
,08-30 15:28:51.274  3889  3889 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 15:28:51.279  2676  2676 I art     : System.exit called, status: 0
,08-30 15:28:51.279  2676  2676 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 15:28:51.344   873  1683 I ActivityManager: Process com.android.bluetooth (pid 2676) has died
,08-30 15:28:51.360  3889  3889 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 15:28:51.389  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:28:51.410   873   884 I ActivityManager: Start proc 3916:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-30 15:28:51.420  3838  3838 D DockEventReceiver: finishStartingService: stopping service
08-30 15:28:51.422   873  2004 I ActivityManager: Killing 2783:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 15:28:51.474  3858  3877 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 15:28:51.555  3916  3916 D AdapterServiceConfig: Adding HeadsetService
,08-30 15:28:51.555  3916  3916 D AdapterServiceConfig: Adding A2dpService
,08-30 15:28:51.557  3916  3916 D AdapterServiceConfig: Adding HidService
,08-30 15:28:51.558  3916  3916 D AdapterServiceConfig: Adding HealthService
,08-30 15:28:51.560  3916  3916 D AdapterServiceConfig: Adding PanService
,08-30 15:28:51.560  3916  3916 D AdapterServiceConfig: Adding GattService
08-30 15:28:51.560  3916  3916 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 15:28:51.564   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee577ad:true
,08-30 15:28:51.565  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:28:51.605  1688  1688 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 15:28:51.608  1688  1688 D SystemUpdateService: onCreate
,08-30 15:28:51.623  1688  1688 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 15:28:51.626  1688  3930 I SystemUpdateService: active receiver: enabled
,08-30 15:28:51.630  1688  3930 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 15:28:51.633  1688  3930 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 15:28:51.633  1688  3930 I SystemUpdateService: now status is 0 (complete)
08-30 15:28:51.633  1688  3930 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 15:28:51.633  1688  3930 I SystemUpdateService: file has been verified
08-30 15:28:51.633  1688  3930 I SystemUpdateService: OTA package size = 12249756
,08-30 15:28:51.635  1688  1688 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 15:28:51.637  1688  2526 I iu.UploadsManager: num queued entries: 0
,08-30 15:28:51.637  1688  2526 I iu.UploadsManager: num updated entries: 0
,08-30 15:28:51.638  1688  2526 I iu.SyncManager: NEXT; no task
,08-30 15:28:51.638  1688  3930 I SystemUpdateService: showing system update notification
,08-30 15:28:51.650  1688  1688 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 15:28:51.652  1688  1688 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 15:28:51.665   873   883 I ActivityManager: Start proc 3932:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 15:28:51.669  1688  1688 D SystemUpdateService: onDestroy
,08-30 15:28:51.713  3932  3932 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 15:28:51.717  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:28:51.725  3932  3932 D SprintDMHelper: simOperator: 
,08-30 15:28:51.725  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 15:28:51.749   873  1683 I ActivityManager: Start proc 3944:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 15:28:51.750   873  1683 I ActivityManager: Killing 1705:android.process.acore/u0a5 (adj 15): empty #17
,08-30 15:28:51.893  2247  3958 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 15:28:51.905   873  1385 I ActivityManager: Start proc 3959:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 15:28:51.908   873  1961 I ActivityManager: Killing 3616:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 15:28:51.996  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 15:28:52.048  3959  3959 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 15:28:52.048  3959  3959 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 15:28:52.048  3959  3959 I GAv4    :   adb logcat -s GAv4
,08-30 15:28:52.066  3959  3959 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:28:52.074  3959  3959 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:28:52.102  3959  3977 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 15:28:52.199  3959  3959 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 15:28:52.237  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 15:28:52.244  3959  3959 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3389-3392)
,08-30 15:28:52.244  3959  3959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 15:28:52.254  3959  3959 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ea30ade}
,08-30 15:28:52.254  3959  3959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 15:28:52.254  3959  3959 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 15:28:52.261  3959  3959 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 15:28:52.262  3959  3959 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 15:28:52.278  3959  3959 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 15:28:52.288  3959  3959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 15:28:52.288  3959  3959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 15:28:52.288  3959  3959 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 15:28:52.288  3959  3959 I Adreno  : Build Date                       : 10/20/15
08-30 15:28:52.288  3959  3959 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 15:28:52.288  3959  3959 I Adreno  : Local Branch                     : M14
08-30 15:28:52.288  3959  3959 I Adreno  : Remote Branch                    : 
08-30 15:28:52.288  3959  3959 I Adreno  : Remote Branch                    : 
08-30 15:28:52.288  3959  3959 I Adreno  : Reconstruct Branch               : 
,08-30 15:28:52.345  3959  3959 I NSApplication: Starting up...
,08-30 15:28:52.354  3959  4005 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 15:28:52.386   873  1974 I ActivityManager: Start proc 4010:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 15:28:52.388   873  1974 I ActivityManager: Killing 3633:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 15:28:52.480  4010  4010 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 15:28:52.647   873   884 I ActivityManager: Killing 3418:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 15:28:53.786   873   884 D WifiService: setWifiEnabled: true pid=3766, uid=10000
,08-30 15:28:53.786   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:28:53.798   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-30 15:28:53.807  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:28:53.808  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:28:53.808  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:28:53.809  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:28:53.813  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:28:53.814  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:28:53.814  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:28:53.814  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:28:53.834   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-30 15:28:53.835   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 15:28:53.836   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 15:28:53.837   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:28:53.837   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 15:28:53.837   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 15:28:53.837   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 15:28:53.859   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 15:28:53.860   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.00 rxSuccessRate=13.88 delta 1000 -> 994
,08-30 15:28:53.861   372   871 D CommandListener: Setting iface cfg
,08-30 15:28:53.863   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 15:28:53.863   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
,08-30 15:28:53.867   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 15:28:53.867   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:28:53.876   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 15:28:53.877   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 15:28:53.877   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 15:28:53.946   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 15:28:53.953  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 15:28:54.379  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 15:28:54.422  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 15:28:54.424  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 15:28:54.432   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:28:54.446   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 15:28:54.446   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:28:54.446   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 15:28:54.465   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:28:54.478   372   871 D CommandListener: Setting iface cfg
,08-30 15:28:54.481   873  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 15:28:54.501   873  4035 D DhcpClient: Receive thread started
,08-30 15:28:54.503   873  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 15:28:54.504   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 15:28:54.591   873  1305 E native  : do suspend false
,08-30 15:28:54.610   873  2276 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 15:28:54.627   873  4035 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172689, domain null
,08-30 15:28:54.628   873  2276 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172689 seconds
,08-30 15:28:54.631   873  2276 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 15:28:54.653   873  4035 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 15:28:54.654   873  2276 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 15:28:54.659   372   871 D CommandListener: Setting iface cfg
,08-30 15:28:54.672   873  2276 D DhcpClient: Scheduling renewal in 86399s
,08-30 15:28:54.672   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 15:28:54.686   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 15:28:54.689   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 15:28:54.689   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 15:28:54.690   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 15:28:54.695   873  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 15:28:54.704   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 15:28:54.742   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 15:28:54.742   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 15:28:54.744   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 15:28:54.745   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 15:28:54.746   873  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 15:28:54.755   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 15:28:54.763   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 15:28:54.763   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-30 15:28:54.763   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-30 15:28:54.763   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: [],
,08-30 15:28:54.764   873  1307 D ConnectivityService:    accepting network in place of null
08-30 15:28:54.764   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,08-30 15:28:54.765   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 15:28:54.803   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:28:54.854   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:28:54.858   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 15:28:54.858   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:28:54.859   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 15:28:54.862   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:28:54.879  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:54.879  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:28:54.879  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:54.880  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:28:54.885  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:28:54.885  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:28:54.885  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:54.885  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:28:54.894  1688  1688 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 15:28:54.897  1688  1688 D SystemUpdateService: onCreate
,08-30 15:28:54.900  1688  1688 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 15:28:54.902  1688  4045 I SystemUpdateService: active receiver: enabled
,08-30 15:28:54.904  1688  4045 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 15:28:54.906  1688  4045 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 15:28:54.906  1688  4045 I SystemUpdateService: now status is 0 (complete)
08-30 15:28:54.906  1688  4045 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 15:28:54.906  1688  4045 I SystemUpdateService: file has been verified
08-30 15:28:54.907  1688  4045 I SystemUpdateService: OTA package size = 12249756
,08-30 15:28:54.913  1688  4045 I SystemUpdateService: showing system update notification
,08-30 15:28:54.925  1688  1688 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 15:28:54.928  1688  2526 I iu.UploadsManager: num queued entries: 0
,08-30 15:28:54.929  1688  2526 I iu.UploadsManager: num updated entries: 0
,08-30 15:28:54.930  1688  2526 I iu.SyncManager: NEXT; no task
,08-30 15:28:54.936  1688  1688 D SystemUpdateService: onDestroy
,08-30 15:28:54.939  1688  1688 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 15:28:54.940  1688  1688 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 15:28:54.942  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:28:54.945  1688  4049 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 15:28:54.945  1688  4049 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 15:28:54.946  1688  4049 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 15:28:54.952  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:28:54.954  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:28:54.961  3932  3932 D SprintDMHelper: simOperator: 
,08-30 15:28:54.961  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 15:28:54.992  1494  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 15:28:54.992  1494  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 15:28:54.992  1494  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 15:28:54.992  1494  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:28:55.015  1688  4049 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-30 15:28:55.859   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 15:28:56.792   873  1960 D WifiService: setWifiEnabled: false pid=3766, uid=10000
,08-30 15:28:56.792   873  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:28:56.814   873  4034 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137961, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 15:28:56.816  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 15:28:56.822   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 15:28:56.822   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 15:28:56.823   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:28:56.823   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:28:56.854   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:28:56.854   873  2276 D DhcpClient: Clearing IP address
08-30 15:28:56.856   372   871 D CommandListener: Setting iface cfg
,08-30 15:28:56.868   873  4035 D DhcpClient: Receive thread stopped
08-30 15:28:56.870   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 15:28:56.871   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 15:28:56.874   403   403 E Parcel  : Reading a NULL string not supported here.
08-30 15:28:56.883   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 15:28:56.884   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 15:28:56.886   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-30 15:28:56.890   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 15:28:56.893   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 15:28:56.898   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:28:56.898  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:28:56.898  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:28:56.898  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:56.898  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:28:56.899  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:28:56.899  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:28:56.900  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:28:56.900  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:28:56.910  1849  2281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:28:56.928   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:28:56.949   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:28:56.950   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 15:28:56.950   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:28:56.952   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:28:56.955  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:28:56.956  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:28:56.961  1688  1688 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 15:28:56.964  1688  1688 D SystemUpdateService: onCreate
,08-30 15:28:56.966  1688  1688 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 15:28:56.973  1688  4062 I SystemUpdateService: active receiver: enabled
,08-30 15:28:56.977  1688  1688 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 15:28:56.980  1688  4062 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 15:28:56.979  1688  2526 I iu.UploadsManager: num queued entries: 0
,08-30 15:28:56.982  1688  2526 I iu.UploadsManager: num updated entries: 0
,08-30 15:28:56.983  1688  2526 I iu.SyncManager: NEXT; no task
,08-30 15:28:56.998  1688  4062 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 15:28:57.007  1688  4062 I SystemUpdateService: now status is 0 (complete)
08-30 15:28:57.008  1688  4062 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 15:28:57.008  1688  4062 I SystemUpdateService: file has been verified
,08-30 15:28:57.009  1688  4062 I SystemUpdateService: OTA package size = 12249756
,08-30 15:28:57.014  1688  4062 I SystemUpdateService: showing system update notification
,08-30 15:28:57.016  1688  1688 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 15:28:57.017  1688  1688 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 15:28:57.019  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:28:57.030  3932  3932 D SprintDMHelper: simOperator: 
,08-30 15:28:57.030  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 15:28:57.038   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-30 15:28:57.040   873  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 15:28:57.070  3959  3959 I art     : Waiting for a blocking GC DisableMovingGc
,08-30 15:28:57.072  3959  3959 I art     : Starting a blocking GC DisableMovingGc
,08-30 15:28:57.091  1688  1688 D SystemUpdateService: onDestroy
,08-30 15:28:57.221  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:28:57.238  1494  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 15:28:57.238  1494  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 15:28:57.238  1494  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 15:28:57.238  1494  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:28:57.251  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 15:28:57.251  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 15:28:57.251  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 15:28:59.776   873  4033 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-30 15:28:59.777   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 15:28:59.845   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc2488b:true
,08-30 15:28:59.845  3916  3916 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 15:28:59.850  3916  3916 I bt_bluedroid: init
,08-30 15:28:59.851  3916  4070 I BluetoothAdapterState: Entering OffState
,08-30 15:28:59.856  3916  4071 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 15:28:59.857  3916  4071 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:28:59.857  3916  4071 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 15:28:59.857  3916  4071 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 15:28:59.859  3916  3916 I bt_bluedroid: get_profile_interface socket
,08-30 15:28:59.862  3916  3916 I bt_bluedroid: get_profile_interface sdp
,08-30 15:28:59.866  3916  3928 I bt_bluedroid: config_hci_snoop_log
,08-30 15:28:59.868   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 15:28:59.868  3916  4074 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:28:59.872  3916  4074 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:28:59.876  3916  4070 D BluetoothAdapterState: Current state: OFF, message: 0
08-30 15:28:59.876  3916  4070 D BluetoothAdapterProperties: Setting state to 14
,08-30 15:28:59.877  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 15:28:59.881  3916  4070 D BluetoothBondStateMachine: make
,08-30 15:28:59.886  3916  4075 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 15:28:59.892  3916  4070 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:28:59.893  3916  3916 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 15:28:59.897  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:28:59.898  3916  3916 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:28:59.899  3916  3916 D BtGatt.GattService: Received start request. Starting profile...
,08-30 15:28:59.899  3916  3916 D BtGatt.GattService: start()
08-30 15:28:59.900  3916  3916 I bt_bluedroid: get_profile_interface gatt
08-30 15:28:59.901  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:28:59.901  3916  3916 D BtGatt.AdvertiseManager: advertise manager created
,08-30 15:28:59.910  3916  3916 V BluetoothAdapterState: isTurningOff()=false
08-30 15:28:59.910  3916  3916 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:28:59.910  3916  3916 V BluetoothAdapterState: isBleTurningOn()=true
08-30 15:28:59.910  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:28:59.910  3916  4070 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 15:28:59.911  3916  4070 I bt_bluedroid: enable
,08-30 15:28:59.912  3916  4071 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 15:28:59.912  3916  4071 I bt_hci  : start_up
,08-30 15:28:59.919  3916  4071 I bt_vendor: alloc value 0xb39f9189
,08-30 15:28:59.919  3916  4071 I bt_vendor: init
08-30 15:28:59.919  3916  4071 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 15:28:59.919  3916  4071 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 15:28:59.981  2247  4051 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-30 15:28:59.981  2247  4051 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 15:28:59.986  2247  4051 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 15:29:00.026  3916  4071 D bt_hci  : start_up starting async portion
,08-30 15:29:00.027  3916  4078 I bt_hci  : event_finish_startup
08-30 15:29:00.027  3916  4078 I bt_hci_h4: hal_open
,08-30 15:29:00.028  3916  4078 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 15:29:00.039  3916  4078 I bt_userial_vendor: device fd = 51 open
,08-30 15:29:00.068  3916  4078 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:29:00.101  3916  4078 D bt_hwcfg: Chipset BCM4354A2
,08-30 15:29:00.101  3916  4078 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 15:29:00.102  3916  4078 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 15:29:00.777  3916  4078 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-30 15:29:00.779  3916  4078 D bt_hwcfg: Settlement delay -- 100 ms
08-30 15:29:00.779  3916  4078 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 15:29:00.896  3916  4078 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:29:00.897  3916  4078 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 15:29:00.926  3916  4078 I bt_hwcfg: vendor lib fwcfg completed
,08-30 15:29:00.927  3916  4078 I bt_vendor: firmware callback
08-30 15:29:00.927  3916  4078 I bt_hci  : firmware_config_callback
,08-30 15:29:00.939  3916  4080 I bt_btu  : btu_task pending for preload complete event
,08-30 15:29:00.940  3916  4080 I bt_btu_task: Bluetooth chip preload is complete
,08-30 15:29:00.940  3916  4080 I bt_btu  : btu_task received preload complete event
,08-30 15:29:00.950  3916  4080 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 15:29:00.950  3916  4080 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 15:29:00.951  3916  4080 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 15:29:00.951  3916  4080 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 15:29:00.951  3916  4080 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 15:29:00.951  3916  4080 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:29:00.952  3916  4080 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:29:00.952  3916  4080 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 15:29:00.952  3916  4080 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 15:29:00.952  3916  4080 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 15:29:00.953  3916  4080 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:29:00.953  3916  4080 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 15:29:00.953  3916  4080 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:29:00.954  3916  4080 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 15:29:00.954  3916  4080 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 15:29:01.085  3916  4080 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-30 15:29:01.085  3916  4080 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-30 15:29:01.096  3916  4074 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 15:29:01.102  3916  4074 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 15:29:01.103  3916  4074 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:29:01.106  3916  4074 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:29:01.112  3916  4074 D BluetoothAdapterProperties: Scan Mode:20
,08-30 15:29:01.113  3916  4074 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:29:01.113  3916  4074 D bt_hci  : do_postload posting postload work item
,08-30 15:29:01.114  3916  4078 I bt_hci  : event_postload
,08-30 15:29:01.114  3916  4078 I bt_vendor: sco_config_cb
,08-30 15:29:01.114  3916  4078 I bt_hci  : sco_config_callback postload finished.
08-30 15:29:01.114  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:01.116  3916  4074 D bt_bte_conf: Device ID record 1 : primary
08-30 15:29:01.116  3916  4074 D bt_bte_conf:   vendorId            = 000f
08-30 15:29:01.116  3916  4074 D bt_bte_conf:   vendorIdSource      = 0001
08-30 15:29:01.116  3916  4074 D bt_bte_conf:   product             = 1200
08-30 15:29:01.116  3916  4074 D bt_bte_conf:   version             = 1436
08-30 15:29:01.116  3916  4074 D bt_bte_conf:   clientExecutableURL = 
08-30 15:29:01.116  3916  4074 D bt_bte_conf:   serviceDescription  = 
08-30 15:29:01.116  3916  4074 D bt_bte_conf:   documentationURL    = 
08-30 15:29:01.116  3916  4074 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 15:29:01.116  3916  4071 D bt_stack_manager: event_start_up_stack finished
08-30 15:29:01.118  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:01.118  3916  4070 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 15:29:01.118  3916  4070 D BluetoothAdapterProperties: Setting state to 15
08-30 15:29:01.118  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 15:29:01.119  3916  4070 I BluetoothAdapterState: Entering BleOnState
08-30 15:29:01.119  3916  4078 I bt_vendor: low_power_mode_cb
08-30 15:29:01.124  3916  4070 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 15:29:01.124  3916  4070 D BluetoothAdapterProperties: Setting state to 11
08-30 15:29:01.125  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 15:29:01.129  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:01.131  3916  3916 D HeadsetService: Received start request. Starting profile...
,08-30 15:29:01.134  3916  3916 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 15:29:01.135  3916  3916 D HeadsetStateMachine: make,
08-30 15:29:01.142  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:01.144  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:01.150  3916  4070 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:29:01.161  3916  3916 D HeadsetStateMachine: max_hf_connections = 1
,08-30 15:29:01.162  3916  3916 I bt_bluedroid: get_profile_interface handsfree
,08-30 15:29:01.162  3916  4074 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 15:29:01.163  3916  4074 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 15:29:01.172  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:01.173  3916  3916 D A2dpService: Received start request. Starting profile...
,08-30 15:29:01.174  3916  3916 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 15:29:01.174  3916  3916 I bt_bluedroid: get_profile_interface avrcp
,08-30 15:29:01.181  3916  3916 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 15:29:01.181  3916  3916 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:29:01.181  3916  3916 D A2dpStateMachine: make
,08-30 15:29:01.183  3916  3916 I bt_bluedroid: get_profile_interface a2dp
,08-30 15:29:01.183  3916  4074 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 15:29:01.186  3916  4089 D A2dpStateMachine: Enter Disconnected: -2
,08-30 15:29:01.187  3916  3916 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 15:29:01.189  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:01.190  3838  3838 D BluetoothInputDevice: Proxy object connected
,08-30 15:29:01.191  3916  3916 D HidService: Received start request. Starting profile...
08-30 15:29:01.191  3916  3916 I bt_bluedroid: get_profile_interface hidhost
08-30 15:29:01.191  3916  3916 D HidService: setHidService(): set to: null
08-30 15:29:01.191  3916  4074 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
,08-30 15:29:01.191  3916  4074 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 15:29:01.192  3916  3916 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 15:29:01.194  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
08-30 15:29:01.194  3916  3916 D HealthService: Received start request. Starting profile...
,08-30 15:29:01.195  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:29:01.196  3916  3916 I bt_bluedroid: get_profile_interface health
,08-30 15:29:01.197  3916  3916 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 15:29:01.197  3838  3838 D HidProfile: Bluetooth service connected
,08-30 15:29:01.198  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:01.200  3838  3838 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:29:01.200  3916  3916 D PanService: Received start request. Starting profile...
,08-30 15:29:01.201  3916  3916 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 15:29:01.201  3916  3916 I bt_bluedroid: get_profile_interface pan
,08-30 15:29:01.201  3838  3838 D PanProfile: Bluetooth service connected
,08-30 15:29:01.202  3916  4074 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 15:29:01.206  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:01.209  3916  3916 D BluetoothMapService: Received start request. Starting profile...
,08-30 15:29:01.208  3838  3838 D BluetoothMap: Proxy object connected
08-30 15:29:01.209  3916  3916 D BluetoothMapService: start(),
,08-30 15:29:01.209  3838  3838 D MapProfile: Bluetooth service connected
08-30 15:29:01.209  3838  3838 D BluetoothMap: getConnectedDevices()
,08-30 15:29:01.210  3838  3838 D BluetoothMap: Bluetooth is Not enabled
08-30 15:29:01.212  3916  3916 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 15:29:01.213  3916  3916 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 15:29:01.213  3916  3916 D BluetoothMapAppObserver: createReceiver()
08-30 15:29:01.214  3916  3916 D BluetoothMapAppObserver: initObservers()
,08-30 15:29:01.214  3916  3916 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 15:29:01.221  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:29:01.222  3916  3916 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:01.222  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:01.222  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:01.224  3916  4086 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 15:29:01.224  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:29:01.224  3916  3916 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:01.224  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:01.224  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:01.224  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:01.225  3916  3916 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:01.226  3916  3916 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:01.226  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:01.226  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:01.226  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:29:01.226  3916  3916 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:01.226  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:01.226  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:01.226  3916  4070 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 15:29:01.227  3916  4070 D BluetoothAdapterProperties: ScanMode =  20
,08-30 15:29:01.227  3916  4070 D BluetoothAdapterProperties: State =  11
08-30 15:29:01.229  3916  4074 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:29:01.229  3916  4074 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:29:01.229  3916  4070 D BluetoothAdapterProperties: Setting state to 12
,08-30 15:29:01.229  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 15:29:01.231   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:29:01.231  1351  1364 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:29:01.232  3916  4070 I BluetoothAdapterState: Entering OnState
,08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:01.232  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:29:01.233  1351  1351 D BluetoothInputDevice: Proxy object connected
08-30 15:29:01.233  1351  1351 D HidProfile: Bluetooth service connected
,08-30 15:29:01.233  1955  1968 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:29:01.233  1351  2108 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 15:29:01.235   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 15:29:01.235  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:29:01.236  1351  1363 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:29:01.237  1351  1351 D BluetoothMap: Proxy object connected
08-30 15:29:01.237  1351  1351 D MapProfile: Bluetooth service connected
,08-30 15:29:01.237  1351  1351 D BluetoothMap: getConnectedDevices()
08-30 15:29:01.238  1351  2032 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:29:01.238   873   873 D BluetoothA2dp: Proxy object connected
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:01.239  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:29:01.240  3916  3916 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 15:29:01.241  3916  3916 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 15:29:01.241  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:29:01.242  3916  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:29:01.243  1351  1351 D BluetoothA2dp: Proxy object connected
08-30 15:29:01.243  1351  1364 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:29:01.244  3916  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:29:01.245  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:29:01.245  1351  1351 D PanProfile: Bluetooth service connected
,08-30 15:29:01.246  1351  2108 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:29:01.246  3916  3916 D ObexServerSockets: Succeed to create listening sockets 
08-30 15:29:01.246  3838  3849 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:29:01.246  3916  3916 D ObexServerSockets0: startAccept()
08-30 15:29:01.246  3916  3916 D ObexServerSockets0: prepareForNewConnect()
,08-30 15:29:01.249  3916  3916 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 15:29:01.249  3916  3916 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 15:29:01.249  3838  3851 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:29:01.250   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:29:01.250  3916  4095 D ObexServerSockets0: Accepting socket connection...
08-30 15:29:01.250  3838  3849 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 15:29:01.250  3916  4096 D ObexServerSockets0: Accepting socket connection...
08-30 15:29:01.250  3838  3851 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:29:01.251   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:29:01.252   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 15:29:01.254  3916  3916 D BluetoothMapService: onReceive
08-30 15:29:01.254  3916  3916 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:29:01.254  3916  3916 D BluetoothMapService: STATE_ON
08-30 15:29:01.254  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:01.256  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:01.257  3838  3838 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 15:29:01.265  3838  3838 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 15:29:01.270  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:29:01.273  3838  3838 D BluetoothA2dp: Proxy object connected
,08-30 15:29:01.275  3916  3916 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 15:29:01.275  3916  3916 D ObexServerSockets0: prepareForNewConnect()
08-30 15:29:01.276  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:29:01.280  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:29:01.285  1351  1351 D BluetoothPbap: Proxy object connected
,08-30 15:29:01.285  1351  1351 D PbapServerProfile: Bluetooth service connected
,08-30 15:29:01.285  3838  3838 D BluetoothPbap: Proxy object connected
,08-30 15:29:01.286  3838  3838 D PbapServerProfile: Bluetooth service connected
,08-30 15:29:01.292  3916  4101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:29:01.305  3916  4105 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:29:01.306  3916  4105 I BtOppRfcommListener: Accept thread started.
,08-30 15:29:01.333   873   873 D BluetoothHeadset: Proxy object connected
,08-30 15:29:01.333   873   873 D BluetoothHeadset: Proxy object connected
08-30 15:29:01.333  1955  1975 D BluetoothHeadset: Proxy object connected
,08-30 15:29:01.333  1955  2151 D BluetoothHeadset: Proxy object connected
08-30 15:29:01.333   873   873 D BluetoothHeadset: Proxy object connected
08-30 15:29:01.334  1351  2032 D BluetoothHeadset: Proxy object connected
,08-30 15:29:01.334  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-30 15:29:01.346  1351  1363 D BluetoothHeadset: Proxy object connected
08-30 15:29:01.346  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-30 15:29:01.350   873   890 D BluetoothHeadset: Proxy object connected
,08-30 15:29:01.352   873   890 D BluetoothHeadset: Proxy object connected
,08-30 15:29:01.368  3838  3849 D BluetoothHeadset: Proxy object connected
,08-30 15:29:01.369  3838  3838 D HeadsetProfile: Bluetooth service connected
,08-30 15:29:02.766   873  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-30 15:29:02.810  3916  4070 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 15:29:02.811  3916  4070 D BluetoothAdapterProperties: Setting state to 13
08-30 15:29:02.811  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:29:02.813  3916  4070 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 15:29:02.816  3916  4070 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:29:02.827  3916  3916 D BluetoothMapService: onReceive
,08-30 15:29:02.827  3916  3916 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:29:02.828  3916  3916 D BluetoothMapService: STATE_TURNING_OFF
,08-30 15:29:02.829  3916  3916 D BluetoothMapService: MAP Service closeService in
08-30 15:29:02.829  3916  3916 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 15:29:02.829  3916  3916 D ObexServerSockets0: shutdown(block = true)
08-30 15:29:02.831  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:02.831  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:29:02.832  3916  4095 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 15:29:02.833  3916  3916 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 15:29:02.834  3916  4096 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 15:29:02.835  3916  4083 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 15:29:02.835  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:29:02.836  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:29:02.836  3916  4074 D BluetoothAdapterProperties: Scan Mode:20
,08-30 15:29:02.836  3916  4070 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 15:29:02.838  3916  3916 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 15:29:02.838  3916  3916 I BtOppRfcommListener: stopping Accept Thread
08-30 15:29:02.839  3916  4105 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 15:29:02.840  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 15:29:02.841  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:02.842  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:29:02.842  3916  4105 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 15:29:02.844  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 15:29:02.844  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:29:02.848  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:02.848  3916  3916 D HeadsetService: Received stop request...Stopping profile...
,08-30 15:29:02.851  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:02.851   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 15:29:02.851   873   873 D BluetoothHeadset: Proxy object disconnected
08-30 15:29:02.852  3838  3851 D BluetoothHeadset: Proxy object disconnected
,08-30 15:29:02.853  1955  2151 D BluetoothHeadset: Proxy object disconnected
,08-30 15:29:02.853   873   873 D BluetoothHeadset: Proxy object disconnected
,08-30 15:29:02.854  1351  2032 D BluetoothHeadset: Proxy object disconnected
,08-30 15:29:02.855  3916  3916 D A2dpService: Received stop request...Stopping profile...
08-30 15:29:02.855  3916  4089 D A2dpStateMachine: Exit Disconnected: -1
,08-30 15:29:02.856   873   873 D BluetoothA2dp: Proxy object disconnected
,08-30 15:29:02.860  3916  3916 D HidService: Received stop request...Stopping profile...
,08-30 15:29:02.860  3916  3916 D HidService: Stopping Bluetooth HidService
,08-30 15:29:02.860  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:29:02.861  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:29:02.862  3916  3916 D HealthService: Received stop request...Stopping profile...
,08-30 15:29:02.862  3838  3838 D HeadsetProfile: Bluetooth service disconnected
,08-30 15:29:02.862  3838  3838 D BluetoothA2dp: Proxy object disconnected
08-30 15:29:02.861  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-30 15:29:02.863  3916  3916 V BluetoothAdapterState: isTurningOff()=true
,08-30 15:29:02.863  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-30 15:29:02.863  1351  1351 D BluetoothA2dp: Proxy object disconnected
,08-30 15:29:02.863  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:02.863  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:02.863  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-30 15:29:02.863  1351  1351 D HidProfile: Bluetooth service disconnected
,08-30 15:29:02.863  3916  3916 D PanService: Received stop request...Stopping profile...
08-30 15:29:02.864  3838  3838 D BluetoothInputDevice: Proxy object disconnected
,08-30 15:29:02.865  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:29:02.865  3838  3838 D HidProfile: Bluetooth service disconnected,
,08-30 15:29:02.865  1351  1351 D PanProfile: Bluetooth service disconnected
,08-30 15:29:02.865  3838  3838 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 15:29:02.865  3838  3838 D PanProfile: Bluetooth service disconnected
,08-30 15:29:02.867  3916  3916 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 15:29:02.867  3916  3916 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 15:29:02.867  3916  4080 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:29:02.867  3916  4080 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 15:29:02.867  3916  4080 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 15:29:02.867  3916  4074 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 15:29:02.867  3916  4074 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-30 15:29:02.869  3916  3916 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 15:29:02.869  3916  3916 D BluetoothMapService: stop()
,08-30 15:29:02.869  3916  3916 D BluetoothMapAppObserver: deinitObservers()
,08-30 15:29:02.869  3916  3916 D BluetoothMapAppObserver: removeReceiver()
08-30 15:29:02.871  1351  1351 D BluetoothMap: Proxy object disconnected
,08-30 15:29:02.871  1351  1351 D MapProfile: Bluetooth service disconnected
08-30 15:29:02.871  3838  3838 D BluetoothMap: Proxy object disconnected
08-30 15:29:02.871  3838  3838 D MapProfile: Bluetooth service disconnected
08-30 15:29:02.871  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-30 15:29:02.871  3916  3916 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:29:02.871  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:02.871  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:02.872  3916  4074 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 15:29:02.872  3916  4080 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 15:29:02.873  3916  4080 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 15:29:02.873  3916  4080 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 15:29:02.873  3916  4080 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 15:29:02.873  3916  4080 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 15:29:02.873  3916  4080 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 15:29:02.875  1351  1351 D BluetoothPbap: Proxy object disconnected
,08-30 15:29:02.875  1351  1351 D PbapServerProfile: Bluetooth service disconnected
,08-30 15:29:02.875  3916  3916 V BluetoothAdapterState: isTurningOff()=true
,08-30 15:29:02.875  3916  3916 V BluetoothAdapterState: isTurningOn()=false
,08-30 15:29:02.875  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:02.875  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:02.875  3916  3916 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 15:29:02.875  3916  4074 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 15:29:02.875  3838  3838 D BluetoothPbap: Proxy object disconnected
,08-30 15:29:02.875  3838  3838 D PbapServerProfile: Bluetooth service disconnected
,08-30 15:29:02.876  3916  3916 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:29:02.878  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-30 15:29:02.878  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-30 15:29:02.878  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:02.878  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:02.878  3916  3916 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:29:02.878  3916  4074 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 15:29:02.878  3916  3916 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:29:02.879  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-30 15:29:02.879  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-30 15:29:02.879  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:02.879  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:02.879  3916  3916 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:29:02.879  3916  3916 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:29:02.880  3916  3916 D BluetoothMapService: MAP Service closeService in
08-30 15:29:02.880  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-30 15:29:02.880  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-30 15:29:02.880  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:02.880  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:02.880  3916  4070 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 15:29:02.880  3916  4070 D BluetoothAdapterProperties: Setting state to 15
08-30 15:29:02.881  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 15:29:02.881  3916  3916 D BluetoothMapService: cleanup()
08-30 15:29:02.881  3916  3916 D BluetoothMapService: MAP Service closeService in
08-30 15:29:02.881   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:29:02.882  1351  2032 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:29:02.882  3916  4070 I BluetoothAdapterState: Entering BleOnState
08-30 15:29:02.882  1955  2105 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:29:02.882  1351  1363 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:29:02.883   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:29:02.883  1351  1364 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:29:02.884  3838  3849 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:29:02.884  1351  2108 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:29:02.885  1351  2032 D BluetoothPan: onBluetoothStateChange on: false
08-30 15:29:02.885  1351  1363 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:29:02.885  3838  3851 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:29:02.886  3838  3849 D BluetoothPan: onBluetoothStateChange on: false
08-30 15:29:02.886   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:29:02.887  3838  3851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:29:02.887  3838  3849 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:29:02.887  3838  3851 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:29:02.888   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:29:02.888  3916  4070 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 15:29:02.888  3916  4070 D BluetoothAdapterProperties: Setting state to 16
08-30 15:29:02.888  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 15:29:02.889  3916  4070 D BluetoothAdapterProperties: onBleDisable
08-30 15:29:02.889  3916  4070 I BluetoothAdapterState: Entering PendingCommandState
08-30 15:29:02.889  3916  4071 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
0,8-30 15:29:02.890  3916  4074 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:29:02.891  3916  4080 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 15:29:02.891  3916  4080 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 15:29:02.892  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:02.893  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:02.894  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:02.894  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 15:29:02.896  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:02.898  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:29:02.910  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:29:03.092  3916  4074 I bt_hci  : shut_down
,08-30 15:29:03.106  3916  4078 D bt_hwcfg: hw_epilog_process
,08-30 15:29:03.107  3916  4078 I bt_vendor: low_power_mode_cb
,08-30 15:29:03.132  3916  4078 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 15:29:03.132  3916  4078 I bt_vendor: epilog_cb
08-30 15:29:03.133  3916  4078 I bt_hci  : epilog_finished_callback
,08-30 15:29:03.139  3916  4074 I bt_hci_h4: hal_close
,08-30 15:29:03.141  3916  4074 I bt_userial_vendor: device fd = 51 close
,08-30 15:29:03.261  3916  4071 D bt_stack_manager: event_shut_down_stack finished.
,08-30 15:29:03.262  3916  4070 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 15:29:03.267  3916  4070 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 15:29:03.268  3916  3916 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:29:03.270  3916  3916 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:29:03.270  3916  3916 D BtGatt.GattService: stop()
,08-30 15:29:03.271  3916  3916 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 15:29:03.276  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:29:03.276  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-30 15:29:03.277  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:03.277  3916  3916 V BluetoothAdapterState: isBleTurningOff()=true
08-30 15:29:03.278  3916  4070 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 15:29:03.278  3916  4070 D BluetoothAdapterProperties: Setting state to 10
,08-30 15:29:03.279  3916  4070 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 15:29:03.281  3916  4070 I BluetoothAdapterState: Entering OffState
,08-30 15:29:03.282   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 15:29:03.312  3916  3916 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 15:29:03.313  3916  3916 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 15:29:03.313  3916  4071 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 15:29:03.323  3916  4071 D bt_stack_manager: event_clean_up_stack finished.
,08-30 15:29:03.324  3916  3916 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 15:29:03.329  3916  3916 I art     : System.exit called, status: 0
,08-30 15:29:03.330  3916  3916 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 15:29:03.384   873   883 I ActivityManager: Process com.android.bluetooth (pid 3916) has died
,08-30 15:29:05.807  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:29:05.807  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:08.815  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:29:08.816  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d793f3a added. We now have 6 listener(s)
,08-30 15:29:08.816  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:08.820  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:29:08.820  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ebfc7eb added. We now have 7 listener(s)
,08-30 15:29:08.821  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:08.822  3766  3817 I System.out: IsBluetoothEnabled
,08-30 15:29:08.835  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:08.891   873   890 I ActivityManager: Start proc 4116:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 15:29:08.972   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 15:29:08.978  1890  1890 I Keyboard.Facilitator: onFinishInput()
,08-30 15:29:08.990   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 15:29:08.990   873   893 I Adreno  : Build Date                       : 10/20/15
08-30 15:29:08.990   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 15:29:08.990   873   893 I Adreno  : Local Branch                     : M14
08-30 15:29:08.990   873   893 I Adreno  : Remote Branch                    : 
08-30 15:29:08.990   873   893 I Adreno  : Remote Branch                    : 
08-30 15:29:08.990   873   893 I Adreno  : Reconstruct Branch               : 
,08-30 15:29:09.030  4116  4116 D AdapterServiceConfig: Adding HeadsetService
,08-30 15:29:09.031  4116  4116 D AdapterServiceConfig: Adding A2dpService
,08-30 15:29:09.039  4116  4116 D AdapterServiceConfig: Adding HidService
,08-30 15:29:09.046  4116  4116 D AdapterServiceConfig: Adding HealthService
,08-30 15:29:09.048  4116  4116 D AdapterServiceConfig: Adding PanService
,08-30 15:29:09.048  4116  4116 D AdapterServiceConfig: Adding GattService
,08-30 15:29:09.049  4116  4116 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 15:29:09.051   280  1296 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (187 us)
,08-30 15:29:09.072   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423b7c5:true
08-30 15:29:09.073  4116  4116 D BluetoothAdapterState: make() - Creating AdapterState
08-30 15:29:09.078  4116  4116 I bt_bluedroid: init
,08-30 15:29:09.078  4116  4129 I BluetoothAdapterState: Entering OffState
,08-30 15:29:09.080  4116  4130 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 15:29:09.080  4116  4130 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:29:09.080  4116  4130 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 15:29:09.080  4116  4130 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 15:29:09.081  4116  4116 I bt_bluedroid: get_profile_interface socket
,08-30 15:29:09.082  4116  4116 I bt_bluedroid: get_profile_interface sdp
,08-30 15:29:09.084  4116  4127 I bt_bluedroid: config_hci_snoop_log
,08-30 15:29:09.085   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 15:29:09.087  4116  4133 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:29:09.090  4116  4133 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:29:09.091  4116  4129 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 15:29:09.091  4116  4129 D BluetoothAdapterProperties: Setting state to 14
,08-30 15:29:09.092  4116  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 15:29:09.095  4116  4129 D BluetoothBondStateMachine: make
,08-30 15:29:09.099  4116  4135 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 15:29:09.106  4116  4129 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:29:09.106  4116  4116 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-30 15:29:09.110  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
08-30 15:29:09.110  4116  4116 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:29:09.112  4116  4116 D BtGatt.GattService: Received start request. Starting profile...
08-30 15:29:09.112  4116  4116 D BtGatt.GattService: start()
,08-30 15:29:09.112  4116  4116 I bt_bluedroid: get_profile_interface gatt
,08-30 15:29:09.114  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:09.115  4116  4116 D BtGatt.AdvertiseManager: advertise manager created
,08-30 15:29:09.128  4116  4116 V BluetoothAdapterState: isTurningOff()=false
,08-30 15:29:09.128  4116  4116 V BluetoothAdapterState: isTurningOn()=false
08-30 15:29:09.129  4116  4116 V BluetoothAdapterState: isBleTurningOn()=true
08-30 15:29:09.129  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:09.131  4116  4129 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 15:29:09.132  4116  4129 I bt_bluedroid: enable
08-30 15:29:09.132  4116  4130 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 15:29:09.133  4116  4130 I bt_hci  : start_up
,08-30 15:29:09.141  4116  4130 I bt_vendor: alloc value 0xb3a6a189
,08-30 15:29:09.141  4116  4130 I bt_vendor: init
08-30 15:29:09.141  4116  4130 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 15:29:09.141  4116  4130 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 15:29:09.250  4116  4130 D bt_hci  : start_up starting async portion
,08-30 15:29:09.251  4116  4138 I bt_hci  : event_finish_startup
,08-30 15:29:09.251  4116  4138 I bt_hci_h4: hal_open
,08-30 15:29:09.251  4116  4138 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 15:29:09.259  4116  4138 I bt_userial_vendor: device fd = 51 open
,08-30 15:29:09.294  4116  4138 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:29:09.325  4116  4138 D bt_hwcfg: Chipset BCM4354A2
,08-30 15:29:09.326  4116  4138 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 15:29:09.326  4116  4138 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 15:29:09.721  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 15:29:09.721  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 15:29:09.758   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 15:29:09.759  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a9370 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@153e948, 16908290=android.view.AbsSavedState$1@153e948}, android:focusedViewId=100}]}]
08-30 15:29:09.759  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 15:29:09.759  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 15:29:09.759  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 15:29:09.777   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 15:29:09.783   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 15:29:09.783   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-30 15:29:09.783   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 15:29:09.797   873   882 I art     : Background partial concurrent mark sweep GC freed 19667(1590KB) AllocSpace objects, 12(356KB) LOS objects, 33% free, 28MB/43MB, paused 1.576ms total 107.960ms
,08-30 15:29:10.045   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 15:29:10.049   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 15:29:10.054   873  1332 D SurfaceControl: Excessive delay in setPowerMode(): 271ms
,08-30 15:29:10.058   873   893 I DreamManagerService: Entering dreamland.
,08-30 15:29:10.060   873   893 I PowerManagerService: Dozing...
,08-30 15:29:10.066   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 15:29:10.125   376  1276 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 15:29:10.125   376  1276 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 15:29:10.133  4116  4138 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-30 15:29:10.133  4116  4138 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 15:29:10.133  4116  4138 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 15:29:10.135   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:29:10.147   873  1305 E native  : do suspend false
,08-30 15:29:10.153  1937  4141 D NfcService: Discovery configuration equal, not updating.
,08-30 15:29:10.181   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:29:10.187   873  1305 E native  : do suspend true
,08-30 15:29:10.250  4116  4138 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 15:29:10.252  4116  4138 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 15:29:10.267   376  1314 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 15:29:10.267   376  1314 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 15:29:10.283  4116  4138 I bt_hwcfg: vendor lib fwcfg completed
08-30 15:29:10.283  4116  4138 I bt_vendor: firmware callback
08-30 15:29:10.283  4116  4138 I bt_hci  : firmware_config_callback
,08-30 15:29:10.298  4116  4143 I bt_btu  : btu_task pending for preload complete event
08-30 15:29:10.298  4116  4143 I bt_btu_task: Bluetooth chip preload is complete
08-30 15:29:10.299  4116  4143 I bt_btu  : btu_task received preload complete event
,08-30 15:29:10.308  4116  4143 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 15:29:10.308  4116  4143 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:29:10.309  4116  4143 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 15:29:10.309  4116  4143 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 15:29:10.309  4116  4143 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 15:29:10.310  4116  4143 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 15:29:10.310  4116  4143 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:29:10.310  4116  4143 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 15:29:10.310  4116  4143 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 15:29:10.310  4116  4143 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 15:29:10.311  4116  4143 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:29:10.311  4116  4143 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 15:29:10.311  4116  4143 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:29:10.311  4116  4143 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 15:29:10.312  4116  4143 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 15:29:10.458  4116  4143 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e7d9d
,08-30 15:29:10.459  4116  4143 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e7d9d 
,08-30 15:29:10.472  4116  4133 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 15:29:10.474  4116  4133 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 15:29:10.475  4116  4133 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 15:29:10.479  4116  4133 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 15:29:10.482  4116  4133 D BluetoothAdapterProperties: Scan Mode:20
,08-30 15:29:10.482  4116  4133 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:29:10.483  4116  4133 D bt_hci  : do_postload posting postload work item
08-30 15:29:10.483  4116  4138 I bt_hci  : event_postload
08-30 15:29:10.483  4116  4138 I bt_vendor: sco_config_cb
08-30 15:29:10.484  4116  4138 I bt_hci  : sco_config_callback postload finished.
08-30 15:29:10.487  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:10.488  4116  4133 D bt_bte_conf: Device ID record 1 : primary
08-30 15:29:10.488  4116  4133 D bt_bte_conf:   vendorId            = 000f
,08-30 15:29:10.488  4116  4133 D bt_bte_conf:   vendorIdSource      = 0001
08-30 15:29:10.488  4116  4133 D bt_bte_conf:   product             = 1200
08-30 15:29:10.488  4116  4133 D bt_bte_conf:   version             = 1436
,08-30 15:29:10.489  4116  4133 D bt_bte_conf:   clientExecutableURL = 
08-30 15:29:10.489  4116  4133 D bt_bte_conf:   serviceDescription  = 
08-30 15:29:10.489  4116  4133 D bt_bte_conf:   documentationURL    = 
,08-30 15:29:10.489  4116  4133 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 15:29:10.490  4116  4130 D bt_stack_manager: event_start_up_stack finished
,08-30 15:29:10.491  4116  4129 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-30 15:29:10.491  4116  4129 D BluetoothAdapterProperties: Setting state to 15
08-30 15:29:10.492  4116  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-30 15:29:10.492  4116  4138 I bt_vendor: low_power_mode_cb
08-30 15:29:10.493  4116  4129 I BluetoothAdapterState: Entering BleOnState
,08-30 15:29:10.499  4116  4129 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 15:29:10.499  4116  4129 D BluetoothAdapterProperties: Setting state to 11
,08-30 15:29:10.499  4116  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 15:29:10.508  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:10.511  4116  4116 D HeadsetService: Received start request. Starting profile...
,08-30 15:29:10.514  4116  4116 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:29:10.514  4116  4116 D HeadsetStateMachine: make
08-30 15:29:10.515  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:10.528  4116  4129 I BluetoothAdapterState: Entering PendingCommandState
,08-30 15:29:10.529  4116  4116 D HeadsetStateMachine: max_hf_connections = 1
,08-30 15:29:10.529  4116  4116 I bt_bluedroid: get_profile_interface handsfree
08-30 15:29:10.529  4116  4133 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-30 15:29:10.530  4116  4133 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 15:29:10.534  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:10.535  4116  4116 D A2dpService: Received start request. Starting profile...
08-30 15:29:10.536  4116  4116 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 15:29:10.536  4116  4116 I bt_bluedroid: get_profile_interface avrcp
,08-30 15:29:10.542  4116  4116 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 15:29:10.542  4116  4116 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:29:10.542  4116  4116 D A2dpStateMachine: make
,08-30 15:29:10.544  4116  4116 I bt_bluedroid: get_profile_interface a2dp
,08-30 15:29:10.544  4116  4133 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 15:29:10.546  4116  4154 D A2dpStateMachine: Enter Disconnected: -2
,08-30 15:29:10.547  4116  4116 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 15:29:10.547  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:10.548  4116  4116 D HidService: Received start request. Starting profile...
,08-30 15:29:10.548  4116  4116 I bt_bluedroid: get_profile_interface hidhost
,08-30 15:29:10.549  4116  4133 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c93e5
08-30 15:29:10.549  4116  4133 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 15:29:10.549  4116  4116 D HidService: setHidService(): set to: null
08-30 15:29:10.549  4116  4116 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 15:29:10.550  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
08-30 15:29:10.551  4116  4116 D HealthService: Received start request. Starting profile...,
,08-30 15:29:10.552  4116  4116 I bt_bluedroid: get_profile_interface health
08-30 15:29:10.553  4116  4116 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 15:29:10.553  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04,
08-30 15:29:10.554  4116  4116 D PanService: Received start request. Starting profile...
,08-30 15:29:10.554  4116  4116 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:29:10.554  4116  4116 I bt_bluedroid: get_profile_interface pan
,08-30 15:29:10.555  4116  4133 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 15:29:10.558  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:29:10.560  4116  4116 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:10.561  4116  4116 D BluetoothMapService: Received start request. Starting profile...
08-30 15:29:10.561  4116  4116 D BluetoothMapService: start()
,08-30 15:29:10.563  4116  4116 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 15:29:10.563  4116  4116 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 15:29:10.563  4116  4116 D BluetoothMapAppObserver: createReceiver()
08-30 15:29:10.564  4116  4116 D BluetoothMapAppObserver: initObservers()
08-30 15:29:10.564  4116  4116 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 15:29:10.570  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:10.571  4116  4116 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:10.571  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:10.571  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:10.572  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:10.572  4116  4116 V BluetoothAdapterState: isTurningOn()=true
08-30 15:29:10.572  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:10.572  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:10.572  4116  4151 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 15:29:10.572  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isTurningOn()=true
,08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isTurningOn()=true
08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:10.573  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
08-30 15:29:10.574  4116  4116 V BluetoothAdapterState: isTurningOff()=false
08-30 15:29:10.574  4116  4116 V BluetoothAdapterState: isTurningOn()=true
08-30 15:29:10.574  4116  4116 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 15:29:10.574  4116  4116 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 15:29:10.574  4116  4129 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 15:29:10.574  4116  4129 D BluetoothAdapterProperties: ScanMode =  20
08-30 15:29:10.574  4116  4129 D BluetoothAdapterProperties: State =  11
08-30 15:29:10.575  4116  4129 D BluetoothAdapterProperties: Setting state to 12
08-30 15:29:10.575  4116  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 15:29:10.576  4116  4133 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:29:10.576  4116  4133 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 15:29:10.577   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:29:10.577  4116  4129 I BluetoothAdapterState: Entering OnState
08-30 15:29:10.577  1351  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:29:10.579  1955  2151 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:29:10.579  1351  1351 D BluetoothInputDevice: Proxy object connected
08-30 15:29:10.579  1351  1351 D HidProfile: Bluetooth service connected
,08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:10.580  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:29:10.580  1351  2108 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:29:10.582   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:29:10.582  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:29:10.582  1351  1364 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:29:10.583   873   873 D BluetoothA2dp: Proxy object connected
08-30 15:29:10.585  3838  3849 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:29:10.586  1351  1351 D BluetoothMap: Proxy object connected
08-30 15:29:10.586  1351  1351 D MapProfile: Bluetooth service connected
08-30 15:29:10.586  1351  1351 D BluetoothMap: getConnectedDevices()
,08-30 15:29:10.589  1351  2032 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:29:10.589  3838  3838 D BluetoothA2dp: Proxy object connected
08-30 15:29:10.590  1351  1351 D BluetoothA2dp: Proxy object connected
08-30 15:29:10.590  1351  2108 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:29:10.591  4116  4116 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 15:29:10.591  4116  4116 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 15:29:10.592  1351  1363 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:29:10.592  3838  3851 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 15:29:10.593  4116  4116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:29:10.594  3838  3849 D BluetoothPan: onBluetoothStateChange on: true
,08-30 15:29:10.595   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:29:10.595  3838  4159 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:29:10.596  4116  4116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:29:10.596  3838  3851 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:29:10.597  4116  4116 D ObexServerSockets: Succeed to create listening sockets 
08-30 15:29:10.597  4116  4116 D ObexServerSockets0: startAccept()
08-30 15:29:10.597  4116  4116 D ObexServerSockets0: prepareForNewConnect()
,08-30 15:29:10.598  3838  4159 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 15:29:10.599  4116  4116 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 15:29:10.599  4116  4116 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 15:29:10.600   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 15:29:10.600  3838  3838 D BluetoothInputDevice: Proxy object connected
08-30 15:29:10.602  3838  3838 D HidProfile: Bluetooth service connected
08-30 15:29:10.601  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:29:10.602  1351  1351 D PanProfile: Bluetooth service connected
08-30 15:29:10.601  4116  4160 D ObexServerSockets0: Accepting socket connection...
08-30 15:29:10.602   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 15:29:10.601  4116  4161 D ObexServerSockets0: Accepting socket connection...
08-30 15:29:10.604  4116  4116 D BluetoothMapService: onReceive
08-30 15:29:10.604  4116  4116 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:29:10.604  4116  4116 D BluetoothMapService: STATE_ON
08-30 15:29:10.604  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:10.607  3838  3838 D BluetoothMap: Proxy object connected
08-30 15:29:10.607  3838  3838 D MapProfile: Bluetooth service connected
08-30 15:29:10.607  3838  3838 D BluetoothMap: getConnectedDevices()
,08-30 15:29:10.609  3838  3838 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:29:10.609  3838  3838 D PanProfile: Bluetooth service connected
,08-30 15:29:10.613  3838  3838 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 15:29:10.620  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:29:10.620  3838  3838 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:29:10.628  3838  3838 D BluetoothPbap: Proxy object connected
,08-30 15:29:10.628  3838  3838 D PbapServerProfile: Bluetooth service connected
08-30 15:29:10.629  4116  4116 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 15:29:10.629  4116  4116 D ObexServerSockets0: prepareForNewConnect()
,08-30 15:29:10.632  1351  1351 D BluetoothPbap: Proxy object connected
,08-30 15:29:10.632  1351  1351 D PbapServerProfile: Bluetooth service connected
,08-30 15:29:10.638  4116  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:29:10.660  4116  4170 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:29:10.663  4116  4170 I BtOppRfcommListener: Accept thread started.
,08-30 15:29:10.679   873   873 D BluetoothHeadset: Proxy object connected
08-30 15:29:10.679   873   873 D BluetoothHeadset: Proxy object connected
08-30 15:29:10.679  1955  2105 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.680  3838  3849 D BluetoothHeadset: Proxy object connected
08-30 15:29:10.680  1955  1968 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.681   873   873 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.681  3838  3838 D HeadsetProfile: Bluetooth service connected
08-30 15:29:10.681  1351  2032 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.682  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-30 15:29:10.693  1351  1364 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.693  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-30 15:29:10.695   873   890 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.697  3838  4159 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.697  3838  3838 D HeadsetProfile: Bluetooth service connected
,08-30 15:29:10.700   873   890 D BluetoothHeadset: Proxy object connected
,08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:10.864  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:29:10.874  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:29:10.878  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:29:10.878  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@77e73e1 added. We now have 8 listener(s)
08-30 15:29:10.879  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:10.885   873  1974 D WifiService: setWifiEnabled: false pid=3766, uid=10000
,08-30 15:29:10.885   873  1974 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:29:10.898  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:10.899   873  1684 D WifiService: setWifiEnabled: true pid=3766, uid=10000
08-30 15:29:10.900   873  1684 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:29:10.915   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:10.931  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:29:10.937  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:29:10.937   873  1305 D WifiConfigStore: loaded 0 passpoint configs
08-30 15:29:10.938   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 15:29:10.939   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 15:29:10.940   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:29:10.940   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 15:29:10.940   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 15:29:10.940   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 15:29:10.956   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.03 rxSuccessRate=0.06 delta 1000 -> 1000
08-30 15:29:10.956   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-30 15:29:10.957   873  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 15:29:10.960   372   871 D CommandListener: Setting iface cfg
,08-30 15:29:10.968   873  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,08-30 15:29:10.968   873  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 15:29:10.969   873  1305 E native  : do suspend true
,08-30 15:29:10.986   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 15:29:10.986   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:29:11.001   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 15:29:11.004   873  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 15:29:11.051   873  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 15:29:11.089   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 15:29:11.091  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 15:29:11.542  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 15:29:11.614  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 15:29:11.615  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 15:29:11.630   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 15:29:11.638   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 15:29:11.638   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:29:11.639   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 15:29:11.659   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 15:29:11.671   372   871 D CommandListener: Setting iface cfg
08-30 15:29:11.673   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 15:29:11.680   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 15:29:11.730   873  4178 D DhcpClient: Receive thread started
,08-30 15:29:11.820   873  1305 E native  : do suspend false
,08-30 15:29:11.839   873  2276 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 15:29:11.854   873  4178 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-30 15:29:11.856   873  2276 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-30 15:29:11.860   873  2276 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 15:29:11.875   873  4178 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 15:29:11.876   873  2276 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 15:29:11.882   372   871 D CommandListener: Setting iface cfg
,08-30 15:29:11.894   873  2276 D DhcpClient: Scheduling renewal in 86399s
,08-30 15:29:11.894   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 15:29:11.897   873  1305 E native  : do suspend true
,08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:29:11.919  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:29:11.921   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 15:29:11.923  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:29:11.925   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 15:29:11.926   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 15:29:11.928   873  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 15:29:11.940   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 15:29:11.944  3766  3817 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 15:29:11.946  3766  3817 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 15:29:11.951  3766  3817 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a9370 Bundle[{}]
,08-30 15:29:11.953  3766  3817 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 15:29:11.953  3766  3817 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 15:29:11.955  3766  3817 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 15:29:11.956  3766  3817 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 15:29:11.958  3766  3817 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 15:29:11.960  3766  3817 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 15:29:11.965   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 15:29:11.965   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 15:29:11.966  3766  3817 I System.out: Running OutgoingSocketThread
08-30 15:29:11.966   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 15:29:11.967  3766  4181 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,08-30 15:29:11.967   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 15:29:11.968  3766  4181 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40535
08-30 15:29:11.968  3766  4181 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 15:29:11.969   873  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 15:29:11.977   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 15:29:11.982   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 15:29:11.982   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 15:29:11.983   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 15:29:11.984   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 15:29:11.984   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-30 15:29:11.984   873  1307 D ConnectivityService:    accepting network in place of null
,08-30 15:29:11.985   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 15:29:11.997   873  4177 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153145, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 15:29:12.017   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:29:12.059   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 15:29:12.068   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 15:29:12.069   873  4175 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:400d:802::200e
08-30 15:29:12.069   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:29:12.077   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 15:29:12.082   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:29:12.101  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:29:12.103  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:29:12.115  1688  1688 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 15:29:12.123  1688  1688 D SystemUpdateService: onCreate
,08-30 15:29:12.128  1688  1688 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 15:29:12.140  1688  4188 I SystemUpdateService: active receiver: enabled
,08-30 15:29:12.150  1688  4188 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 15:29:12.155  1688  1688 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 15:29:12.157  1688  2526 I iu.UploadsManager: num queued entries: 0
,08-30 15:29:12.157  1688  2526 I iu.UploadsManager: num updated entries: 0
,08-30 15:29:12.160  1688  4188 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 15:29:12.160  1688  4188 I SystemUpdateService: now status is 0 (complete)
08-30 15:29:12.160  1688  4188 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 15:29:12.160  1688  4188 I SystemUpdateService: file has been verified
08-30 15:29:12.160  1688  4188 I SystemUpdateService: OTA package size = 12249756
,08-30 15:29:12.163   873  4175 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 13:29:12 GMT], X-Android-Received-Millis=[1472563752162], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472563752126]}
,08-30 15:29:12.165   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 15:29:12.166   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 15:29:12.166   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 15:29:12.166  1688  2526 I iu.SyncManager: NEXT; no task
08-30 15:29:12.168   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 15:29:12.176  1688  1688 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 15:29:12.177  1688  1688 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 15:29:12.180  1688  4188 I SystemUpdateService: showing system update notification
,08-30 15:29:12.182  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:29:12.184  1688  4191 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 15:29:12.184  1688  4191 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 15:29:12.187  3932  3932 D SprintDMHelper: simOperator: 
,08-30 15:29:12.187  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 15:29:12.188  1688  4191 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 15:29:12.198  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:29:12.200  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 15:29:12.224  1688  1688 D SystemUpdateService: onDestroy
,08-30 15:29:12.253  1494  3003 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 15:29:12.253  1494  3003 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 15:29:12.253  1494  3003 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 15:29:12.253  1494  3003 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 15:29:12.269  1688  4191 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-30 15:29:12.332  2247  4194 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 15:29:12.968  3766  3817 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,08-30 15:29:12.969  3766  3817 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,08-30 15:29:12.978  3766  3817 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-30 15:29:12.980  3766  3817 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 15:29:12.981  3766  3817 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,08-30 15:29:12.987  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:29:12.987  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92c1506 added. We now have 2 listener(s)
,08-30 15:29:12.989  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:29:12.989  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 15:29:12.989  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:29:12.989  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:29:12.989  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed0f7c7 added. We now have 9 listener(s)
08-30 15:29:12.990  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:12.990  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:29:12.994  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:29:13.000  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:29:13.003  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:29:13.003  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:29:13.004  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-30 15:29:13.004  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68d6d1d added. We now have 3 listener(s)
,08-30 15:29:13.007  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:13.007  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:29:13.007  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 15:29:13.007  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:29:13.008  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:29:13.008  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e47b92 added. We now have 10 listener(s)
08-30 15:29:13.008  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:13.008  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:29:13.008  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:29:13.008  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:29:13.009  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:29:13.009  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:29:13.009  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:29:13.009  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.009  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92c1506 removed from the list
08-30 15:29:13.009  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.009  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed0f7c7 removed from the list
,08-30 15:29:13.010  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:13.011  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:29:13.011  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.012  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.012  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.013  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.014  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:29:13.014  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:29:13.014  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed0f7c7 not in the list
08-30 15:29:13.015  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.015  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:13.017  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:29:13.017  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.017  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.018  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e47b92 removed from the list
,08-30 15:29:13.018  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:29:13.018  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.018  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:13.019  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.019  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68d6d1d removed from the list
,08-30 15:29:13.021  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:29:13.021  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddb4963 added. We now have 2 listener(s)
,08-30 15:29:13.027  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:29:13.027  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:29:13.027  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:29:13.028  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:29:13.028  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4c9960 added. We now have 9 listener(s)
08-30 15:29:13.028  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:13.029  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:29:13.033  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:29:13.039  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:29:13.041  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:29:13.041  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:29:13.042  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:29:13.043  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24abede added. We now have 3 listener(s)
,08-30 15:29:13.044  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:29:13.044  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:13.045  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:29:13.045  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:29:13.045  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:29:13.045  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daf18bf added. We now have 10 listener(s)
,08-30 15:29:13.045  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:29:13.046  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:29:13.046  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 15:29:13.046  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:29:13.046  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:29:13.046  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:29:13.048  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:13.050  3766  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 15:29:13.050  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:29:13.054  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:29:13.054  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 15:29:13.055  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:29:13.058  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:29:13.058  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 15:29:13.058  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:29:13.059  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:29:13.062  4116  4152 D BtGatt.GattService: registerClient() - UUID=3f9bd917-9fd2-4597-8f96-3fa74ae5a86a
,08-30 15:29:13.063  4116  4133 D BtGatt.GattService: onClientRegistered() - UUID=3f9bd917-9fd2-4597-8f96-3fa74ae5a86a, clientIf=5
,08-30 15:29:13.064  3766  3778 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 15:29:13.065  4116  4126 D BtGatt.GattService: start scan with filters
,08-30 15:29:13.067   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 15:29:13.069  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:29:13.069  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:29:13.069  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:29:13.070  4116  4137 D BtGatt.ScanManager: handling starting scan
08-30 15:29:13.070  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:29:13.072  4116  4137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f49cb04
,08-30 15:29:13.073  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:29:13.073  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:29:13.073  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:29:13.076  4116  4133 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 15:29:13.076  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.077  4116  4137 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 15:29:13.079  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:29:13.082  3766  3817 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 15:29:13.083  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:29:13.083  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 15:29:13.083  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:29:13.083  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 15:29:13.083  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 15:29:13.083  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:29:13.083  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:29:13.083  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 15:29:13.084  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:29:13.084  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:29:13.084  3766  3817 D BluetoothAdapter: STATE_ON
08-30 15:29:13.085  4116  4126 D BtGatt.GattService: stopScan() - queue size =1
,08-30 15:29:13.087  4116  4133 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 15:29:13.087  4116  4162 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:29:13.087  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.087  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 15:29:13.087  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:29:13.087  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 15:29:13.088  4116  4137 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 15:29:13.088  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:29:13.088  4116  4137 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 15:29:13.088  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:29:13.089  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:29:13.089  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 15:29:13.089  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:29:13.089  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:29:13.090  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:29:13.091  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 15:29:13.091  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:29:13.091  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:29:13.094  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:29:13.094  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:29:13.094  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:29:13.095  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:29:13.095  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.095  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:29:13.095  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.095  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddb4963 removed from the list
,08-30 15:29:13.095  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.095  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4c9960 removed from the list
08-30 15:29:13.095  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:29:13.095  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.096  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.096  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:13.097  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.097  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:29:13.097  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.097  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4c9960 not in the list
08-30 15:29:13.097  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.097  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.098  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:29:13.098  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.098  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:29:13.099  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daf18bf removed from the list
08-30 15:29:13.099  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:29:13.099  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.099  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.099  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 15:29:13.099  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24abede removed from the list
08-30 15:29:13.100  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:29:13.100  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c681db added. We now have 2 listener(s),
08-30 15:29:13.102  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:29:13.102  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:29:13.102  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:29:13.102  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:29:13.102  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4783478 added. We now have 9 listener(s)
08-30 15:29:13.103  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:13.103  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:29:13.106  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:29:13.110  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:29:13.113  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:29:13.114  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:29:13.114  4116  4133 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
08-30 15:29:13.114  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.114  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:29:13.114  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca9cbb6 added. We now have 3 listener(s)
,08-30 15:29:13.116  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:29:13.116  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 15:29:13.116  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:29:13.116  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:29:13.116  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:13.117  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52160b7 added. We now have 10 listener(s)
08-30 15:29:13.117  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:29:13.117  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:29:13.119  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:29:13.119  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:29:13.119  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:29:13.119  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:29:13.119  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:29:13.120  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:29:13.122  4116  4133 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 15:29:13.123  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.123  3766  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 15:29:13.123  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:29:13.127  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:29:13.127  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 15:29:13.127  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:29:13.130  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 15:29:13.130  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:29:13.130  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 15:29:13.131  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:29:13.136  4116  4162 D BtGatt.GattService: registerClient() - UUID=85f0e8d7-4a96-4592-9576-f202155ff424
,08-30 15:29:13.137  4116  4133 D BtGatt.GattService: onClientRegistered() - UUID=85f0e8d7-4a96-4592-9576-f202155ff424, clientIf=5
08-30 15:29:13.137  3766  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 15:29:13.137  4116  4152 D BtGatt.GattService: start scan with filters
,08-30 15:29:13.140  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 15:29:13.140  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 15:29:13.140  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:29:13.140  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:29:13.142  4116  4133 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 15:29:13.142  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.143  4116  4137 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:29:13.143  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 15:29:13.143  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:29:13.144  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 15:29:13.145  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:29:13.147  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:29:13.147  3766  3817 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 15:29:13.148  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:29:13.148  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:29:13.148  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:29:13.148  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:29:13.148  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.148  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 15:29:13.148  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.148  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c681db removed from the list
08-30 15:29:13.148  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.148  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4783478 removed from the list
08-30 15:29:13.149  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:29:13.149  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:29:13.149  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:29:13.149  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 15:29:13.149  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.149  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:29:13.150  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.150  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:29:13.150  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.150  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4783478 not in the list
,08-30 15:29:13.150  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:29:13.150  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:29:13.150  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:29:13.151  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:29:13.151  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 15:29:13.151  3766  3817 D BluetoothAdapter: STATE_ON
08-30 15:29:13.152  4116  4126 D BtGatt.GattService: stopScan() - queue size =0
08-30 15:29:13.152  4116  4127 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:29:13.153  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:29:13.153  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 15:29:13.153  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:29:13.153  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 15:29:13.153  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 15:29:13.156  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 15:29:13.156  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:29:13.156  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:29:13.156  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:29:13.157  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.157  4116  4133 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 15:29:13.157  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.157  4116  4137 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:29:13.158  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:29:13.158  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:29:13.158  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:29:13.158  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:29:13.158  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.158  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:29:13.158  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52160b7 removed from the list
08-30 15:29:13.158  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:29:13.158  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.158  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.158  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.159  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca9cbb6 removed from the list
08-30 15:29:13.159  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:29:13.159  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e15153 added. We now have 2 listener(s)
08-30 15:29:13.161  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:29:13.161  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:29:13.161  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:29:13.162  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:29:13.162  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e91a90 added. We now have 9 listener(s)
,08-30 15:29:13.162  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:13.162  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:29:13.164  4116  4133 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
08-30 15:29:13.164  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.166  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:29:13.166  4116  4137 D BtGatt.ScanManager: handling starting scan
,08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:29:13.172  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:29:13.176  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:29:13.176  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:29:13.179  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:29:13.179  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:13.179  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d929b8e added. We now have 3 listener(s)
,08-30 15:29:13.180  4116  4133 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 15:29:13.180  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.180  4116  4137 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 15:29:13.181  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:13.186  4116  4133 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 15:29:13.186  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.186  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 15:29:13.186  4116  4137 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:29:13.186  4116  4137 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 15:29:13.187  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:29:13.187  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:29:13.187  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:29:13.188  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5afaf added. We now have 10 listener(s)
,08-30 15:29:13.188  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:29:13.188  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:29:13.189  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:29:13.189  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:29:13.189  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:29:13.189  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 15:29:13.197  3766  3817 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 15:29:13.197  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:29:13.200  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 15:29:13.201  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 15:29:13.201  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:29:13.204  4116  4133 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 15:29:13.204  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.205  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 15:29:13.205  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 15:29:13.205  3766  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 15:29:13.205  3766  3817 D BluetoothAdapter: STATE_ON
,08-30 15:29:13.207  4116  4127 D BtGatt.GattService: registerClient() - UUID=396b952f-0f94-406d-8b97-f1aeb0c35806
,08-30 15:29:13.207  4116  4133 D BtGatt.GattService: onClientRegistered() - UUID=396b952f-0f94-406d-8b97-f1aeb0c35806, clientIf=5
,08-30 15:29:13.208  3766  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 15:29:13.208  4116  4126 D BtGatt.GattService: start scan with filters
08-30 15:29:13.210  4116  4133 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 15:29:13.210  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.211  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 15:29:13.211  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 15:29:13.211  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 15:29:13.211  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 15:29:13.214  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:29:13.214  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 15:29:13.214  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 15:29:13.216  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 15:29:13.217  4116  4133 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 15:29:13.217  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.218  4116  4137 D BtGatt.ScanManager: stopping BLe Batch
,08-30 15:29:13.220  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 15:29:13.220  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:29:13.220  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:29:13.220  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:29:13.220  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.220  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 15:29:13.220  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.221  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e15153 removed from the list
08-30 15:29:13.221  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.221  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e91a90 removed from the list
,08-30 15:29:13.221  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:29:13.221  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:29:13.221  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.222  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 15:29:13.222  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:29:13.222  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:29:13.223  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.223  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:29:13.223  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.223  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e91a90 not in the list
,08-30 15:29:13.223  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:29:13.223  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 15:29:13.223  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:29:13.224  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:29:13.224  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 15:29:13.224  4116  4133 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 15:29:13.224  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.224  4116  4137 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:29:13.224  3766  3817 D BluetoothAdapter: STATE_ON
08-30 15:29:13.225  4116  4126 D BtGatt.GattService: stopScan() - queue size =0
,08-30 15:29:13.225  4116  4152 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 15:29:13.225  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:29:13.225  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 15:29:13.225  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 15:29:13.226  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 15:29:13.226  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 15:29:13.226  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:29:13.227  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 15:29:13.227  3766  3817 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:29:13.227  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 15:29:13.227  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:13.228  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:29:13.228  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:29:13.228  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:29:13.228  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:29:13.229  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:29:13.229  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:29:13.229  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5afaf removed from the list
,08-30 15:29:13.229  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:29:13.229  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.229  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.229  4116  4133 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 15:29:13.229  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.229  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.229  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d929b8e removed from the list
08-30 15:29:13.230  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:29:13.230  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a797cb added. We now have 2 listener(s)
08-30 15:29:13.230  4116  4137 D BtGatt.ScanManager: handling starting scan
08-30 15:29:13.231  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:29:13.231  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:29:13.231  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:29:13.232  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:29:13.232  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9daba8 added. We now have 9 listener(s)
,08-30 15:29:13.232  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:13.232  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:29:13.234  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:29:13.236  4116  4133 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 15:29:13.236  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.237  4116  4137 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:29:13.239  3766  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:29:13.241  3766  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:29:13.241  3766  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 15:29:13.241  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 15:29:13.241  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1a8e66 added. We now have 3 listener(s)
,08-30 15:29:13.242  4116  4133 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,08-30 15:29:13.242  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 15:29:13.242  4116  4137 D BtGatt.ScanManager: Starting BLE batch scan
08-30 15:29:13.242  4116  4137 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 15:29:13.243  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:13.244  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 15:29:13.244  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 15:29:13.244  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:29:13.245  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 15:29:13.245  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195e5a7 added. We now have 10 listener(s)
,08-30 15:29:13.245  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:29:13.245  3766  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:29:13.245  3766  3817 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:29:13.245  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 15:29:13.245  3766  3817 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:29:13.245  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 15:29:13.246  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:29:13.246  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 15:29:13.246  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 15:29:13.246  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a797cb removed from the list
,08-30 15:29:13.246  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:29:13.246  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9daba8 removed from the list
,08-30 15:29:13.246  3766  3817 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:29:13.246  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:13.247  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:29:13.247  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:13.248  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:29:13.248  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:29:13.248  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:29:13.249  3766  3817 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9daba8 not in the list
,08-30 15:29:13.249  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:29:13.249  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:29:13.250  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:29:13.250  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 15:29:13.250  3766  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 15:29:13.250  3766  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@195e5a7 removed from the list
,08-30 15:29:13.250  3766  3817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:29:13.250  3766  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:29:13.250  3766  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:29:13.250  3766  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:29:13.250  3766  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1a8e66 removed from the list
,08-30 15:29:13.251  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 15:29:13.251  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 15:29:13.251  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 15:29:13.251  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-30 15:29:13.252  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-30 15:29:13.252  3766  3817 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:29:13.253  4116  4133 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 15:29:13.253  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.257  3766  4200 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
08-30 15:29:13.257  3766  4200 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
,08-30 15:29:13.257  3766  4200 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 15:29:13.258  4116  4133 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 15:29:13.258  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.261  3766  4201 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,08-30 15:29:13.261  3766  4201 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
08-30 15:29:13.261  3766  4201 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 15:29:13.263  3766  3817 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-30 15:29:13.263  3766  3817 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 15:29:13.263  3766  3817 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 15:29:13.263  3766  3817 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-30 15:29:13.263  3766  3817 D com.test.thalitest.ThaliTestRunner: Total duration: 22918 ms
08-30 15:29:13.265  3766  3817 I jxcore-log: *Native tests were executed*
08-30 15:29:13.265  3766  3817 I jxcore-log: 
08-30 15:29:13.265  3766  3817 I jxcore-log: Total number of executed tests:  80
08-30 15:29:13.265  3766  3817 I jxcore-log: 
08-30 15:29:13.265  3766  3817 I jxcore-log: Number of passed tests:  80
08-30 15:29:13.265  3766  3817 I jxcore-log: 
,08-30 15:29:13.266  3766  3817 I jxcore-log: Number of failed tests:  0
08-30 15:29:13.266  3766  3817 I jxcore-log: 
08-30 15:29:13.266  4116  4133 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 15:29:13.266  3766  3817 I jxcore-log: Number of ignored tests:  0
08-30 15:29:13.266  3766  3817 I jxcore-log: ,
08-30 15:29:13.266  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.266  4116  4137 D BtGatt.ScanManager: stopping BLe Batch
08-30 15:29:13.266  3766  3817 I jxcore-log: Total duration:  22918
,08-30 15:29:13.266  3766  3817 I jxcore-log: 
08-30 15:29:13.266  3766  3817 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 15:29:13.266  3766  3817 I jxcore-log: 
08-30 15:29:13.270  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.270  3766  3817 I jxcore-log: 
,08-30 15:29:13.273  4116  4133 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 15:29:13.273  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.273  4116  4137 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 15:29:13.273  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.273  3766  3817 I jxcore-log: 
08-30 15:29:13.275  3766  3766 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 15:29:13.276  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.276  3766  3817 I jxcore-log: 
08-30 15:29:13.277  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.277  3766  3817 I jxcore-log: 
08-30 15:29:13.278  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.278  3766  3817 I jxcore-log: 
08-30 15:29:13.280  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.280  3766  3817 I jxcore-log: 
08-30 15:29:13.282  4116  4133 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 15:29:13.282  4116  4133 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 15:29:13.282  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.282  3766  3817 I jxcore-log: 
08-30 15:29:13.284  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.284  3766  3817 I jxcore-log: 
08-30 15:29:13.285  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.285  3766  3817 I jxcore-log: 
08-30 15:29:13.286  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:29:13.286  3766  3817 I jxcore-log: 
08-30 15:29:13.287  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:29:13.287  3766  3817 I jxcore-log: 
08-30 15:29:13.288  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:29:13.288  3766  3817 I jxcore-log: 
08-30 15:29:13.289  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.289  3766  3817 I jxcore-log: 
08-30 15:29:13.290  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.290  3766  3817 I jxcore-log: 
08-30 15:29:13.290  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.290  3766  3817 I jxcore-log: 
08-30 15:29:13.291  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.291  3766  3817 I jxcore-log: 
08-30 15:29:13.293  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.293  3766  3817 I jxcore-log: 
08-30 15:29:13.293  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.293  3766  3817 I jxcore-log: 
08-30 15:29:13.294  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.294  3766  3817 I jxcore-log: 
08-30 15:29:13.295  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.295  3766  3817 I jxcore-log: 
08-30 15:29:13.296  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.296  3766  3817 I jxcore-log: 
08-30 15:29:13.296  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:29:13.296  3766  3817 I jxcore-log: 
08-30 15:29:13.297  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:29:13.297  3766  3817 I jxcore-log: 
08-30 15:29:13.297  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:29:13.297  3766  3817 I jxcore-log: 
08-30 15:29:13.298  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.298  3766  3817 I jxcore-log: 
08-30 15:29:13.299  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.299  3766  3817 I jxcore-log: 
08-30 15:29:13.299  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.299  3766  3817 I jxcore-log: 
08-30 15:29:13.300  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.300  3766  3817 I jxcore-log: 
08-30 15:29:13.301  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.301  3766  3817 I jxcore-log: 
08-30 15:29:13.301  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:29:13.301  3766  3817 I jxcore-log: 
,08-30 15:29:13.592  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:29:13.597  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:29:13.597  3766  3817 I jxcore-log: 
,08-30 15:29:13.658  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:29:13.661  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:29:13.661  3766  3817 I jxcore-log: 
,08-30 15:29:13.728  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:29:13.732  3766  3817 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:29:13.732  3766  3817 I jxcore-log: 
,08-30 15:29:13.947  4202  4202 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 15:29:13.951  4202  4202 D AndroidRuntime: CheckJNI is OFF
,08-30 15:29:13.996  4202  4202 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 15:29:14.042  4202  4202 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 15:29:14.065  4202  4202 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 15:29:14.075   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 15:29:14.076   873   886 I ActivityManager: Killing 3766:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 15:29:14.187   873   896 W PackageSettings: Skipping PackageSetting{313ddc1 com.example.hello/10273} due to missing metadata
,08-30 15:29:14.192   873  1510 I WindowState: WIN DEATH: Window{7d59b36 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 15:29:14.192   873   884 D GraphicsStats: Buffer count: 2
08-30 15:29:14.193   873  1306 D WifiService: Client connection lost with reason: 4
,08-30 15:29:14.249   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 15:29:14.250   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 15:29:14.251   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-30 15:29:14.251   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 15:29:14.251   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.251   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.251   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 15:29:14.251   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 15:29:14.251   873   886 I ActivityManager:   Force finishing activity ActivityRecord{11aa85f u0 com.test.thalitest/.MainActivity t2}
,08-30 15:29:14.252   873   896 I art     : Starting a blocking GC Explicit
,08-30 15:29:14.266   873  2008 W ActivityManager: Spurious death for ProcessRecord{26d4fbc 0:com.test.thalitest/u0a0}, curProc for 3766: null
,08-30 15:29:14.299   873   896 I art     : Explicit concurrent mark sweep GC freed 55418(3MB) AllocSpace objects, 10(296KB) LOS objects, 33% free, 29MB/43MB, paused 791us total 46.920ms
,08-30 15:29:14.333   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 15:29:14.341  4202  4202 I art     : System.exit called, status: 0
,08-30 15:29:14.341  4202  4202 I AndroidRuntime: VM exiting with result code 0.
,08-30 15:29:14.346   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 15:29:14.375   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 15:29:14.379  4116  4116 D BluetoothMapAppObserver: onReceive
08-30 15:29:14.379  4116  4116 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 15:29:14.382  1890  1890 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 15:29:14.385  1849  2261 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 15:29:14.386   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 15:29:14.386  3602  3602 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 15:29:14.403  1890  4213 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 15:29:14.407  1955  1955 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 15:29:14.415   873  2021 I ActivityManager: Start proc 4216:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 15:29:14.420  1890  4213 I Decoder : createOrResetDecoder
,08-30 15:29:14.467  1494  1494 I ConfigService: onCreate
,08-30 15:29:14.469  4216  4216 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 15:29:14.470  1494  4229 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 15:29:14.470  1494  4229 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 15:29:14.470  1494  4229 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-30 15:29:14.471   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 15:29:14.472  1494  4229 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-30 15:29:14.482   873  1684 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3766 uid 10000
,08-30 15:29:14.483  1890  1890 I Keyboard.Facilitator: onFinishInput()
,08-30 15:29:14.488  1890  4213 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 15:29:14.517   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 15:29:14.518   873   885 E PackageManager: Failed to write settings, restoring backup
08-30 15:29:14.518   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 15:29:14.518   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 15:29:14.518   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 15:29:14.518   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 15:29:14.518   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 15:29:14.518   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.518   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.518   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:29:14.521  1967  2107 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 15:29:14.523   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-30 15:29:14.523   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 15:29:14.523   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:29:14.523   873   886 E DropBoxManagerService: 	... 13 more
,08-30 15:29:14.534   873  1385 I ActivityManager: Start proc 4233:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 15:29:14.534  1967  2107 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 15:29:14.534  1967  2107 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1967
08-30 15:29:14.534  1967  2107 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.534  1967  2107 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:29:14.536   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 15:29:14.538  4216  4216 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 15:29:14.539   873  4242 E DropBoxManagerService: Can't write: system_app_crash
08-30 15:29:14.539   873  4242 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:29:14.539   873  4242 E DropBoxManagerService: 	... 5 more
,08-30 15:29:14.541  1967  2107 I Process : Sending signal. PID: 1967 SIG: 9
,08-30 15:29:14.572  1890  4213 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 15:29:14.573  1890  4213 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-30 15:29:14.573  1890  4213 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 15:29:14.577  1890  4213 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 15:29:14.577  1890  4213 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 15:29:14.578  1890  4213 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 15:29:14.578  1890  4213 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 15:29:14.578  1890  4213 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-30 15:29:14.579  1890  4213 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-30 15:29:14.579  1890  4213 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 15:29:14.579  1890  4213 I Keyboard.Facilitator.RecurringTaskScheduler: run(),
08-30 15:29:14.579  1890  4213 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 15:29:14.579  1890  4213 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 15:29:14.657  4216  4251 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 15:29:14.664  4216  4231 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.664  4216  4231 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.665  4216  4231 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:29:14.676   873  1385 D GraphicsStats: Buffer count: 1
,08-30 15:29:14.676   873  1683 I WindowState: WIN DEATH: Window{1572a96 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 15:29:14.686   873   884 I ActivityManager: Start proc 4252:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 15:29:14.687   873  1385 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1967) has died
,08-30 15:29:14.688   873  1385 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-30 15:29:14.689   873  1385 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 15:29:14.711  4216  4231 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 15:29:14.711   873   886 I ActivityManager: Start proc 4264:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 15:29:14.727  1688  4250 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 15:29:14.735  1688  4250 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 15:29:14.740  4252  4252 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 15:29:14.742   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-30 15:29:14.756  1494  1494 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 15:29:14.756  1494  1494 D AndroidRuntime: Shutting down VM
08-30 15:29:14.757  1494  1494 E AndroidRuntime: FATAL EXCEPTION: main
08-30 15:29:14.757  1494  1494 E AndroidRuntime: Process: com.google.process.gapps, PID: 1494
08-30 15:29:14.757  1494  1494 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	,at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 15:29:14.757  1494  1494 E AndroidRuntime: 	... 8 more
,08-30 15:29:14.759  1494  1494 I Process : Sending signal. PID: 1494 SIG: 9
,08-30 15:29:14.760   873  4278 E DropBoxManagerService: Can't write: system_app_crash
08-30 15:29:14.760   873  4278 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:29:14.760   873  4278 E DropBoxManagerService: 	... 5 more
,08-30 15:29:14.762  4216  4251 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.762  4216  4251 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:29:14.762  4264  4264 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723),
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:29:14.762  4264  4264 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 15:29:14.762  4264  4264 D AndroidRuntime: Shutting down VM
08-30 15:29:14.762  4216  4251 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
,08-30 15:29:14.762  4216  4251 E AndroidRuntime: Process: android.process.acore, PID: 4216
08-30 15:29:14.762  4216  4251 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.762  4216  4251 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 15:29:14.765   873  4280 E DropBoxManagerService: Can't write: system_app_crash
08-30 15:29:14.765   873  4280 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:29:14.765   873  4280 E DropBoxManagerService: 	... 5 more
08-30 15:29:14.770  4264  4264 E AndroidRuntime: FATAL EXCEPTION: main
08-30 15:29:14.770  4264  4264 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4264
08-30 15:29:14.770  4264  4264 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at andr,oid.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 15:29:14.770  4264  4264 E AndroidRuntime: 	... 10 more
08-30 15:29:14.771   873  2020 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 15:29:14.772  4264  4264 I Process : Sending signal. PID: 4264 SIG: 9
08-30 15:29:14.772   873  4281 E DropBoxManagerService: Can't write: system_app_crash
08-30 15:29:14.772   873  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 15:29:14.772   873  4281 E DropBoxManagerService: 	... 5 more
,08-30 15:29:14.775  4216  4251 I Process : Sending signal. PID: 4216 SIG: 9
08-30 15:29:14.783   278   278 E lowmemorykiller: Error writing /proc/4216/oom_score_adj; errno=22
08-30 15:29:14.784   278   278 E lowmemorykiller: Error writing /proc/4216/oom_score_adj; errno=22
08-30 15:29:14.784   873  2008 I ActivityManager: Killing 3660:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 15:29:14.789  1688  4250 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 15:29:14.789  1688  4250 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 15:29:14.820   873  1306 D WifiService: Client connection lost with reason: 4
,08-30 15:29:14.842   873  2004 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4264) has died
,08-30 15:29:14.843   873  2004 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 15:29:14.846   873   884 I ActivityManager: Process com.google.process.gapps (pid 1494) has died
08-30 15:29:14.846   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-30 15:29:14.846   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-30 15:29:14.847   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
08-30 15:29:14.847   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
,08-30 15:29:14.849   873  1683 I ActivityManager: Process android.process.acore (pid 4216) has died
,08-30 15:29:14.849   873  1683 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40997ms
,08-30 15:29:14.853   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
