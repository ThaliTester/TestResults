#### Test 82894682e70646c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,09-06 19:03:21.154  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:03:21.173  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:03:21.178  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:03:21.238  1497  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-06 19:03:21.238  1497  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-06 19:03:21.239  1497  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:03:21.239  1497  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-06 19:03:21.299  3549  3549 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-06 19:03:21.300  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-06 19:03:21.301  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-06 19:03:21.885  3835  3835 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-06 19:03:21.889  3835  3835 D AndroidRuntime: CheckJNI is OFF
09-06 19:03:21.925  3835  3835 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-06 19:03:21.968  3835  3835 I Radio-JNI: register_android_hardware_Radio DONE
09-06 19:03:21.988  3835  3835 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 19:03:21.993   871  2013 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:03:22.036  2041  2413 W SearchService: Abort, client detached.
09-06 19:03:22.052  2041  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6b5984
09-06 19:03:22.052  2041  2343 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-06 19:03:22.052  2041  2041 I HotwordDetector: Closing mic
09-06 19:03:22.052  3835  3835 D AndroidRuntime: Shutting down VM
09-06 19:03:22.097   871  1691 I ActivityManager: Start proc 3844:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-06 19:03:22.114   374  2345 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-06 19:03:22.115   374  2345 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-06 19:03:22.121   374  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-06 19:03:22.124  2041  2335 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-06 19:03:22.124  2041  2342 I MicroRecognitionRnrImpl: Detection finished
09-06 19:03:22.188  3844  3844 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-06 19:03:22.219  3844  3844 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-06 19:03:22.227  3844  3844 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1239-1242)
09-06 19:03:22.227  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:03:22.247  3844  3844 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23a8b4}
09-06 19:03:22.248  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:03:22.248  3844  3844 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:03:22.255  3844  3844 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-06 19:03:22.257  3844  3844 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:03:22.290  3844  3844 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 19:03:22.308  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:03:22.308  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:03:22.308  3844  3844 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:03:22.308  3844  3844 I Adreno  : Build Date                       : 10/20/15
09-06 19:03:22.308  3844  3844 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:03:22.308  3844  3844 I Adreno  : Local Branch                     : M14
09-06 19:03:22.308  3844  3844 I Adreno  : Remote Branch                    : 
09-06 19:03:22.308  3844  3844 I Adreno  : Remote Branch                    : 
09-06 19:03:22.308  3844  3844 I Adreno  : Reconstruct Branch               : 
,09-06 19:03:22.391   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7121508:true
,09-06 19:03:22.475  3844  3844 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 19:03:22.497  3844  3844 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-06 19:03:22.588  3844  3884 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-06 19:03:22.609  3844  3869 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-06 19:03:22.645  3844  3884 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 19:03:22.695   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +629ms
,09-06 19:03:22.698  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-06 19:03:22.788  3844  3844 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3844
,09-06 19:03:22.900   871  1690 I ActivityManager: Killing 3242:com.google.android.gm/u0a78 (adj 15): empty #17
,09-06 19:03:22.968   871  1690 I ActivityManager: Killing 2997:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-06 19:03:23.002  3844  3844 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:03:23.114  3844  3886 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684014800
,09-06 19:03:23.119  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:03:23.119  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:03:23.119  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:03:23.119  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:03:23.119  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 19:03:23.119  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3173f8 added. We now have 1 listener(s)
,09-06 19:03:23.123  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-06 19:03:23.124  3844  3886 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:03:23.124  3844  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:03:23.125  3844  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:03:23.128  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63d4637 added. We now have 1 listener(s)
09-06 19:03:23.128  3844  3886 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:23.131   871  1304 D WifiService: New client listening to asynchronous messages
,09-06 19:03:23.131  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:03:23.131  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:03:23.132  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:03:23.132  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:03:23.132  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:03:23.134  3844  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-06 19:03:23.134  3844  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-06 19:03:23.139  3844  3886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:23.139  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:23.139  3844  3886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:03:23.139  3844  3886 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:23.140  3844  3886 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:03:23.141  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:23.143  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:23.161  3844  3844 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:03:24.145  3844  3894 W jxcore-log: Initializing JXcore engine
09-06 19:03:24.145  3844  3894 W jxcore-log: JXcore engine is ready
,09-06 19:03:24.188  3894  3894 W Thread-338: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-06 19:03:24.188  3894  3894 W Thread-338: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11935]" dev="sockfs" ino=11935 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-06 19:03:24.188  3894  3894 W Thread-338: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 19:03:24.188  3894  3894 W Thread-338: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24992]" dev="sockfs" ino=24992 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-06 19:03:24.205  3844  3894 W jxcore-log: Starting JXcore engine
,09-06 19:03:24.327  3844  3894 W jxcore-log: Platform android
09-06 19:03:24.327  3844  3894 W jxcore-log: 
,09-06 19:03:24.328  3844  3894 W jxcore-log: Process ARCH arm
09-06 19:03:24.328  3844  3894 W jxcore-log: 
,09-06 19:03:24.603  3844  3894 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:03:24.603  3844  3894 I jxcore-log: 
,09-06 19:03:24.603  3844  3894 W jxcore-log: JXcore engine is started
,09-06 19:03:24.610  3844  3886 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:03:24.613  3844  3844 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:03:25.223   871  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-06 19:03:29.652  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:03:29.656  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:03:29.688  1497  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-06 19:03:29.688  1497  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 19:03:29.688  1497  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:03:29.688  1497  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:03:29.715  3013  3906 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-06 19:03:29.715  3013  3906 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jdm.a(PG:82)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jcs.o(PG:406)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jcn.a(PG:1379)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jcs.i(PG:143)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at blb.a(PG:3937)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at czp.a(PG:18188)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at czp.a(PG:9081)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at czq.run(PG:1686)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:03:29.715  3013  3906 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jdj.a(PG:4091)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jdj.a(PG:1125)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jdm.a(PG:77)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	... 12 more
09-06 19:03:29.715  3013  3906 E HttpOperation: Caused by: faj: BadAuthentication
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at fal.a(PG:38)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	at jdj.a(PG:4089)
09-06 19:03:29.715  3013  3906 E HttpOperation: 	... 14 more
,09-06 19:03:29.765  1497  2412 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-06 19:03:29.765  1497  2412 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 19:03:29.766  1497  2412 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:03:29.766  1497  2412 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:03:29.790  3013  3906 E HttpOperation: [getmobileexperiments] Unexpected exception
09-06 19:03:29.790  3013  3906 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jdm.a(PG:82)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jcs.o(PG:406)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jcn.a(PG:1379)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jcs.i(PG:143)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at hec.a(PG:42)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at hee.a(PG:102)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at czr.a(PG:65)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at kka.a(PG:108)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at czp.a(PG:19176)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at czp.a(PG:9081)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at czq.run(PG:1686)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:03:29.790  3013  3906 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jdj.a(PG:4091)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jdj.a(PG:1125)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jdm.a(PG:77)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	... 15 more
09-06 19:03:29.790  3013  3906 E HttpOperation: Caused by: faj: BadAuthentication
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at fal.a(PG:38)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	at jdj.a(PG:4089)
09-06 19:03:29.790  3013  3906 E HttpOperation: 	... 17 more
,09-06 19:03:29.790  3013  3906 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-06 19:03:29.790  3013  3906 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jdm.a(PG:82)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jcs.o(PG:406)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jcn.a(PG:1379)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jcs.i(PG:143)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at hec.a(PG:42)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at hee.a(PG:102)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at czr.a(PG:65)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at kka.a(PG:108)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at czp.a(PG:19176)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at czp.a(PG:9081)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at czq.run(PG:1686)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jdj.a(PG:4091)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jdj.a(PG:1125)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jdm.a(PG:77)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	... 15 more
09-06 19:03:29.790  3013  3906 E ExperimentLoader: Caused by: faj: BadAuthentication
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at fal.a(PG:38)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	at jdj.a(PG:4089)
09-06 19:03:29.790  3013  3906 E ExperimentLoader: 	... 17 more
,09-06 19:03:29.889   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128451, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-06 19:03:34.311  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:03:34.311  3844  3894 I jxcore-log: 
,09-06 19:03:34.315  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:03:34.315  3844  3894 I jxcore-log: 
,09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:34.330  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:34.337  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:34.345  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:03:34.345  3844  3894 I jxcore-log: 
,09-06 19:03:34.347  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:03:34.347  3844  3894 I jxcore-log: 
,09-06 19:03:34.858  3844  3894 D executeNativeTests: Running unit tests
,09-06 19:03:34.934  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:34.934  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 added. We now have 2 listener(s)
,09-06 19:03:34.935  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:03:34.936  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:34.936  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:34.936  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:34.936  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 added. We now have 2 listener(s)
09-06 19:03:34.936  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:34.937  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:34.948  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:34.959  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:34.963  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:34.964  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:34.966  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:03:34.968  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:03:34.969  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:03:34.973  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:34.973  3844  3894 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:03:34.974  3844  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-06 19:03:34.974  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-06 19:03:34.974  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:03:34.975  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 19:03:34.977  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:34.979  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:34.979  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:03:34.980  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:34.980  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:34.980  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:34.981  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:34.982  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 removed from the list
,09-06 19:03:34.982  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:34.982  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 removed from the list
09-06 19:03:34.985  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:34.985  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:34.985  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:34.988  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:34.989  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:34.991  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:34.992  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:34.992  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:34.992  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:34.996  3844  3894 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-06 19:03:34.997  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:34.997  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:34.998  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:34.998  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:34.999  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:34.999  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:34.999  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:34.999  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:34.999  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:34.999  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.000  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.000  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.000  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.000  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.003  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.003  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.003  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.004  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:35.018  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:03:35.018  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:03:35.018  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-06 19:03:35.018  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:03:35.018  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:03:35.019  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:03:35.019  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:03:35.019  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:03:35.019  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-06 19:03:35.019  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:03:35.019  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:03:35.020  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:03:35.020  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:03:35.020  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-06 19:03:35.020  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:03:35.020  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:03:35.021  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:03:35.021  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-06 19:03:35.021  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:03:35.022  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:03:35.022  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.022  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.022  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.023  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.023  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.023  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.023  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.023  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.023  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.023  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.023  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.023  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.023  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.023  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.026  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.026  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.026  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.026  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.028  3844  3894 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:03:35.035  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:35.044  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:35.048  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:35.048  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:35.050  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:35.050  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:35.050  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:35.050  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:35.050  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:03:35.052  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:35.056  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.060  3844  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:03:35.060  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:03:35.075  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:03:35.080  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:03:35.082  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:03:35.089  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-06 19:03:35.095  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-06 19:03:35.095  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:03:35.096  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:03:35.097  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:35.098  3844  3894 D BluetoothAdapter: STATE_ON
,09-06 19:03:35.106  2709  2723 D BtGatt.GattService: registerClient() - UUID=4c9b928b-95d6-4705-a367-06eeabb7031d
,09-06 19:03:35.107  2709  2762 D BtGatt.GattService: onClientRegistered() - UUID=4c9b928b-95d6-4705-a367-06eeabb7031d, clientIf=5
,09-06 19:03:35.108  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:03:35.110  2709  2721 D BtGatt.GattService: start scan with filters
,09-06 19:03:35.116  2709  2767 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:35.117  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:03:35.118  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:35.118  2709  2767 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
09-06 19:03:35.118  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:35.119  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:35.127  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:35.129  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:35.129  2709  2762 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:03:35.130  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.130  2709  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:03:35.131  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:35.133  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:35.137  3844  3894 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:03:35.141  2709  2762 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:03:35.141  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.142  2709  2767 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:03:35.142  2709  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 19:03:35.143  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:35.144  3844  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:03:35.144  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.145  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:03:35.145  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.145  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:03:35.145  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:35.146  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:35.146  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:35.146  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:35.149  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:03:35.149  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:35.150  3844  3894 D BluetoothAdapter: STATE_ON
09-06 19:03:35.151  2709  2918 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:03:35.153  2709  2723 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:03:35.153  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:35.153  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:03:35.154  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:35.154  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:35.154  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:03:35.156  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:35.156  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:35.157  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:35.157  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:03:35.158  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:35.163  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:35.163  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:35.163  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:35.163  2709  2762 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:03:35.164  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.164  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.164  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.164  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:35.164  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.164  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.165  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:35.165  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.165  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.165  3844  3894 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:03:35.168  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:35.170  2709  2762 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 19:03:35.170  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:35.175  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:35.179  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:35.179  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:35.179  2709  2762 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 19:03:35.179  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.180  2709  2767 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:35.180  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:35.180  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:03:35.180  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:35.180  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:35.180  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:03:35.184  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:35.188  2709  2762 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:03:35.188  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.188  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.188  2709  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 19:03:35.189  3844  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:03:35.190  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:03:35.194  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:35.195  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-06 19:03:35.195  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:35.196  2709  2762 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:03:35.196  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.201  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:03:35.201  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:35.201  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:35.202  3844  3894 D BluetoothAdapter: STATE_ON
,09-06 19:03:35.205  2709  2909 D BtGatt.GattService: registerClient() - UUID=8290a57c-4491-45c8-abd7-d73f661b1297
,09-06 19:03:35.206  2709  2762 D BtGatt.GattService: onClientRegistered() - UUID=8290a57c-4491-45c8-abd7-d73f661b1297, clientIf=5
09-06 19:03:35.210  3844  3890 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:03:35.211  2709  2917 D BtGatt.GattService: start scan with filters
,09-06 19:03:35.216  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:03:35.216  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:35.216  2709  2767 D BtGatt.ScanManager: handling starting scan
09-06 19:03:35.216  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:35.216  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:35.222  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:35.223  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-06 19:03:35.223  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:35.225  2709  2762 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:03:35.225  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.225  2709  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:03:35.227  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:35.231  3844  3894 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:03:35.233  2709  2762 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 19:03:35.233  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.234  2709  2767 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:35.234  2709  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 19:03:35.236  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.236  3844  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:03:35.236  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:35.236  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:03:35.236  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.237  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:03:35.237  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:35.237  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:03:35.237  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:35.237  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:35.238  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:03:35.238  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:03:35.239  3844  3894 D BluetoothAdapter: STATE_ON
,09-06 19:03:35.241  2709  2721 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:03:35.242  2709  2909 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 19:03:35.244  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:03:35.245  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:35.245  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:35.245  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:03:35.246  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:03:35.249  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:35.249  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:35.249  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:35.250  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:03:35.250  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:35.250  2709  2762 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:03:35.251  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-06 19:03:35.252  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:35.253  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:35.253  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:35.253  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:35.254  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.254  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:35.254  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
,09-06 19:03:35.254  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.255  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.255  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:03:35.255  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.257  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.257  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.257  2709  2762 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:03:35.257  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.262  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:03:35.262  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.262  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:35.262  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.263  3844  3894 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:03:35.265  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:35.268  2709  2762 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 19:03:35.268  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.268  2709  2767 D BtGatt.ScanManager: stopping BLe Batch,
,09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:35.271  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:35.273  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:35.273  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:35.274  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:35.275  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:03:35.275  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:35.275  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:35.275  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:03:35.276  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.276  2709  2762 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:03:35.276  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.277  2709  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:03:35.278  3844  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:03:35.278  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:03:35.279  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:35.285  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:35.285  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:03:35.285  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:35.286  2709  2762 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 19:03:35.286  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.293  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:03:35.294  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:03:35.294  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:35.295  3844  3894 D BluetoothAdapter: STATE_ON
,09-06 19:03:35.299  2709  2723 D BtGatt.GattService: registerClient() - UUID=520e6913-baf7-4df8-804e-f82200c8be4b
,09-06 19:03:35.300  2709  2762 D BtGatt.GattService: onClientRegistered() - UUID=520e6913-baf7-4df8-804e-f82200c8be4b, clientIf=5
09-06 19:03:35.300  3844  3890 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:03:35.301  2709  2909 D BtGatt.GattService: start scan with filters
,09-06 19:03:35.305  2709  2767 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:35.305  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:03:35.305  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:03:35.305  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:03:35.306  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:35.313  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:35.313  2709  2762 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:03:35.313  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.314  2709  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:03:35.315  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:35.315  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:03:35.317  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:03:35.320  2709  2762 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:03:35.320  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.320  2709  2767 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:35.320  2709  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:03:35.321  3844  3894 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:03:35.321  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.321  3844  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:03:35.322  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.322  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:03:35.322  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.322  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:03:35.322  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:35.322  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:35.322  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:35.322  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:35.322  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:03:35.322  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:03:35.323  3844  3894 D BluetoothAdapter: STATE_ON
09-06 19:03:35.324  2709  2909 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:03:35.324  2709  2917 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:03:35.325  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:35.325  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:35.325  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:35.325  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:03:35.325  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:03:35.327  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:35.327  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:35.327  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:35.327  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:03:35.329  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:35.330  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:35.330  3844  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:03:35.330  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.330  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.331  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.331  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.331  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:35.331  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.331  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.331  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.331  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.331  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:35.331  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.331  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:35.331  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:35.332  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.332  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.333  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.333  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.334  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.334  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.335  3844  3894 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:03:35.336  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.336  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.336  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.336  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.336  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.336  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.336  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.336  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.336  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.337  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.337  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.337  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.337  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.337  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.339  2709  2762 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:03:35.340  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.340  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:03:35.340  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.340  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:35.340  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:35.341  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:03:35.341  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.341  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:35.341  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:03:35.341  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:35.342  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.342  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.342  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.342  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:35.342  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.342  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:03:35.342  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.342  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.342  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.342  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.343  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.343  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.343  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.343  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.343  3844  3894 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-06 19:03:35.344  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:35.344  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.344  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.344  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.344  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.344  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.344  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.344  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.344  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.344  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:03:35.344  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.344  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.345  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.345  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.345  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.345  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.345  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.345  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:35.346  3844  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:03:35.346  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.346  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.346  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.346  2709  2762 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:03:35.346  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.347  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.347  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.347  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.347  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.347  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.347  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.347  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.347  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.347  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.347  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.347  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.348  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.348  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.348  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.348  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.349  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:03:35.349  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:03:35.349  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:03:35.349  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:03:35.349  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:03:35.350  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:03:35.350  3844  3894 I io.jxcore.node.Connecti,onHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.350  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.350  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.350  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.350  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.350  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.350  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.351  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.351  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.351  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.351  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.351  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.351  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.351  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.352  2709  2762 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:03:35.352  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.352  2709  2767 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:35.353  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.353  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.353  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.353  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.353  3844  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:03:35.354  3844  3894 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-06 19:03:35.354  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:03:35.357  3844  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:03:35.357  3844  3894 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-06 19:03:35.357  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:03:35.357  2709  2762 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:03:35.357  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:03:35.357  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:35.357  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:03:35.358  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-06 19:03:35.359  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:03:35.360  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:03:35.360  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:03:35.360  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:03:35.360  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-06 19:03:35.360  3844  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:03:35.360  3844  3894 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:03:35.360  3844  3894 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:03:35.360  3844  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:03:35.360  3844  3894 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:03:35.361  3844  3894 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-06 19:03:35.361  3844  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:03:35.361  3844  3894 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:03:35.361  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:03:35.361  2709  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:03:35.367  2709  2762 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:03:35.367  2709  2762 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:35.367  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:03:35.369  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:03:35.369  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:03:35.369  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:03:35.369  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:03:35.370  3844  3894 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:03:35.370  3844  3894 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:03:35.370  3844  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 402)
09-06 19:03:35.370  3844  3894 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:03:35.371  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.371  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.371  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.371  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.371  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.372  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.372  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:03:35.372  3844  3914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:03:35.373  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.373  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.374  3844  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 402
09-06 19:03:35.374  3844  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 402)
09-06 19:03:35.374  3844  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 402)
,09-06 19:03:35.374  3844  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 402)
09-06 19:03:35.375  2709  2906 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-06 19:03:35.373  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.375  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.375  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.375  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.375  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.375  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.376  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.376  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.376  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.377  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:35.377  3844  3894 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:03:35.377  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.377  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.377  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.379  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.379  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.379  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.379  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.379  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.379  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.379  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.379  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.379  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.379  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.379  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.380  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.380  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.380  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:35.381  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.381  3844  3894 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:03:35.382  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.382  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.382  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.382  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.382  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.382  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.382  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.382  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.382  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.382  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.382  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.382  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.382  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.383  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.384  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.384  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.384  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.384  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.385  3844  3894 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:03:35.385  3844  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:03:35.385  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:03:35.385  3844  3894 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:03:35.385  3844  3894 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:03:35.385  3844  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:03:35.385  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:03:35.385  3844  3894 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:03:35.385  3844  3894 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:03:35.385  3844  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:03:35.385  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:03:35.385  3844  3894 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:03:35.386  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.386  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false -, Stop operation: Should start/stop everything
09-06 19:03:35.386  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.386  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.386  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.386  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.386  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.386  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.386  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.386  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.386  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.386  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.386  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.386  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.388  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.388  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.388  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.388  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.388  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.388  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:35.388  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.388  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.389  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.389  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.389  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.389  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.389  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.389  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:35.389  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.389  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.389  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.389  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.389  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.389  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.389  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.389  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.390  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.390  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.390  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.390  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.390  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.390  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.390  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.390  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.390  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.390  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.390  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.391  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.391  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.391  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.392  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.393  3844  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:03:35.393  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:35.393  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:03:35.394  3844  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:03:35.394  3844  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:03:35.394  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:03:35.394  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-06 19:03:35.394  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:35.395  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.395  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:03:35.395  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:03:35.395  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:03:35.395  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.395  3844  3894 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:03:35.395  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:03:35.395  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.395  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.395  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:35.395  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:35.395  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:35.395  3844  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:03:35.395  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.395  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.396  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:35.396  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:35.396  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.396  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:35.397  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.397  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:35.397  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.397  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.397  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.397  3844  3916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 19:03:35.397  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.397  3844  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:03:35.397  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.397  3844  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:03:35.397  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.397  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.397  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.397  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.397  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.397  3844  3844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:03:35.397  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.397  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.397  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.398  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:03:35.398  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.398  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.399  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.399  3844  3894 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:03:35.400  3844  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:03:35.400  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:03:35.401  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:03:35.401  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.401  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.401  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.402  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.402  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.402  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.402  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
09-06 19:03:35.402  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.402  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:35.402  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.402  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.403  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.403  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.403  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.404  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.404  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.404  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.404  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.409  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.409  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:35.409  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.409  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:35.409  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.410  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.410  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
,09-06 19:03:35.410  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.410  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.410  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.410  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.410  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.410  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.410  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:35.411  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.411  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.411  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.411  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.412  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:35.412  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:03:35.412  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:35.412  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:35.412  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.412  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.412  3844  3894 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9b5cc8 not in the list
,09-06 19:03:35.412  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.412  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
09-06 19:03:35.412  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:35.413  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.413  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.413  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:35.413  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:35.414  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:35.414  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:35.414  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:35.414  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61ba161 not in the list
,09-06 19:03:35.415  3844  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:03:35.415  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:03:35.415  3844  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-06 19:03:35.415  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:03:35.415  3844  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:03:35.415  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-06 19:03:35.417  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:03:35.417  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:03:35.417  3844  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-06 19:03:35.417  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:03:35.417  3844  3894 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:03:35.417  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:03:35.418  3844  3894 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:03:35.418  3844  3894 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-06 19:03:35.418  3844  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:03:35.418  3844  3894 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:03:35.419  3844  3894 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:03:35.419  3844  3894 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:03:35.419  3844  3894 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:03:35.419  3844  3894 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-06 19:03:35.420  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:35.420  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@624f35b added. We now have 2 listener(s)
09-06 19:03:35.420  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:35.422  3844  3894 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 19:03:35.422   871  2009 D WifiService: setWifiEnabled: true pid=3844, uid=10000
09-06 19:03:35.422   871  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:03:35.423  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:35.423  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34387f8 added. We now have 3 listener(s)
09-06 19:03:35.423  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:35.428  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:35.428  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8fea4d1 added. We now have 4 listener(s)
09-06 19:03:35.428  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:35.430  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:35.430  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54a0b36 added. We now have 5 listener(s)
09-06 19:03:35.430  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:35.432   871  1390 D WifiService: setWifiEnabled: false pid=3844, uid=10000
09-06 19:03:35.432   871  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:03:35.436  2709  2758 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 19:03:35.436  2709  2758 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:03:35.436  2709  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:03:35.436  2709  2758 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:03:35.437  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:35.439  2709  2709 D BluetoothMapService: onReceive
09-06 19:03:35.439  2709  2709 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:35.439  2709  2709 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:03:35.439  2709  2709 D BluetoothMapService: MAP Service closeService in
09-06 19:03:35.439  2709  2709 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 19:03:35.440  2709  2709 D ObexServerSockets0: shutdown(block = true)
09-06 19:03:35.440  2709  2709 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:03:35.440  2709  2709 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:03:35.440  2709  2906 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 19:03:35.441  2709  2930 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 19:03:35.441  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:35.441  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:35.441  2709  2929 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-06 19:03:35.441  2709  2758 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:03:35.441  2709  2709 I BtOppRfcommListener: stopping Accept Thread
09-06 19:03:35.442  2709  3449 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:03:35.442  2709  3449 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:03:35.442  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.442  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:35.442  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:35.444  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.448  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:35.450  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:03:35.452  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:35.452  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:35.453  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:35.453  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:35.453   871   884 I ActivityManager: Start proc 3919:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-06 19:03:35.455   871  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 19:03:35.455   871  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-06 19:03:35.455   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:03:35.455   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:03:35.458  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.458  2709  2762 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:03:35.460  2709  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-06 19:03:35.463  2709  2709 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:03:35.467   871   871 D BluetoothHeadset: Proxy object disconnected
,09-06 19:03:35.467  1981  1994 D BluetoothHeadset: Proxy object disconnected
,09-06 19:03:35.467  2709  2709 D A2dpService: Received stop request...Stopping profile...
09-06 19:03:35.468   871   871 D BluetoothHeadset: Proxy object disconnected
,09-06 19:03:35.468  2709  2912 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:03:35.468  1359  2085 D BluetoothHeadset: Proxy object disconnected
09-06 19:03:35.468   871   871 D BluetoothHeadset: Proxy object disconnected
09-06 19:03:35.470  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.473  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.472   871   871 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:35.473  2709  2709 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:35.473  2709  2709 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:35.473  2709  2709 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:03:35.473  2709  2709 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:35.474  2709  2709 D HidService: Received stop request...Stopping profile...
09-06 19:03:35.474  2709  2709 D HidService: Stopping Bluetooth HidService
,09-06 19:03:35.475   370   869 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:03:35.476   871  2069 D DhcpClient: Clearing IP address
,09-06 19:03:35.477  2709  2709 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:03:35.477  2709  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:03:35.477  2709  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:03:35.477  2709  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:03:35.477  1359  1359 D HeadsetProfile: Bluetooth service disconnected
09-06 19:03:35.477  2709  2762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-06 19:03:35.477  1359  1359 D BluetoothA2dp: Proxy object disconnected
,09-06 19:03:35.477  2709  2762 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-06 19:03:35.478  2709  2709 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:03:35.480  1359  1359 D BluetoothInputDevice: Proxy object disconnected
09-06 19:03:35.480  1359  1359 D HidProfile: Bluetooth service disconnected
09-06 19:03:35.481   370   869 D CommandListener: Setting iface cfg
09-06 19:03:35.482  2709  2709 D HealthService: Received stop request...Stopping profile...
09-06 19:03:35.482  1497  2548 V NativeCrypto: Read error: ssl=0x9aebb000: I/O error during system call, Connection timed out
09-06 19:03:35.484  1497  2548 V NativeCrypto: SSL shutdown failed: ssl=0x9aebb000: I/O error during system call, Broken pipe
09-06 19:03:35.485  2709  2709 D PanService: Received stop request...Stopping profile...
09-06 19:03:35.485   871  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
09-06 19:03:35.486   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:03:35.486   871   881 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-06 19:03:35.486  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:03:35.486   871  2066 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-06 19:03:35.487  2709  2709 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:35.487  2709  2709 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:35.487  2709  2709 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:35.487  2709  2709 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:35.488   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:03:35.489   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-06 19:03:35.486  1359  1359 D PanProfile: Bluetooth service disconnected
09-06 19:03:35.487  2709  2709 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:03:35.489  2709  2709 D BluetoothMapService: stop()
09-06 19:03:35.490  2709  2709 D BluetoothMapAppObserver: deinitObservers()
09-06 19:03:35.490  2709  2709 D BluetoothMapAppObserver: removeReceiver()
09-06 19:03:35.490   402   402 E Parcel  : Reading a NULL string not supported here.
09-06 19:03:35.492  2709  2709 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:35.492  2709  2709 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:35.492  2709  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:03:35.492  2709  2709 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:35.493  2709  2709 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:35.493  2709  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:03:35.493  2709  2899 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:35.493  2709  2899 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:35.493  2709  2899 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:35.493  2709  2709 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:03:35.493  2709  2899 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:35.493  2709  2709 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:03:35.493  2709  2762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:03:35.493  2709  2762 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:03:35.493  2709  2709 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:03:35.493  2709  2709 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:35.494  2709  2709 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:35.494  2709  2709 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:35.495  1359  1359 D BluetoothMap: Proxy object disconnected
09-06 19:03:35.495  1359  1359 D MapProfile: Bluetooth service disconnected
09-06 19:03:35.495   370   869 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:03:35.496  2709  2709 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:03:35.496  2709  2762 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:03:35.497  2709  2709 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:03:35.497  2709  2709 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:35.497  2709  2709 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:35.497  2709  2709 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:35.497  2709  2709 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:35.497  2709  2709 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:03:35.497  2709  2709 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:03:35.500  2709  2709 D BluetoothMapService: MAP Service closeService in
09-06 19:03:35.500  2709  2709 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:35.500  2709  2709 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:03:35.500  2709  2709 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:35.500  2709  2709 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:35.500   871  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-06 19:03:35.500   871  2066 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-06 19:03:35.501  2709  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 19:03:35.501  2709  2758 D BluetoothAdapterProperties: Setting state to 15
09-06 19:03:35.501  2709  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 19:03:35.502   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:03:35.502   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:03:35.502  2709  2758 I BluetoothAdapterState: Entering BleOnState
09-06 19:03:35.502  2709  2709 D BluetoothMapService: cleanup()
09-06 19:03:35.502  2709  2709 D BluetoothMapService: MAP Service closeService in
09-06 19:03:35.500   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:03:35.503  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:35.503  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:35.503  1359  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:03:35.504  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.504  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:35.505   871  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:03:35.505   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:03:35.505   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:03:35.505  1359  2085 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:03:35.506  1359  1370 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:03:35.506  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:35.506  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:35.507  1359  1376 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:03:35.508  1359  2085 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:03:35.508  1860  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:03:35.508  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.508  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:35.508  1359  1370 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:03:35.509  1981  2152 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:03:35.509  2709  2758 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 19:03:35.509  2709  2758 D BluetoothAdapterProperties: Setting state to 16
09-06 19:03:35.509  2709  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 19:03:35.510  2709  2758 D BluetoothAdapterProperties: onBleDisable
09-06 19:03:35.510  2709  2758 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:03:35.510  2709  2759 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 19:03:35.511  2709  2762 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:03:35.514  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:35.514  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:35.515  2709  2899 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:03:35.515  2709  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:03:35.517  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.519  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.521  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:35.528   871  2116 D DhcpClient: Receive thread stopped
09-06 19:03:35.538   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:35.545  3919  3919 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-06 19:03:35.554  3919  3919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:35.557   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:35.557   871  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:03:35.557   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:35.559   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:03:35.562  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:35.562  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:03:35.563  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:35.563  3436  3436 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@940da5e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-06 19:03:35.571   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8adfb37:true
,09-06 19:03:35.579   871  2007 I ActivityManager: Start proc 3938:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-06 19:03:35.587  3919  3919 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 19:03:35.589  3919  3919 D BluetoothMap: Create BluetoothMap proxy object
,09-06 19:03:35.594  3919  3919 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-06 19:03:35.600  3919  3919 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:35.613   871  2009 I ActivityManager: Killing 3092:com.google.android.talk/u0a61 (adj 15): empty #17
,09-06 19:03:35.613   370   869 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:03:35.614   871  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 19:03:35.625  3938  3938 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-06 19:03:35.716  2709  2762 I bt_hci  : shut_down
,09-06 19:03:35.717  2709  2768 D bt_hwcfg: hw_epilog_process
,09-06 19:03:35.728  2709  2768 I bt_vendor: low_power_mode_cb
,09-06 19:03:35.748  2709  2768 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:03:35.748  2709  2768 I bt_vendor: epilog_cb
,09-06 19:03:35.748  2709  2768 I bt_hci  : epilog_finished_callback
,09-06 19:03:35.754  2709  2762 I bt_hci_h4: hal_close
,09-06 19:03:35.755  2709  2762 I bt_userial_vendor: device fd = 51 close
,09-06 19:03:35.817  3938  3938 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.817  3938  3938 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.817  3938  3938 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.817  3938  3938 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.817  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.818  3938  3938 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:583)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.818  3938  3938 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.818  3938  3938 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.818  3938  3938 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102),
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:03:35.818  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:03:35.851   871  1391 I ActivityManager: Start proc 3969:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-06 19:03:35.851   871  1391 I ActivityManager: Killing 3436:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-06 19:03:35.897  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:03:35.920  2709  2759 D bt_stack_manager: event_shut_down_stack finished.
09-06 19:03:35.921  2709  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:03:35.922  2709  2709 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:03:35.922  2709  2758 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-06 19:03:35.923  2709  2709 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:03:35.923  2709  2709 D BtGatt.GattService: stop()
09-06 19:03:35.923  2709  2709 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:03:35.924  2709  2709 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:35.924  2709  2709 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:35.925  2709  2709 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:35.925  2709  2709 V BluetoothAdapterState: isBleTurningOff()=true
09-06 19:03:35.925  2709  2758 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-06 19:03:35.926  2709  2758 D BluetoothAdapterProperties: Setting state to 10
09-06 19:03:35.926  2709  2758 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 19:03:35.927  2709  2758 I BluetoothAdapterState: Entering OffState
09-06 19:03:35.927   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 19:03:35.936  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-06 19:03:35.943  2709  2709 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-06 19:03:35.943  2709  2709 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 19:03:35.943  2709  2709 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:03:35.944  2709  2759 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 19:03:35.952  2709  2759 D bt_stack_manager: event_clean_up_stack finished.
,09-06 19:03:35.954  2709  2709 I art     : System.exit called, status: 0
,09-06 19:03:35.954  2709  2709 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:03:36.028   871  2007 I ActivityManager: Process com.android.bluetooth (pid 2709) has died
,09-06 19:03:36.138  3969  3989 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-06 19:03:36.138  3969  3989 I Babel_SMS: MmsConfig.loadMmsSettings
,09-06 19:03:36.157  3969  3989 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-06 19:03:36.157  3969  3989 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 19:03:36.186  3969  3989 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-06 19:03:36.187  3969  3989 I Babel_SMS: MmsConfig.loadFromResources
,09-06 19:03:36.189  3969  3989 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:03:36.192  3969  3989 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-06 19:03:36.228  3969  3969 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:36.236  3969  3969 I Babel_Crash: startup - clean
,09-06 19:03:36.259  3969  3969 I Babel_telephony: TeleModule.launchCompleted
,09-06 19:03:36.272   871  2007 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-06 19:03:36.287  3969  3969 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-06 19:03:36.294  3969  3969 W Babel   : BAM#gBA: invalid account id: -1
,09-06 19:03:36.295  3969  3969 W Babel   : BAM#gBA: invalid account id: -1
,09-06 19:03:36.296  3969  3969 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-06 19:03:36.303  3969  3994 I Babel   : deleted: false for 0
,09-06 19:03:36.307   871  1377 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-06 19:03:36.356   871  1691 I ActivityManager: Start proc 3996:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-06 19:03:36.384  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:36.427  3996  3996 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-06 19:03:36.456  3969  3969 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:03:36.482  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:36.484  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:36.491  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:36.507  3969  3969 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:03:36.523   871  2014 I ActivityManager: Killing 3598:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-06 19:03:36.591  3969  3969 I vclib   : onServiceConnected
,09-06 19:03:36.626  3996  3996 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-06 19:03:36.668  3919  3919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:36.705   871  2009 I ActivityManager: Start proc 4023:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-06 19:03:36.709  3919  3919 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:36.776  3938  3960 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:03:36.795  4023  4023 D AdapterServiceConfig: Adding HeadsetService
,09-06 19:03:36.796  4023  4023 D AdapterServiceConfig: Adding A2dpService
09-06 19:03:36.796  4023  4023 D AdapterServiceConfig: Adding HidService
09-06 19:03:36.796  4023  4023 D AdapterServiceConfig: Adding HealthService
09-06 19:03:36.796  4023  4023 D AdapterServiceConfig: Adding PanService
,09-06 19:03:36.797  4023  4023 D AdapterServiceConfig: Adding GattService
,09-06 19:03:36.799  4023  4023 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:03:36.803   871  2014 I ActivityManager: Killing 2784:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-06 19:03:36.825   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a115c0f:true
,09-06 19:03:36.862  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:36.886  1700  1700 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:03:36.903  1700  1700 D SystemUpdateService: onCreate
,09-06 19:03:36.907  1700  1700 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:03:36.911  1700  4035 I SystemUpdateService: active receiver: enabled
,09-06 19:03:36.918  1700  4035 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:03:36.919  1700  1700 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-06 19:03:36.921  1700  2527 I iu.UploadsManager: num queued entries: 0
09-06 19:03:36.922  1700  2527 I iu.UploadsManager: num updated entries: 0
,09-06 19:03:36.924  1700  2527 I iu.SyncManager: NEXT; no task
,09-06 19:03:36.927  1700  1700 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:03:36.928  1700  1700 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:03:36.929  1700  4035 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-06 19:03:36.930  1700  4035 I SystemUpdateService: now status is 0 (complete)
,09-06 19:03:36.930  1700  4035 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 19:03:36.930  1700  4035 I SystemUpdateService: file has been verified
,09-06 19:03:36.932  1700  4035 I SystemUpdateService: OTA package size = 12249756
,09-06 19:03:36.939  1700  4035 I SystemUpdateService: showing system update notification,
09-06 19:03:36.942   871  1391 I ActivityManager: Start proc 4037:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-06 19:03:36.956  1700  1700 D SystemUpdateService: onDestroy
,09-06 19:03:36.985  4037  4037 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-06 19:03:36.987  4037  4037 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:36.992  4037  4037 D SprintDMHelper: simOperator: 
,09-06 19:03:36.992  4037  4037 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:03:37.012   871  1995 I ActivityManager: Start proc 4049:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-06 19:03:37.015   871  1995 I ActivityManager: Killing 3533:android.process.acore/u0a5 (adj 15): empty #17
,09-06 19:03:37.171   871  2010 I ActivityManager: Start proc 4064:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-06 19:03:37.175  3969  4063 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-06 19:03:37.179   871  1690 I ActivityManager: Killing 3674:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-06 19:03:37.264  4064  4064 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-06 19:03:37.345  4064  4064 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:03:37.345  4064  4064 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:03:37.345  4064  4064 I GAv4    :   adb logcat -s GAv4
,09-06 19:03:37.363  4064  4064 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:03:37.372  4064  4064 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:03:37.401  4064  4082 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:03:37.512  4064  4064 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-06 19:03:37.549  4064  4064 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-06 19:03:37.561  4064  4064 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6571-6576)
,09-06 19:03:37.561  4064  4064 I LibraryLoader: Expected native library version number "",actual native library version number "",
,09-06 19:03:37.576  4064  4064 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e5cb28}
,09-06 19:03:37.576  4064  4064 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:03:37.577  4064  4064 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:03:37.585  4064  4064 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 19:03:37.587  4064  4064 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:03:37.603  4064  4064 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 19:03:37.615  4064  4064 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:03:37.615  4064  4064 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:03:37.615  4064  4064 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:03:37.615  4064  4064 I Adreno  : Build Date                       : 10/20/15
09-06 19:03:37.615  4064  4064 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:03:37.615  4064  4064 I Adreno  : Local Branch                     : M14
09-06 19:03:37.615  4064  4064 I Adreno  : Remote Branch                    : 
09-06 19:03:37.615  4064  4064 I Adreno  : Remote Branch                    : 
09-06 19:03:37.615  4064  4064 I Adreno  : Reconstruct Branch               : 
,09-06 19:03:37.674  4064  4064 I NSApplication: Starting up...
,09-06 19:03:37.684  4064  4110 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 19:03:37.713   871  1995 I ActivityManager: Start proc 4115:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-06 19:03:37.714   871  1995 I ActivityManager: Killing 3691:com.android.musicfx/u0a18 (adj 15): empty #17
,09-06 19:03:37.789  4115  4115 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-06 19:03:37.994   871  2007 I ActivityManager: Killing 3484:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-06 19:03:38.445   871  2010 D WifiService: setWifiEnabled: true pid=3844, uid=10000
09-06 19:03:38.445   871  2010 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:03:38.458   871  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:03:38.470  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:38.470  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:38.471  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:38.471  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:38.474  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:38.474  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:38.475  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:38.475  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:38.503   871  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:03:38.504   871  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 19:03:38.505   871  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 19:03:38.505   871  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:03:38.506   871  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-06 19:03:38.506   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 19:03:38.506   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:03:38.518   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:03:38.519   871  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.38 rxSuccessRate=13.75 delta 1000 -> 994
09-06 19:03:38.519   370   869 D CommandListener: Setting iface cfg
09-06 19:03:38.520   871  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-06 19:03:38.520   871  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:03:38.527   871  1300 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 19:03:38.529   871  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 19:03:38.528   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:03:38.529   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:38.536   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:03:38.591   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:03:38.593  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:03:39.029  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:03:39.116  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:03:39.118  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 19:03:39.130   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:03:39.146   871  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-06 19:03:39.147   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:03:39.147   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 19:03:39.174   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:39.186   370   869 D CommandListener: Setting iface cfg
,09-06 19:03:39.189   871  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:03:39.211   871  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-06 19:03:39.219   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 19:03:39.236   871  4140 D DhcpClient: Receive thread started
,09-06 19:03:39.322   871  1303 E native  : do suspend false
,09-06 19:03:39.344   871  2069 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 19:03:39.357   871  4140 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,09-06 19:03:39.360   871  2069 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,09-06 19:03:39.365   871  2069 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:03:39.385   871  4140 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 19:03:39.387   871  2069 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 19:03:39.392   370   869 D CommandListener: Setting iface cfg
,09-06 19:03:39.403   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 19:03:39.404   871  2069 D DhcpClient: Scheduling renewal in 86399s
,09-06 19:03:39.414   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 19:03:39.416   871  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:03:39.416   871  1303 D WifiConfigStore: No blacklist allowed without epno enabled
09-06 19:03:39.417   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 19:03:39.418   871  1305 D ConnectivityService: Adding iface wlan0 to network 101
,09-06 19:03:39.425   871  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:03:39.473   871  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:03:39.473   871  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-06 19:03:39.476   871  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-06 19:03:39.479   871  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-06 19:03:39.481   871  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-06 19:03:39.494   871  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:03:39.498   871  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-06 19:03:39.498   871  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-06 19:03:39.499   871  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-06 19:03:39.499   871  1305 D ConnectivityService:    accepting network in place of null
09-06 19:03:39.499   871  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 19:03:39.500   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:03:39.500   871  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:03:39.513   871  4139 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138528, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 19:03:39.547   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:39.590   871  4138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:803::200e
,09-06 19:03:39.601   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:39.606   871  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 19:03:39.606   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:39.612   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:03:39.625   871  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-06 19:03:39.629  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:39.629  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:39.629  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:39.629  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:39.637  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:39.637  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:39.637  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:39.637  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:39.644  1700  1700 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:03:39.647  1700  1700 D SystemUpdateService: onCreate
,09-06 19:03:39.651  1700  1700 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:03:39.653  1700  4150 I SystemUpdateService: active receiver: enabled
,09-06 19:03:39.655  1700  4150 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:03:39.660  1700  4150 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-06 19:03:39.660  1700  4150 I SystemUpdateService: now status is 0 (complete)
09-06 19:03:39.660  1700  4150 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:03:39.660  1700  4150 I SystemUpdateService: file has been verified
09-06 19:03:39.660  1700  4150 I SystemUpdateService: OTA package size = 12249756
,09-06 19:03:39.663  1700  4150 I SystemUpdateService: showing system update notification
,09-06 19:03:39.670  1700  1700 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:03:39.675  1700  2527 I iu.UploadsManager: num queued entries: 0
,09-06 19:03:39.676  1700  2527 I iu.UploadsManager: num updated entries: 0
,09-06 19:03:39.677  1700  2527 I iu.SyncManager: NEXT; no task
,09-06 19:03:39.680  1700  1700 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:03:39.680  1700  4154 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-06 19:03:39.680  1700  4154 W BaseAppContext: Using Auth Proxy for data requests.
09-06 19:03:39.681  1700  1700 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:03:39.681  1700  1700 D SystemUpdateService: onDestroy
,09-06 19:03:39.683  1700  4154 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 19:03:39.683  4037  4037 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:39.689   871  4138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:03:39 GMT], X-Android-Received-Millis=[1473181419687], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473181419641]}
,09-06 19:03:39.690   871  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 19:03:39.690   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-06 19:03:39.690   871  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 19:03:39.691   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 19:03:39.692  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 19:03:39.692  4037  4037 D SprintDMHelper: simOperator: 
09-06 19:03:39.692  4037  4037 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:03:39.695  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:03:39.720  1497  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 19:03:39.720  1497  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 19:03:39.720  1497  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:03:39.720  1497  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:03:39.739  1700  4154 E MDM     : [173] SitrepService.a: Error sending sitrep.
,09-06 19:03:39.836  3969  4157 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 19:03:39.973  1497  4162 I GCM     : Ack for not saved message 136
,09-06 19:03:40.608   871  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 19:03:41.453   871   881 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,09-06 19:03:41.454   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:03:41.475  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-06 19:03:41.478   871  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 19:03:41.479   871  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-06 19:03:41.479   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
09-06 19:03:41.479   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:41.495   871  2069 D DhcpClient: Clearing IP address
,09-06 19:03:41.495   370   869 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:03:41.498   370   869 D CommandListener: Setting iface cfg
,09-06 19:03:41.500   871  4140 D DhcpClient: Receive thread stopped
,09-06 19:03:41.503  1497  4162 V NativeCrypto: Read error: ssl=0x9b02d600: I/O error during system call, Connection timed out
,09-06 19:03:41.505  1497  4162 V NativeCrypto: SSL shutdown failed: ssl=0x9b02d600: I/O error during system call, Broken pipe
,09-06 19:03:41.506   871  2009 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
09-06 19:03:41.506   871  4138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-06 19:03:41.507   871  4138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:803::200e,
,09-06 19:03:41.510   871  4138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-06 19:03:41.511   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-06 19:03:41.511   871  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:03:41.512   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 19:03:41.518   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 19:03:41.519   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-06 19:03:41.526   871  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-06 19:03:41.530   402   402 E Parcel  : Reading a NULL string not supported here.
,09-06 19:03:41.538   871  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
09-06 19:03:41.539   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:03:41.564   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:41.586  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:03:41.587   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:41.588   370   869 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:03:41.588   871  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-06 19:03:41.588   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:41.591   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:03:41.595  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:41.595  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:41.595  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:41.595  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:41.596  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:41.597  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:41.597  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:41.597  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:41.600   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 19:03:41.603  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:41.603  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:41.603  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:41.603  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:41.605  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:41.605  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:41.605  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:41.605  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:41.606   871  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:03:41.610  1860  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:03:41.619  1497  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-06 19:03:41.619  1497  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-06 19:03:41.619  1497  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:03:41.619  1497  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:03:41.622  1700  1700 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:03:41.625  1700  1700 D SystemUpdateService: onCreate
,09-06 19:03:41.629  1700  1700 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:03:41.632  1700  4174 I SystemUpdateService: active receiver: enabled
09-06 19:03:41.636  1700  4174 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-06 19:03:41.639  3549  3549 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-06 19:03:41.640  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-06 19:03:41.640  3549  3549 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-06 19:03:41.637  1700  4174 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-06 19:03:41.640  1700  4174 I SystemUpdateService: now status is 0 (complete)
09-06 19:03:41.640  1700  4174 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:03:41.640  1700  4174 I SystemUpdateService: file has been verified
09-06 19:03:41.641  1700  4174 I SystemUpdateService: OTA package size = 12249756
09-06 19:03:41.641  1700  1700 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:03:41.648  1700  2527 I iu.UploadsManager: num queued entries: 0
,09-06 19:03:41.650  1700  2527 I iu.UploadsManager: num updated entries: 0
09-06 19:03:41.651  1700  2527 I iu.SyncManager: NEXT; no task
,09-06 19:03:41.652  1700  4174 I SystemUpdateService: showing system update notification
,09-06 19:03:41.655  1700  1700 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:03:41.656  1700  1700 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:03:41.658  4037  4037 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:41.661  4037  4037 D SprintDMHelper: simOperator: 
09-06 19:03:41.661  4037  4037 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:03:41.662   370   869 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:03:41.663   871  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-06 19:03:41.663   871  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-06 19:03:41.663  1700  1700 D SystemUpdateService: onDestroy
,09-06 19:03:41.680  3969  4177 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-06 19:03:41.932   871  1995 I ActivityManager: Killing 3713:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-06 19:03:44.491   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee5fef9:true
,09-06 19:03:44.492  4023  4023 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 19:03:44.498  4023  4023 I bt_bluedroid: init
,09-06 19:03:44.498  4023  4180 I BluetoothAdapterState: Entering OffState
,09-06 19:03:44.506  4023  4181 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:03:44.506  4023  4181 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:03:44.507  4023  4181 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:03:44.507  4023  4181 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:03:44.509  4023  4023 I bt_bluedroid: get_profile_interface socket
,09-06 19:03:44.513  4023  4184 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:03:44.514  4023  4184 D BluetoothAdapterProperties: Name is: Nexus 6
09-06 19:03:44.516  4023  4023 I bt_bluedroid: get_profile_interface sdp
,09-06 19:03:44.520  4023  4034 I bt_bluedroid: config_hci_snoop_log
,09-06 19:03:44.521   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:03:44.528  4023  4180 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 19:03:44.529  4023  4180 D BluetoothAdapterProperties: Setting state to 14
09-06 19:03:44.529  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:03:44.532  4023  4180 D BluetoothBondStateMachine: make
,09-06 19:03:44.536  4023  4185 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:03:44.539  4023  4180 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:03:44.541  4023  4023 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:03:44.545  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:44.546  4023  4023 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:03:44.547  4023  4023 D BtGatt.GattService: Received start request. Starting profile...
,09-06 19:03:44.547  4023  4023 D BtGatt.GattService: start()
,09-06 19:03:44.547  4023  4023 I bt_bluedroid: get_profile_interface gatt
,09-06 19:03:44.549  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
09-06 19:03:44.549  4023  4023 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:03:44.558  4023  4023 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:44.558  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:44.558  4023  4023 V BluetoothAdapterState: isBleTurningOn()=true
09-06 19:03:44.558  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:44.559  4023  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-06 19:03:44.559  4023  4180 I bt_bluedroid: enable
,09-06 19:03:44.559  4023  4181 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 19:03:44.560  4023  4181 I bt_hci  : start_up
,09-06 19:03:44.568  4023  4181 I bt_vendor: alloc value 0xb39b9189
,09-06 19:03:44.568  4023  4181 I bt_vendor: init
09-06 19:03:44.568  4023  4181 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-06 19:03:44.568  4023  4181 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:03:44.677  4023  4181 D bt_hci  : start_up starting async portion
,09-06 19:03:44.678  4023  4188 I bt_hci  : event_finish_startup
09-06 19:03:44.678  4023  4188 I bt_hci_h4: hal_open
,09-06 19:03:44.678  4023  4188 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:03:44.686  4023  4188 I bt_userial_vendor: device fd = 51 open
,09-06 19:03:44.718  4023  4188 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:03:44.750  4023  4188 D bt_hwcfg: Chipset BCM4354A2
,09-06 19:03:44.750  4023  4188 D bt_hwcfg: Target name = [BCM4354A2],
09-06 19:03:44.751  4023  4188 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:03:45.442  4023  4188 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:03:45.443  4023  4188 D bt_hwcfg: Settlement delay -- 100 ms
09-06 19:03:45.444  4023  4188 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:03:45.561  4023  4188 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:03:45.563  4023  4188 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:03:45.592  4023  4188 I bt_hwcfg: vendor lib fwcfg completed
09-06 19:03:45.592  4023  4188 I bt_vendor: firmware callback
09-06 19:03:45.592  4023  4188 I bt_hci  : firmware_config_callback
,09-06 19:03:45.604  4023  4192 I bt_btu  : btu_task pending for preload complete event
,09-06 19:03:45.604  4023  4192 I bt_btu_task: Bluetooth chip preload is complete
,09-06 19:03:45.604  4023  4192 I bt_btu  : btu_task received preload complete event
,09-06 19:03:45.614  4023  4192 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:03:45.615  4023  4192 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:03:45.615  4023  4192 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:03:45.615  4023  4192 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-06 19:03:45.616  4023  4192 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-06 19:03:45.616  4023  4192 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 19:03:45.616  4023  4192 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:03:45.616  4023  4192 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:03:45.617  4023  4192 I         : BTE_InitTraceLevels -- TRC_GAP
,09-06 19:03:45.617  4023  4192 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:03:45.617  4023  4192 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:03:45.618  4023  4192 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 19:03:45.618  4023  4192 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:03:45.618  4023  4192 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:03:45.619  4023  4192 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:03:45.752  4023  4192 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,09-06 19:03:45.752  4023  4192 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,09-06 19:03:45.764  4023  4184 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 19:03:45.766  4023  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:03:45.767  4023  4184 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:03:45.770  4023  4184 D BluetoothAdapterProperties: Name is: Nexus 6
09-06 19:03:45.773  4023  4184 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:45.774  4023  4184 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:03:45.774  4023  4184 D bt_hci  : do_postload posting postload work item
09-06 19:03:45.774  4023  4188 I bt_hci  : event_postload
,09-06 19:03:45.775  4023  4188 I bt_vendor: sco_config_cb
,09-06 19:03:45.775  4023  4188 I bt_hci  : sco_config_callback postload finished.
09-06 19:03:45.777  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:45.780  4023  4184 D bt_bte_conf: Device ID record 1 : primary
,09-06 19:03:45.781  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:45.781  4023  4184 D bt_bte_conf:   vendorId            = 000f
,09-06 19:03:45.781  4023  4184 D bt_bte_conf:   vendorIdSource      = 0001
09-06 19:03:45.782  4023  4184 D bt_bte_conf:   product             = 1200
09-06 19:03:45.782  4023  4184 D bt_bte_conf:   version             = 1436
09-06 19:03:45.782  4023  4184 D bt_bte_conf:   clientExecutableURL = 
09-06 19:03:45.782  4023  4184 D bt_bte_conf:   serviceDescription  = 
09-06 19:03:45.783  4023  4184 D bt_bte_conf:   documentationURL    = 
09-06 19:03:45.783  4023  4184 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-06 19:03:45.783  4023  4181 D bt_stack_manager: event_start_up_stack finished
,09-06 19:03:45.785  4023  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-06 19:03:45.786  4023  4180 D BluetoothAdapterProperties: Setting state to 15
09-06 19:03:45.786  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-06 19:03:45.787  4023  4188 I bt_vendor: low_power_mode_cb
,09-06 19:03:45.789  4023  4180 I BluetoothAdapterState: Entering BleOnState
,09-06 19:03:45.793  4023  4180 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 19:03:45.793  4023  4180 D BluetoothAdapterProperties: Setting state to 11
09-06 19:03:45.793  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 19:03:45.797  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:45.799  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:45.801  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:45.802  4023  4023 D HeadsetService: Received start request. Starting profile...
09-06 19:03:45.809  4023  4023 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
09-06 19:03:45.810  4023  4023 D HeadsetStateMachine: make
,09-06 19:03:45.812  4023  4180 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:03:45.818  4023  4023 D HeadsetStateMachine: max_hf_connections = 1
,09-06 19:03:45.819  4023  4023 I bt_bluedroid: get_profile_interface handsfree
09-06 19:03:45.819  4023  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-06 19:03:45.819  4023  4184 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 19:03:45.825  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:45.825  4023  4023 D A2dpService: Received start request. Starting profile...
,09-06 19:03:45.826  4023  4023 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:03:45.827  4023  4023 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:03:45.835  4023  4023 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:03:45.835  4023  4023 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 19:03:45.835  4023  4023 D A2dpStateMachine: make
09-06 19:03:45.836  4023  4023 I bt_bluedroid: get_profile_interface a2dp
,09-06 19:03:45.837  4023  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:03:45.839  4023  4201 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:03:45.841  4023  4023 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:03:45.841  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:03:45.843  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:45.844  4023  4023 D HidService: Received start request. Starting profile...
,09-06 19:03:45.844  4023  4023 I bt_bluedroid: get_profile_interface hidhost
09-06 19:03:45.844  4023  4023 D HidService: setHidService(): set to: null
09-06 19:03:45.844  4023  4184 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
09-06 19:03:45.844  4023  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-06 19:03:45.845  4023  4023 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:03:45.844  3919  3919 D BluetoothInputDevice: Proxy object connected
09-06 19:03:45.845  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:45.846  3919  3919 D HidProfile: Bluetooth service connected
09-06 19:03:45.846  4023  4023 D HealthService: Received start request. Starting profile...
,09-06 19:03:45.847  4023  4023 I bt_bluedroid: get_profile_interface health
,09-06 19:03:45.848  4023  4023 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:03:45.848  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:45.849  3919  3919 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:03:45.849  4023  4023 D PanService: Received start request. Starting profile...
09-06 19:03:45.849  4023  4023 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-06 19:03:45.850  4023  4023 I bt_bluedroid: get_profile_interface pan
09-06 19:03:45.850  4023  4184 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:03:45.850  3919  3919 D PanProfile: Bluetooth service connected
,09-06 19:03:45.854  4023  4023 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:45.855  3919  3919 D BluetoothMap: Proxy object connected
,09-06 19:03:45.855  4023  4023 D BluetoothMapService: Received start request. Starting profile...
,09-06 19:03:45.855  4023  4023 D BluetoothMapService: start()
09-06 19:03:45.855  3919  3919 D MapProfile: Bluetooth service connected
09-06 19:03:45.856  3919  3919 D BluetoothMap: getConnectedDevices()
,09-06 19:03:45.856  3919  3919 D BluetoothMap: Bluetooth is Not enabled
,09-06 19:03:45.858  4023  4023 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:03:45.859  4023  4023 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-06 19:03:45.859  4023  4023 D BluetoothMapAppObserver: createReceiver()
,09-06 19:03:45.860  4023  4023 D BluetoothMapAppObserver: initObservers()
,09-06 19:03:45.860  4023  4023 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:03:45.869  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:03:45.869  4023  4023 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:03:45.869  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:45.869  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:03:45.871  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:03:45.872  4023  4023 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:45.872  4023  4199 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:03:45.872  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:45.872  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:45.872  4023  4023 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:45.872  4023  4023 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:45.873  4023  4023 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:45.874  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:45.874  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:45.874  4023  4023 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:45.874  4023  4023 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:45.874  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:45.874  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:45.874  4023  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 19:03:45.874  4023  4180 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:03:45.874  4023  4180 D BluetoothAdapterProperties: State =  11
09-06 19:03:45.878  4023  4184 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:03:45.878  4023  4180 D BluetoothAdapterProperties: Setting state to 12
09-06 19:03:45.878  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:03:45.878  4023  4184 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:03:45.879   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:45.879  4023  4180 I BluetoothAdapterState: Entering OnState
09-06 19:03:45.879  3919  3931 D BluetoothPan: onBluetoothStateChange on: true
,09-06 19:03:45.879   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:03:45.879  3919  3929 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:03:45.880  1359  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:03:45.884   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:45.884   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:03:45.885  1359  1359 D BluetoothInputDevice: Proxy object connected
,09-06 19:03:45.885  1359  1359 D HidProfile: Bluetooth service connected
,09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:45.885  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:45.886  3919  3931 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:03:45.886   871   871 D BluetoothA2dp: Proxy object connected
,09-06 19:03:45.887  4023  4023 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:03:45.888  4023  4023 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-06 19:03:45.889  1359  2085 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:03:45.890  4023  4023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:45.891  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:45.893  1359  1359 D BluetoothMap: Proxy object connected
09-06 19:03:45.893  1359  1359 D MapProfile: Bluetooth service connected
09-06 19:03:45.893  1359  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:45.893  1359  1359 D BluetoothMap: getConnectedDevices()
09-06 19:03:45.894  1359  1370 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:03:45.894  4023  4023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:03:45.896  1359  2085 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:03:45.896  4023  4023 D ObexServerSockets: Succeed to create listening sockets 
09-06 19:03:45.896  4023  4023 D ObexServerSockets0: startAccept()
09-06 19:03:45.896  4023  4023 D ObexServerSockets0: prepareForNewConnect()
09-06 19:03:45.898  1359  1359 D BluetoothA2dp: Proxy object connected
,09-06 19:03:45.899  4023  4023 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:03:45.899  4023  4023 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:45.899  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:45.900  1359  1370 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:03:45.903  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:03:45.903  1359  1359 D PanProfile: Bluetooth service connected
09-06 19:03:45.903  3919  3929 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:03:45.904  1981  2059 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:45.904  4023  4207 D ObexServerSockets0: Accepting socket connection...
09-06 19:03:45.905  4023  4208 D ObexServerSockets0: Accepting socket connection...
09-06 19:03:45.906   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:03:45.906  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:45.907  4023  4023 D BluetoothMapService: onReceive
09-06 19:03:45.907  4023  4023 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:45.907  4023  4023 D BluetoothMapService: STATE_ON
09-06 19:03:45.910  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:45.910  3919  3919 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 19:03:45.911  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:45.914  3919  3919 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 19:03:45.921  3919  3919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:45.923  3919  3919 D BluetoothA2dp: Proxy object connected
,09-06 19:03:45.928  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:45.933  3919  3919 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:45.944  1359  1359 D BluetoothPbap: Proxy object connected
,09-06 19:03:45.944  1359  1359 D PbapServerProfile: Bluetooth service connected
09-06 19:03:45.945  3919  3919 D BluetoothPbap: Proxy object connected
09-06 19:03:45.945  4023  4023 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:03:45.945  4023  4023 D ObexServerSockets0: prepareForNewConnect()
09-06 19:03:45.946  3919  3919 D PbapServerProfile: Bluetooth service connected
,09-06 19:03:45.957  4023  4213 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:45.978  4023  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:45.980  4023  4217 I BtOppRfcommListener: Accept thread started.
,09-06 19:03:45.981   871   871 D BluetoothHeadset: Proxy object connected
,09-06 19:03:45.981  1981  1994 D BluetoothHeadset: Proxy object connected
09-06 19:03:45.982   871   871 D BluetoothHeadset: Proxy object connected
09-06 19:03:45.983  1359  1376 D BluetoothHeadset: Proxy object connected
09-06 19:03:45.983  1359  1359 D HeadsetProfile: Bluetooth service connected
09-06 19:03:45.983   871   871 D BluetoothHeadset: Proxy object connected
,09-06 19:03:45.985   871   888 D BluetoothHeadset: Proxy object connected
,09-06 19:03:45.993  1359  1370 D BluetoothHeadset: Proxy object connected
09-06 19:03:45.993  1359  1359 D HeadsetProfile: Bluetooth service connected
,09-06 19:03:46.004  1981  1993 D BluetoothHeadset: Proxy object connected
,09-06 19:03:46.018  3919  3931 D BluetoothHeadset: Proxy object connected
,09-06 19:03:46.022  3919  3919 D HeadsetProfile: Bluetooth service connected
,09-06 19:03:47.472  4023  4180 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 19:03:47.472  4023  4180 D BluetoothAdapterProperties: Setting state to 13
09-06 19:03:47.473  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:03:47.474  4023  4180 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 19:03:47.482  4023  4023 D BluetoothMapService: onReceive
,09-06 19:03:47.483  4023  4023 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:03:47.483  4023  4023 D BluetoothMapService: STATE_TURNING_OFF
,09-06 19:03:47.484  4023  4023 D BluetoothMapService: MAP Service closeService in
,09-06 19:03:47.484  4023  4023 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 19:03:47.485  4023  4023 D ObexServerSockets0: shutdown(block = true)
09-06 19:03:47.486  4023  4207 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-06 19:03:47.491  4023  4184 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:47.492  4023  4180 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:03:47.492  4023  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-06 19:03:47.493  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:47.494  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:47.497  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:47.497  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:03:47.501  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:47.502  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:47.502  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:03:47.502  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:47.504  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.504  4023  4023 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:03:47.505  4023  4023 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-06 19:03:47.505   871  1305 D ConnectivityService: handlePromptUnvalidated 101
09-06 19:03:47.505  4023  4195 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 19:03:47.505  4023  4208 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-06 19:03:47.506  3919  3919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:47.506  4023  4023 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:03:47.506  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.510   871   871 D BluetoothHeadset: Proxy object disconnected
,09-06 19:03:47.511  1981  2152 D BluetoothHeadset: Proxy object disconnected
,09-06 19:03:47.511   871   871 D BluetoothHeadset: Proxy object disconnected
09-06 19:03:47.512  3919  3929 D BluetoothHeadset: Proxy object disconnected
,09-06 19:03:47.512  1359  2085 D BluetoothHeadset: Proxy object disconnected
09-06 19:03:47.512   871   871 D BluetoothHeadset: Proxy object disconnected
,09-06 19:03:47.513  4023  4023 D A2dpService: Received stop request...Stopping profile...
,09-06 19:03:47.513  4023  4201 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:03:47.514   871   871 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:47.516  1359  1359 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:03:47.516  4023  4023 D HidService: Received stop request...Stopping profile...
,09-06 19:03:47.516  4023  4023 D HidService: Stopping Bluetooth HidService
09-06 19:03:47.516  1359  1359 D BluetoothA2dp: Proxy object disconnected
09-06 19:03:47.517  1359  1359 D BluetoothInputDevice: Proxy object disconnected
09-06 19:03:47.517  1359  1359 D HidProfile: Bluetooth service disconnected
09-06 19:03:47.517  4023  4023 D HealthService: Received stop request...Stopping profile...
09-06 19:03:47.520  4023  4023 D PanService: Received stop request...Stopping profile...
09-06 19:03:47.521  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:03:47.521  1359  1359 D PanProfile: Bluetooth service disconnected
09-06 19:03:47.521  3919  3919 D DockEventReceiver: finishStartingService: stopping service
09-06 19:03:47.521  4023  4023 I BtOppRfcommListener: stopping Accept Thread
09-06 19:03:47.522  4023  4217 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:03:47.522  3919  3919 D HeadsetProfile: Bluetooth service disconnected
09-06 19:03:47.523  3919  3919 D BluetoothA2dp: Proxy object disconnected
,09-06 19:03:47.523  3919  3919 D BluetoothInputDevice: Proxy object disconnected
09-06 19:03:47.523  3919  3919 D HidProfile: Bluetooth service disconnected,
09-06 19:03:47.524  3919  3919 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:03:47.524  3919  3919 D PanProfile: Bluetooth service disconnected
09-06 19:03:47.524  4023  4217 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:03:47.526  4023  4023 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:03:47.526  4023  4023 D BluetoothMapService: stop()
,09-06 19:03:47.527  4023  4023 D BluetoothMapAppObserver: deinitObservers()
09-06 19:03:47.527  4023  4023 D BluetoothMapAppObserver: removeReceiver()
09-06 19:03:47.528  1359  1359 D BluetoothMap: Proxy object disconnected
,09-06 19:03:47.528  4023  4023 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:47.528  1359  1359 D MapProfile: Bluetooth service disconnected
09-06 19:03:47.528  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:47.528  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:03:47.528  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:47.530  4023  4023 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:03:47.530  4023  4192 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:03:47.530  4023  4192 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:03:47.530  4023  4192 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:03:47.530  4023  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 19:03:47.530  4023  4184 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-06 19:03:47.530  4023  4023 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:03:47.532  3919  3919 D BluetoothMap: Proxy object disconnected
09-06 19:03:47.532  3919  3919 D MapProfile: Bluetooth service disconnected
09-06 19:03:47.532  4023  4023 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:47.532  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:47.532  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:47.532  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:03:47.533  4023  4192 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:03:47.533  4023  4023 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:47.533  4023  4192 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:03:47.533  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:47.533  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:03:47.533  4023  4192 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:03:47.533  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false,
09-06 19:03:47.534  4023  4192 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:47.534  4023  4192 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-06 19:03:47.534  4023  4192 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:03:47.534  4023  4023 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-06 19:03:47.534  4023  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-06 19:03:47.534  4023  4023 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-06 19:03:47.534  4023  4184 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:03:47.534  4023  4023 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:47.534  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:47.535  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:03:47.535  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:47.535  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:03:47.535  4023  4023 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-06 19:03:47.535  4023  4023 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:03:47.535  4023  4023 V BluetoothAdapterState: isTurningOff()=true
09-06 19:03:47.535  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:47.536  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:03:47.536  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:47.536  4023  4184 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:03:47.536  4023  4023 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-06 19:03:47.536  4023  4023 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:03:47.538  4023  4023 D BluetoothMapService: MAP Service closeService in
09-06 19:03:47.538  4023  4023 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:03:47.538  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:47.538  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:47.538  4023  4023 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:47.539  4023  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-06 19:03:47.539  4023  4180 D BluetoothAdapterProperties: Setting state to 15
09-06 19:03:47.539  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 19:03:47.539  4023  4023 D BluetoothMapService: cleanup()
09-06 19:03:47.539  4023  4023 D BluetoothMapService: MAP Service closeService in
,09-06 19:03:47.539  4023  4180 I BluetoothAdapterState: Entering BleOnState
09-06 19:03:47.540   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:03:47.540  3919  3931 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:03:47.541  1359  1359 D BluetoothPbap: Proxy object disconnected
,09-06 19:03:47.541  1359  1359 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:03:47.561   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:03:47.562  3919  3931 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:03:47.562  1359  2085 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:03:47.565  3919  3919 D BluetoothPbap: Proxy object disconnected
09-06 19:03:47.565  3919  3919 D PbapServerProfile: Bluetooth service disconnected
09-06 19:03:47.565   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:03:47.566   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:03:47.566  3919  3929 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:03:47.566  1359  1376 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:03:47.567  1359  1370 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:03:47.568  1359  2085 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:03:47.568  1359  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:03:47.569  1359  1370 D BluetoothPan: onBluetoothStateChange on: false
,09-06 19:03:47.570  3919  3931 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:03:47.571  1981  2059 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:03:47.571  3919  4221 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:03:47.572  3919  3929 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 19:03:47.572  4023  4180 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 19:03:47.572  4023  4180 D BluetoothAdapterProperties: Setting state to 16
09-06 19:03:47.572  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-06 19:03:47.573  4023  4180 D BluetoothAdapterProperties: onBleDisable
09-06 19:03:47.573  4023  4180 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:03:47.574  4023  4181 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-06 19:03:47.576  4023  4192 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 19:03:47.576  4023  4192 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:03:47.581  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.583  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.583  4023  4184 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:47.584  3919  3919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:03:47.586  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:47.588  3919  3919 D DockEventReceiver: finishStartingService: stopping service
09-06 19:03:47.588  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:47.592  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:47.776  4023  4184 I bt_hci  : shut_down
,09-06 19:03:47.777  4023  4188 D bt_hwcfg: hw_epilog_process
,09-06 19:03:47.789  4023  4188 I bt_vendor: low_power_mode_cb
,09-06 19:03:47.810  4023  4188 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:03:47.810  4023  4188 I bt_vendor: epilog_cb
09-06 19:03:47.810  4023  4188 I bt_hci  : epilog_finished_callback
,09-06 19:03:47.818  4023  4184 I bt_hci_h4: hal_close
,09-06 19:03:47.820  4023  4184 I bt_userial_vendor: device fd = 51 close
,09-06 19:03:47.935  4023  4181 D bt_stack_manager: event_shut_down_stack finished.
,09-06 19:03:47.936  4023  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:03:47.942  4023  4180 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-06 19:03:47.942  4023  4023 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:03:47.943  4023  4023 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:03:47.944  4023  4023 D BtGatt.GattService: stop()
09-06 19:03:47.944  4023  4023 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:03:47.949  4023  4023 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:03:47.950  4023  4023 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:47.950  4023  4023 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:47.950  4023  4023 V BluetoothAdapterState: isBleTurningOff()=true
09-06 19:03:47.951  4023  4180 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-06 19:03:47.952  4023  4180 D BluetoothAdapterProperties: Setting state to 10
09-06 19:03:47.952  4023  4180 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 19:03:47.954  4023  4180 I BluetoothAdapterState: Entering OffState
,09-06 19:03:47.955   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 19:03:47.985  4023  4023 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-06 19:03:47.985  4023  4023 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 19:03:47.986  4023  4181 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 19:03:47.994  4023  4181 D bt_stack_manager: event_clean_up_stack finished.
,09-06 19:03:47.995  4023  4023 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:03:48.003  4023  4023 I art     : System.exit called, status: 0
09-06 19:03:48.004  4023  4023 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:03:48.066   871   881 I ActivityManager: Process com.android.bluetooth (pid 4023) has died
,09-06 19:03:50.469  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:50.469  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:53.477  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:53.477  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e252ba4 added. We now have 6 listener(s)
09-06 19:03:53.478  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:53.482  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:53.482  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df7bd0d added. We now have 7 listener(s)
09-06 19:03:53.483  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:53.484  3844  3894 I System.out: IsBluetoothEnabled
,09-06 19:03:53.497  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:53.556   871   888 I ActivityManager: Start proc 4229:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 19:03:53.694  4229  4229 D AdapterServiceConfig: Adding HeadsetService
,09-06 19:03:53.694  4229  4229 D AdapterServiceConfig: Adding A2dpService
,09-06 19:03:53.694  4229  4229 D AdapterServiceConfig: Adding HidService
,09-06 19:03:53.694  4229  4229 D AdapterServiceConfig: Adding HealthService
,09-06 19:03:53.695  4229  4229 D AdapterServiceConfig: Adding PanService
,09-06 19:03:53.695  4229  4229 D AdapterServiceConfig: Adding GattService
,09-06 19:03:53.695  4229  4229 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:03:53.710   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26913b2:true
,09-06 19:03:53.712  4229  4229 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 19:03:53.722  4229  4229 I bt_bluedroid: init
,09-06 19:03:53.722  4229  4241 I BluetoothAdapterState: Entering OffState
,09-06 19:03:53.725  4229  4242 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:03:53.725  4229  4242 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:03:53.725  4229  4242 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:03:53.726  4229  4242 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 19:03:53.726  4229  4229 I bt_bluedroid: get_profile_interface socket
,09-06 19:03:53.731  4229  4229 I bt_bluedroid: get_profile_interface sdp
,09-06 19:03:53.734  4229  4245 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:03:53.738  4229  4245 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:03:53.738  4229  4240 I bt_bluedroid: config_hci_snoop_log
,09-06 19:03:53.742   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:03:53.752  4229  4241 D BluetoothAdapterState: Current state: OFF, message: 0
09-06 19:03:53.752  4229  4241 D BluetoothAdapterProperties: Setting state to 14
09-06 19:03:53.753  4229  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:03:53.758  4229  4241 D BluetoothBondStateMachine: make
,09-06 19:03:53.763  4229  4246 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:03:53.772  4229  4229 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:03:53.773  4229  4241 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:03:53.779  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:53.780  4229  4229 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:03:53.781  4229  4229 D BtGatt.GattService: Received start request. Starting profile...
,09-06 19:03:53.781  4229  4229 D BtGatt.GattService: start(),
,09-06 19:03:53.782  4229  4229 I bt_bluedroid: get_profile_interface gatt
09-06 19:03:53.784  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
09-06 19:03:53.784  4229  4229 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:03:53.796  4229  4229 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:03:53.796  4229  4229 V BluetoothAdapterState: isTurningOn()=false
09-06 19:03:53.796  4229  4229 V BluetoothAdapterState: isBleTurningOn()=true
09-06 19:03:53.797  4229  4229 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:53.797  4229  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-06 19:03:53.798  4229  4241 I bt_bluedroid: enable
,09-06 19:03:53.799  4229  4242 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 19:03:53.799  4229  4242 I bt_hci  : start_up
,09-06 19:03:53.808  4229  4242 I bt_vendor: alloc value 0xb3a09189
,09-06 19:03:53.808  4229  4242 I bt_vendor: init
09-06 19:03:53.808  4229  4242 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 19:03:53.808  4229  4242 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:03:53.916  4229  4242 D bt_hci  : start_up starting async portion
,09-06 19:03:53.916  4229  4249 I bt_hci  : event_finish_startup
09-06 19:03:53.916  4229  4249 I bt_hci_h4: hal_open
,09-06 19:03:53.918  4229  4249 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:03:53.928  4229  4249 I bt_userial_vendor: device fd = 51 open
,09-06 19:03:53.954   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-06 19:03:53.961  4229  4249 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:03:53.976  1892  1892 I Keyboard.Facilitator: onFinishInput()
,09-06 19:03:53.982   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:03:53.982   871   891 I Adreno  : Build Date                       : 10/20/15
09-06 19:03:53.982   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:03:53.982   871   891 I Adreno  : Local Branch                     : M14
09-06 19:03:53.982   871   891 I Adreno  : Remote Branch                    : 
09-06 19:03:53.982   871   891 I Adreno  : Remote Branch                    : 
09-06 19:03:53.982   871   891 I Adreno  : Reconstruct Branch               : 
,09-06 19:03:53.990  4229  4249 D bt_hwcfg: Chipset BCM4354A2
,09-06 19:03:53.995  4229  4249 D bt_hwcfg: Target name = [BCM4354A2]
,09-06 19:03:53.996  4229  4249 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:03:54.035   281  1291 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (610 us)
,09-06 19:03:54.730  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:03:54.731  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:03:54.757  4229  4249 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:03:54.758  4229  4249 D bt_hwcfg: Settlement delay -- 100 ms
09-06 19:03:54.758  4229  4249 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:03:54.765   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-06 19:03:54.767  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b91d7aa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@323a4c2, 16908290=android.view.AbsSavedState$1@323a4c2}, android:focusedViewId=100}]}]
,09-06 19:03:54.767  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 19:03:54.768  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:03:54.768  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-06 19:03:54.770   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-06 19:03:54.775   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,09-06 19:03:54.775   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-06 19:03:54.776   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-06 19:03:54.817   871   880 I art     : Background partial concurrent mark sweep GC freed 38149(2MB) AllocSpace objects, 15(604KB) LOS objects, 33% free, 28MB/43MB, paused 1.506ms total 114.359ms
,09-06 19:03:54.874  4229  4249 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:03:54.876  4229  4249 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:03:54.907  4229  4249 I bt_hwcfg: vendor lib fwcfg completed
,09-06 19:03:54.908  4229  4249 I bt_vendor: firmware callback
,09-06 19:03:54.908  4229  4249 I bt_hci  : firmware_config_callback
,09-06 19:03:54.919  4229  4254 I bt_btu  : btu_task pending for preload complete event
,09-06 19:03:54.919  4229  4254 I bt_btu_task: Bluetooth chip preload is complete
,09-06 19:03:54.919  4229  4254 I bt_btu  : btu_task received preload complete event
,09-06 19:03:54.929  4229  4254 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:03:54.929  4229  4254 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:03:54.930  4229  4254 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 19:03:54.930  4229  4254 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:03:54.930  4229  4254 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:03:54.930  4229  4254 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:03:54.931  4229  4254 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:03:54.931  4229  4254 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:03:54.931  4229  4254 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:03:54.932  4229  4254 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:03:54.932  4229  4254 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:03:54.932  4229  4254 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:03:54.932  4229  4254 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:03:54.933  4229  4254 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:03:54.933  4229  4254 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:03:55.007   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-06 19:03:55.009   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-06 19:03:55.010   871  1328 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
09-06 19:03:55.016   871   891 I DreamManagerService: Entering dreamland.
,09-06 19:03:55.019   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-06 19:03:55.022   871   891 I PowerManagerService: Dozing...
,09-06 19:03:55.057  4229  4254 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3986d9d
,09-06 19:03:55.057  4229  4254 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3986d9d 
,09-06 19:03:55.062   374  1273 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-06 19:03:55.062   374  1273 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
09-06 19:03:55.063  4229  4245 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 19:03:55.064  4229  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:03:55.065  4229  4245 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:03:55.067  4229  4245 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:03:55.071  4229  4245 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:03:55.071  4229  4245 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:03:55.071  4229  4245 D bt_hci  : do_postload posting postload work item
,09-06 19:03:55.071  4229  4249 I bt_hci  : event_postload
,09-06 19:03:55.072  4229  4249 I bt_vendor: sco_config_cb
,09-06 19:03:55.072  4229  4249 I bt_hci  : sco_config_callback postload finished.
,09-06 19:03:55.072   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 19:03:55.073  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:55.074  4229  4245 D bt_bte_conf: Device ID record 1 : primary
09-06 19:03:55.074  4229  4245 D bt_bte_conf:   vendorId            = 000f
09-06 19:03:55.074  4229  4245 D bt_bte_conf:   vendorIdSource      = 0001
,09-06 19:03:55.075  4229  4245 D bt_bte_conf:   product             = 1200
09-06 19:03:55.075  4229  4245 D bt_bte_conf:   version             = 1436
09-06 19:03:55.075  4229  4245 D bt_bte_conf:   clientExecutableURL = 
09-06 19:03:55.075  4229  4245 D bt_bte_conf:   serviceDescription  = 
,09-06 19:03:55.075  4229  4245 D bt_bte_conf:   documentationURL    = 
09-06 19:03:55.076  4229  4249 I bt_vendor: low_power_mode_cb
09-06 19:03:55.076  4229  4245 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-06 19:03:55.076  4229  4242 D bt_stack_manager: event_start_up_stack finished
09-06 19:03:55.076   871  1303 E native  : do suspend false
09-06 19:03:55.076  4229  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 19:03:55.077  4229  4241 D BluetoothAdapterProperties: Setting state to 15
,09-06 19:03:55.077  4229  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-06 19:03:55.078  4229  4241 I BluetoothAdapterState: Entering BleOnState
,09-06 19:03:55.082  4229  4241 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 19:03:55.083  4229  4241 D BluetoothAdapterProperties: Setting state to 11
,09-06 19:03:55.083  4229  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 19:03:55.087  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:55.087  4229  4229 D HeadsetService: Received start request. Starting profile...
09-06 19:03:55.086  1965  4260 D NfcService: Discovery configuration equal, not updating.
09-06 19:03:55.090  4229  4229 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 19:03:55.091  4229  4229 D HeadsetStateMachine: make
,09-06 19:03:55.097  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:55.099  4229  4241 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:03:55.102  4229  4229 D HeadsetStateMachine: max_hf_connections = 1
09-06 19:03:55.102  4229  4229 I bt_bluedroid: get_profile_interface handsfree
09-06 19:03:55.102  4229  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-06 19:03:55.102  4229  4245 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 19:03:55.108  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:55.108  4229  4229 D A2dpService: Received start request. Starting profile...
09-06 19:03:55.109  4229  4229 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:03:55.109  4229  4229 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:03:55.110   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:03:55.113   871  1303 E native  : do suspend true
,09-06 19:03:55.114  4229  4229 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:03:55.114  4229  4229 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:03:55.114  4229  4229 D A2dpStateMachine: make
,09-06 19:03:55.116  4229  4229 I bt_bluedroid: get_profile_interface a2dp
09-06 19:03:55.116  4229  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:03:55.120  4229  4266 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:03:55.121  4229  4229 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:03:55.121  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
09-06 19:03:55.122  4229  4229 D HidService: Received start request. Starting profile...
,09-06 19:03:55.122  4229  4229 I bt_bluedroid: get_profile_interface hidhost
09-06 19:03:55.122  4229  4245 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39683e5
09-06 19:03:55.122  4229  4245 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-06 19:03:55.123  4229  4229 D HidService: setHidService(): set to: null
,09-06 19:03:55.123  4229  4229 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:03:55.124  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:55.124  4229  4229 D HealthService: Received start request. Starting profile...
,09-06 19:03:55.125  4229  4229 I bt_bluedroid: get_profile_interface health
,09-06 19:03:55.126  4229  4229 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:03:55.127  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
09-06 19:03:55.127  4229  4229 D PanService: Received start request. Starting profile...
09-06 19:03:55.127  4229  4229 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:03:55.127  4229  4229 I bt_bluedroid: get_profile_interface pan
,09-06 19:03:55.128  4229  4245 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:03:55.130  4229  4229 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:55.130  4229  4229 D BluetoothMapService: Received start request. Starting profile...
09-06 19:03:55.130  4229  4229 D BluetoothMapService: start()
,09-06 19:03:55.133  4229  4229 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:03:55.133  4229  4229 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 19:03:55.133  4229  4229 D BluetoothMapAppObserver: createReceiver()
,09-06 19:03:55.134  4229  4229 D BluetoothMapAppObserver: initObservers()
09-06 19:03:55.134  4229  4229 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:03:55.142  4229  4229 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:03:55.142  4229  4229 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:55.142  4229  4263 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:03:55.142  4229  4229 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:55.142  4229  4229 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:55.143  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:03:55.144  4229  4229 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:55.144  4229  4229 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:55.144  4229  4229 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:03:55.144  4229  4229 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:55.144  4229  4229 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:55.144  4229  4229 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:55.145  4229  4229 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:55.146  4229  4229 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:55.146  4229  4229 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:03:55.146  4229  4229 V BluetoothAdapterState: isTurningOff()=false
09-06 19:03:55.146  4229  4229 V BluetoothAdapterState: isTurningOn()=true
09-06 19:03:55.146  4229  4229 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:03:55.146  4229  4229 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:03:55.147  4229  4241 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 19:03:55.147  4229  4241 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:03:55.147  4229  4241 D BluetoothAdapterProperties: State =  11
,09-06 19:03:55.148  4229  4245 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:03:55.148  4229  4245 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:03:55.148  4229  4241 D BluetoothAdapterProperties: Setting state to 12
09-06 19:03:55.148  4229  4241 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:03:55.149   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:03:55.149  3919  3931 D BluetoothPan: onBluetoothStateChange on: true
,09-06 19:03:55.151   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:55.151  3919  4221 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:03:55.151  4229  4241 I BluetoothAdapterState: Entering OnState
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:55.152  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:03:55.153  1359  2085 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:03:55.154  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:55.154   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:55.154   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:03:55.155  3919  3931 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:03:55.155  1359  1359 D BluetoothInputDevice: Proxy object connected
09-06 19:03:55.155  1359  1359 D HidProfile: Bluetooth service connected
,09-06 19:03:55.156  1359  1370 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:03:55.157  1359  1359 D BluetoothMap: Proxy object connected
,09-06 19:03:55.157  1359  1359 D MapProfile: Bluetooth service connected
09-06 19:03:55.157  1359  1359 D BluetoothMap: getConnectedDevices()
,09-06 19:03:55.157  1359  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:55.158  3919  3919 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:03:55.158  3919  3919 D PanProfile: Bluetooth service connected
,09-06 19:03:55.158  3919  3919 D BluetoothMap: Proxy object connected
09-06 19:03:55.159  3919  3919 D MapProfile: Bluetooth service connected
09-06 19:03:55.159  3919  3919 D BluetoothMap: getConnectedDevices()
,09-06 19:03:55.159  1359  2085 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:03:55.161  1359  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:03:55.161  4229  4229 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:03:55.162  4229  4229 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-06 19:03:55.163  1359  1376 D BluetoothPan: onBluetoothStateChange on: true
,09-06 19:03:55.163  1359  1359 D BluetoothA2dp: Proxy object connected
09-06 19:03:55.163  4229  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:55.165  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:03:55.165  1359  1359 D PanProfile: Bluetooth service connected
09-06 19:03:55.165  4229  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:55.165  3919  4253 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:03:55.166  4229  4229 D ObexServerSockets: Succeed to create listening sockets 
09-06 19:03:55.166  4229  4229 D ObexServerSockets0: startAccept()
09-06 19:03:55.166  4229  4229 D ObexServerSockets0: prepareForNewConnect()
09-06 19:03:55.167  1981  1993 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:03:55.167  3919  3929 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:03:55.168  4229  4229 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:03:55.168  4229  4229 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 19:03:55.169  4229  4271 D ObexServerSockets0: Accepting socket connection...
,09-06 19:03:55.169  4229  4272 D ObexServerSockets0: Accepting socket connection...
09-06 19:03:55.170  3919  4221 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:03:55.172  4229  4229 D BluetoothMapService: onReceive
,09-06 19:03:55.172  4229  4229 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:03:55.172  4229  4229 D BluetoothMapService: STATE_ON
09-06 19:03:55.173  3919  3919 D BluetoothInputDevice: Proxy object connected
,09-06 19:03:55.173  3919  3919 D HidProfile: Bluetooth service connected
09-06 19:03:55.174  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:55.175  3919  3919 D BluetoothA2dp: Proxy object connected
,09-06 19:03:55.180  3919  3919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:03:55.183  3919  3919 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:03:55.186  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:03:55.200  1359  1359 D BluetoothPbap: Proxy object connected
09-06 19:03:55.200  3919  3919 D BluetoothPbap: Proxy object connected
09-06 19:03:55.200  3919  3919 D PbapServerProfile: Bluetooth service connected
09-06 19:03:55.200  1359  1359 D PbapServerProfile: Bluetooth service connected
,09-06 19:03:55.203   374  1311 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-06 19:03:55.203   374  1311 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
09-06 19:03:55.203   871   871 D BluetoothA2dp: Proxy object connected
,09-06 19:03:55.205   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:03:55.207  4229  4229 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 19:03:55.207  4229  4229 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:03:55.210  4229  4277 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:55.229  4229  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:03:55.230  4229  4283 I BtOppRfcommListener: Accept thread started.
,09-06 19:03:55.250   871   871 D BluetoothHeadset: Proxy object connected
,09-06 19:03:55.250   871   888 D BluetoothHeadset: Proxy object connected
,09-06 19:03:55.250  1981  2059 D BluetoothHeadset: Proxy object connected
09-06 19:03:55.251   871   871 D BluetoothHeadset: Proxy object connected
09-06 19:03:55.251  3919  3931 D BluetoothHeadset: Proxy object connected
09-06 19:03:55.251  3919  3919 D HeadsetProfile: Bluetooth service connected
09-06 19:03:55.251  1359  2085 D BluetoothHeadset: Proxy object connected
09-06 19:03:55.252   871   871 D BluetoothHeadset: Proxy object connected
09-06 19:03:55.252  1359  1359 D HeadsetProfile: Bluetooth service connected
,09-06 19:03:55.254   871   888 D BluetoothHeadset: Proxy object connected
,09-06 19:03:55.258  1359  1370 D BluetoothHeadset: Proxy object connected
,09-06 19:03:55.258  1359  1359 D HeadsetProfile: Bluetooth service connected
,09-06 19:03:55.267  1981  1994 D BluetoothHeadset: Proxy object connected
,09-06 19:03:55.270  3919  3929 D BluetoothHeadset: Proxy object connected
,09-06 19:03:55.271  3919  3919 D HeadsetProfile: Bluetooth service connected
,09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:55.519  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:55.526  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:55.529  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:55.530  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26c72d3 added. We now have 8 listener(s)
,09-06 19:03:55.530  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:55.536   871  2007 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,09-06 19:03:55.536   871  2007 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:03:55.549  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:55.550   871  2009 D WifiService: setWifiEnabled: true pid=3844, uid=10000
09-06 19:03:55.550   871  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:03:55.571   871  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:55.580  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:55.589  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:55.610   871  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:03:55.611   871  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 19:03:55.612   871  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 19:03:55.613   871  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:03:55.613   871  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-06 19:03:55.613   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 19:03:55.614   871  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:03:55.629   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:03:55.630   370   869 D CommandListener: Setting iface cfg
,09-06 19:03:55.630   871  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)',
09-06 19:03:55.631   871  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:03:55.632   871  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.06 delta 1000 -> 1000
,09-06 19:03:55.633   871  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-06 19:03:55.635   871  1300 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 19:03:55.636   871  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 19:03:55.656   871  1303 E native  : do suspend true
,09-06 19:03:55.689   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:03:55.690   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:55.702   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:03:55.765   871  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:03:55.767  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:03:56.193  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:03:56.239  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:03:56.239  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 19:03:56.247   871  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:03:56.260   871  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:03:56.260   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:56.260   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 19:03:56.281   871  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:03:56.292   370   869 D CommandListener: Setting iface cfg
,09-06 19:03:56.293   871  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,09-06 19:03:56.302   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 19:03:56.334   871  4291 D DhcpClient: Receive thread started
,09-06 19:03:56.426   871  1303 E native  : do suspend false
,09-06 19:03:56.449   871  2069 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 19:03:56.463   871  4291 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-06 19:03:56.465   871  2069 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-06 19:03:56.468   871  2069 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:03:56.483   871  4291 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 19:03:56.484   871  2069 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 19:03:56.490   370   869 D CommandListener: Setting iface cfg
,09-06 19:03:56.502   871  2069 D DhcpClient: Scheduling renewal in 86399s
,09-06 19:03:56.503   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 19:03:56.506   871  1303 E native  : do suspend true
,09-06 19:03:56.537   871  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 19:03:56.541   871  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-06 19:03:56.543   871  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 19:03:56.546   871  1305 D ConnectivityService: Adding iface wlan0 to network 102
,09-06 19:03:56.560   871  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:03:56.574  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:03:56.577  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:03:56.581  3844  3894 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:03:56.581  3844  3894 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:03:56.583  3844  3894 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b91d7aa Bundle[{}]
,09-06 19:03:56.584  3844  3894 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:03:56.584  3844  3894 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:03:56.585  3844  3894 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:03:56.585  3844  3894 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 19:03:56.586  3844  3894 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:03:56.586  3844  3894 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:03:56.591  3844  3894 I System.out: Running OutgoingSocketThread
,09-06 19:03:56.592  3844  4295 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
,09-06 19:03:56.593  3844  4295 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45532
,09-06 19:03:56.593  3844  4295 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:03:56.603   871  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:03:56.604   871  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-06 19:03:56.605   871  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-06 19:03:56.606   871  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-06 19:03:56.607   871  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-06 19:03:56.614   871  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:03:56.619   871  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-06 19:03:56.619   871  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-06 19:03:56.620   871  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-06 19:03:56.620   871  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:03:56.621   871  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-06 19:03:56.621   871  1305 D ConnectivityService:    accepting network in place of null
,09-06 19:03:56.622   871  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:03:56.679   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:56.713   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:03:56.722   871  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-06 19:03:56.722   871  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:56.733   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:03:56.733   871  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:56.749  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:56.755  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:56.771  1700  1700 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:03:56.774  1700  1700 D SystemUpdateService: onCreate
,09-06 19:03:56.779  1700  1700 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:03:56.792  1700  4302 I SystemUpdateService: active receiver: enabled
,09-06 19:03:56.801  1700  4302 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:03:56.805  1700  1700 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:03:56.811  1700  4302 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-06 19:03:56.812  1700  4302 I SystemUpdateService: now status is 0 (complete)
09-06 19:03:56.812  1700  4302 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:03:56.812  1700  4302 I SystemUpdateService: file has been verified
09-06 19:03:56.812  1700  4302 I SystemUpdateService: OTA package size = 12249756
,09-06 19:03:56.806  1700  2527 I iu.UploadsManager: num queued entries: 0
,09-06 19:03:56.817  1700  1700 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:03:56.819  1700  1700 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:03:56.821  4037  4037 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:03:56.824  1700  4305 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-06 19:03:56.825  1700  4305 W BaseAppContext: Using Auth Proxy for data requests.
,09-06 19:03:56.826  1700  4305 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 19:03:56.829  1700  2527 I iu.UploadsManager: num updated entries: 0
,09-06 19:03:56.831  4037  4037 D SprintDMHelper: simOperator: 
,09-06 19:03:56.831  4037  4037 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:03:56.834  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:03:56.837  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:03:56.855  1700  2527 I iu.SyncManager: NEXT; no task
,09-06 19:03:56.862  1700  4302 I SystemUpdateService: showing system update notification
,09-06 19:03:56.871  1497  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 19:03:56.871  1497  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-06 19:03:56.872  1497  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-06 19:03:56.873  1497  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:03:56.878  1497  2259 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-06 19:03:56.892  1700  1700 D SystemUpdateService: onDestroy
,09-06 19:03:56.899  1700  4305 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-06 19:03:57.594  3844  3894 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,09-06 19:03:57.594  3844  3894 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,09-06 19:03:57.604  3844  3894 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,09-06 19:03:57.606  3844  3894 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 19:03:57.606  3844  3894 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,09-06 19:03:57.613  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:57.613  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55b5e10 added. We now have 2 listener(s)
,09-06 19:03:57.615  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:03:57.615  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:57.615  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:03:57.615  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:57.615  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef01d09 added. We now have 9 listener(s)
09-06 19:03:57.616  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:57.616  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:03:57.620  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:57.627  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:57.630  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:57.630  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:57.631  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:57.632  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@781692f added. We now have 3 listener(s)
,09-06 19:03:57.634  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:57.636  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:57.638  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:03:57.638  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:03:57.638  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:57.639  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:57.639  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9804b3c added. We now have 10 listener(s)
09-06 19:03:57.640  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:57.640  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:03:57.641  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:57.641  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:57.642  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:57.643  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.643  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:57.643  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:57.644  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55b5e10 removed from the list
09-06 19:03:57.644  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:57.645  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef01d09 removed from the list
09-06 19:03:57.645  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:57.645  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.646  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.647  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:57.648  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.648  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:57.649  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.649  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef01d09 not in the list
09-06 19:03:57.649  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.649  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.651  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:57.651  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.651  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.652  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9804b3c removed from the list
09-06 19:03:57.652  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:57.652  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.652  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.653  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:57.653  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@781692f removed from the list
09-06 19:03:57.655  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:57.655  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef480c5 added. We now have 2 listener(s)
,09-06 19:03:57.661  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:03:57.662  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:57.662  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:57.662  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:57.663  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab50a1a added. We now have 9 listener(s)
09-06 19:03:57.663  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:57.664  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:03:57.670  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:57.676  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:57.678  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:57.679  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:03:57.679  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:57.679  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a4df28 added. We now have 3 listener(s)
,09-06 19:03:57.681  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:03:57.681  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:03:57.681  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:03:57.681  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:03:57.681  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b216441 added. We now have 10 listener(s)
,09-06 19:03:57.681  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:57.682  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:03:57.682  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:03:57.682  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:03:57.682  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:57.682  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:03:57.682  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:57.686  3844  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 19:03:57.686  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:03:57.688  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:57.692  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:57.693  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:03:57.694  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:57.699  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:03:57.699  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:57.699  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:03:57.700  3844  3894 D BluetoothAdapter: STATE_ON,
,09-06 19:03:57.706  4229  4264 D BtGatt.GattService: registerClient() - UUID=e608e559-8533-4b32-a726-0091776d57d1
,09-06 19:03:57.707  4229  4245 D BtGatt.GattService: onClientRegistered() - UUID=e608e559-8533-4b32-a726-0091776d57d1, clientIf=5
,09-06 19:03:57.708  3844  3890 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:03:57.709  4229  4239 D BtGatt.GattService: start scan with filters
,09-06 19:03:57.716  4229  4248 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:57.717  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:03:57.717  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:57.717  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:57.717  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:57.721   871  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-06 19:03:57.722  4229  4248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9d35f9e
,09-06 19:03:57.725  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:57.726  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:57.727  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:57.728  4229  4245 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:03:57.728  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.729  4229  4248 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:03:57.733  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:57.740  3844  3894 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:03:57.741  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:57.741  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:03:57.741  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.742  4229  4245 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 19:03:57.742  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.742  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:03:57.743  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:03:57.743  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:03:57.743  4229  4248 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:57.743  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:03:57.743  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:57.743  4229  4248 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 19:03:57.744  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:03:57.744  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:57.746  3844  3894 D BluetoothAdapter: STATE_ON
09-06 19:03:57.747  4229  4239 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:03:57.749  4229  4273 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 19:03:57.750  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:03:57.752  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:57.752  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:57.752  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:03:57.752  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:03:57.753  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:57.753  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:03:57.753  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:57.754  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:03:57.754  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:57.755  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:57.755  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:03:57.755  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:57.758  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:57.758  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:57.758  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:03:57.758  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:57.758  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.758  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:57.759  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:57.759  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef480c5 removed from the list
09-06 19:03:57.759  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:57.759  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab50a1a removed from the list
,09-06 19:03:57.759  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:57.759  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:57.759  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.759  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:57.760  4229  4245 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:03:57.760  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.760  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.761  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:03:57.761  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.761  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab50a1a not in the list
,09-06 19:03:57.761  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.761  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:57.762  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:57.762  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.762  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.762  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b216441 removed from the list
09-06 19:03:57.762  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:57.762  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.762  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:57.763  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:57.763  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a4df28 removed from the list
,09-06 19:03:57.763  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:57.764  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdf037d added. We now have 2 listener(s)
09-06 19:03:57.765  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:03:57.766  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:57.766  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:57.766  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:57.766  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2c272 added. We now have 9 listener(s)
09-06 19:03:57.766  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:57.767  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:03:57.768  4229  4245 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 19:03:57.768  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.773  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:57.779   871  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156794, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:57.779  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:03:57.780  4229  4245 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 19:03:57.780  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.780  4229  4248 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:57.784  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:57.784  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:57.784  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:57.785  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64a6b40 added. We now have 3 listener(s)
,09-06 19:03:57.787  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:03:57.787  4229  4245 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:03:57.787  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-06 19:03:57.787  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:57.787  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:57.788  4229  4248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:03:57.788  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:57.788  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddd5a79 added. We now have 10 listener(s)
,09-06 19:03:57.788  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:57.788  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:57.788  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:57.790  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:57.790  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:03:57.791  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:57.791  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:57.791  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:03:57.793  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:57.794  4229  4245 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:03:57.794  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.795  3844  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:03:57.795  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:03:57.798  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:03:57.798  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:03:57.798  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:03:57.800  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:03:57.801  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:57.801  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:03:57.801  3844  3894 D BluetoothAdapter: STATE_ON
,09-06 19:03:57.803  4229  4240 D BtGatt.GattService: registerClient() - UUID=ea28dee2-6751-44d3-9590-1abbdabec752
,09-06 19:03:57.803  4229  4245 D BtGatt.GattService: onClientRegistered() - UUID=ea28dee2-6751-44d3-9590-1abbdabec752, clientIf=5
,09-06 19:03:57.803  3844  3890 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:03:57.803  4229  4264 D BtGatt.GattService: start scan with filters
,09-06 19:03:57.805  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:03:57.805  4229  4248 D BtGatt.ScanManager: handling starting scan
09-06 19:03:57.805  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:03:57.806  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:03:57.806  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-06 19:03:57.808  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:57.808  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:03:57.808  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:03:57.809  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-06 19:03:57.811  4229  4245 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:03:57.811  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.811  4229  4248 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:03:57.812  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:03:57.812  3844  3894 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-06 19:03:57.812  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:57.813  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:57.813  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-06 19:03:57.813  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:57.813  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.813  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:03:57.813  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:03:57.813  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bdf037d removed from the list
09-06 19:03:57.813  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 19:03:57.813  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2c272 removed from the list
09-06 19:03:57.813  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:03:57.813  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:57.814  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.814  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-06 19:03:57.814  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.814  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:57.814  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:03:57.815  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:03:57.815  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:57.815  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2c272 not in the list
,09-06 19:03:57.815  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:57.815  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:03:57.815  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:03:57.815  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:03:57.815  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:03:57.815  3844  3894 D BluetoothAdapter: STATE_ON
,09-06 19:03:57.816  4229  4273 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:03:57.816  4229  4245 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 19:03:57.816  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.816  4229  4240 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:03:57.817  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-06 19:03:57.817  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:03:57.817  4229  4248 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:03:57.817  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 19:03:57.817  4229  4248 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 19:03:57.817  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:03:57.817  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:03:57.818  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:57.818  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:57.818  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-06 19:03:57.818  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:03:57.818  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.819  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:03:57.819  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:03:57.819  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:03:57.819  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddd5a79 removed from the list
,09-06 19:03:57.819  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:57.819  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.819  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:57.819  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:57.819  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:03:57.819  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-06 19:03:57.819  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64a6b40 removed from the list
,09-06 19:03:57.820  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:03:57.820  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:57.820  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed02535 added. We now have 2 listener(s)
09-06 19:03:57.822  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:03:57.822  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:57.822  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:03:57.823  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:57.823  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f42dca added. We now have 9 listener(s)
,09-06 19:03:57.823  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:57.823  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:03:57.826  4229  4245 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:03:57.826  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.826  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:03:57.831  4229  4245 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
09-06 19:03:57.831  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:57.832  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:57.834  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:57.834  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:57.834  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:57.834  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6626258 added. We now have 3 listener(s)
09-06 19:03:57.836  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:57.837  4229  4245 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:03:57.837  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.837  4229  4248 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:03:57.838  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:57.839  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:03:57.839  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-06 19:03:57.840  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:57.840  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-06 19:03:57.840  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eadfb1 added. We now have 10 listener(s)
09-06 19:03:57.840  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:03:57.840  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:57.840  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:03:57.840  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:03:57.840  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:57.840  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:03:57.843  4229  4245 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:03:57.843  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.843  4229  4248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:03:57.845  3844  3894 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 19:03:57.845  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:03:57.848  4229  4245 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:03:57.848  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.848  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:03:57.849  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-06 19:03:57.849  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:03:57.851  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:03:57.851  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:03:57.852  3844  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:03:57.852  3844  3894 D BluetoothAdapter: STATE_ON
,09-06 19:03:57.853  4229  4273 D BtGatt.GattService: registerClient() - UUID=535f4a55-1633-4119-a36a-2f9c67a4d6ec
09-06 19:03:57.854  4229  4245 D BtGatt.GattService: onClientRegistered() - UUID=535f4a55-1633-4119-a36a-2f9c67a4d6ec, clientIf=5
,09-06 19:03:57.854  3844  3890 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:03:57.854  4229  4239 D BtGatt.GattService: start scan with filters
09-06 19:03:57.856  4229  4248 D BtGatt.ScanManager: handling starting scan
,09-06 19:03:57.856  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:03:57.856  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:03:57.857  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:03:57.857  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:03:57.859  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:57.859  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-06 19:03:57.859  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:03:57.860  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:03:57.861  4229  4245 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:03:57.861  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.862  4229  4248 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:03:57.864  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:57.864  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:57.864  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:03:57.864  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:57.864  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.864  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:03:57.864  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:57.864  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed02535 removed from the list
,09-06 19:03:57.864  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.864  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f42dca removed from the list
09-06 19:03:57.864  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:03:57.864  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:03:57.865  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.865  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-06 19:03:57.865  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.865  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:57.865  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.865  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:57.865  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.865  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f42dca not in the list
,09-06 19:03:57.865  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:03:57.866  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:03:57.866  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:03:57.866  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 19:03:57.866  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:03:57.866  3844  3894 D BluetoothAdapter: STATE_ON
09-06 19:03:57.866  4229  4245 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:03:57.866  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.866  4229  4264 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:03:57.867  4229  4248 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:03:57.867  4229  4248 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:03:57.867  4229  4240 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 19:03:57.867  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:03:57.867  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:03:57.867  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:03:57.867  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:03:57.867  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:03:57.868  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:57.868  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:03:57.868  3844  3894 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:03:57.868  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:03:57.869  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.869  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:57.869  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.869  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.869  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:57.869  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eadfb1 removed from the list
09-06 19:03:57.869  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:57.870  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.870  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:03:57.870  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.870  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:57.870  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:03:57.870  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6626258 removed from the list
09-06 19:03:57.870  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:03:57.870  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc5ed added. We now have 2 listener(s)
09-06 19:03:57.872  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:03:57.872  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:03:57.872  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:57.872  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:57.872  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dcac22 added. We now have 9 listener(s)
09-06 19:03:57.872  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:57.872  3844  3894 I org.thaliproject.p2p.btconnectorlib.Disco,veryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:03:57.874  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:03:57.876  4229  4245 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:03:57.876  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:03:57.877  3844  3894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:03:57.878  3844  3894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:03:57.878  3844  3894 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:03:57.878  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:03:57.878  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16f2470 added. We now have 3 listener(s)
,09-06 19:03:57.880  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:03:57.880  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:03:57.880  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:03:57.880  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:03:57.880  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80cd3e9 added. We now have 10 listener(s)
,09-06 19:03:57.880  3844  3894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:03:57.881  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:03:57.881  3844  3894 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:03:57.881  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:57.881  3844  3894 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:03:57.881  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:03:57.881  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.881  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:03:57.881  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:03:57.881  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc5ed removed from the list
,09-06 19:03:57.881  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.881  4229  4245 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:03:57.881  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.881  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dcac22 removed from the list
09-06 19:03:57.883  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:03:57.883  3844  3894 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:03:57.883  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.883  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:03:57.883  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:03:57.884  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.884  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:57.884  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.884  3844  3894 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dcac22 not in the list
,09-06 19:03:57.884  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.884  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.885  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:03:57.885  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:03:57.885  3844  3894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:03:57.885  3844  3894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80cd3e9 removed from the list
,09-06 19:03:57.885  3844  3894 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:03:57.885  3844  3894 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:03:57.885  3844  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:03:57.885  3844  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:03:57.885  3844  3894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16f2470 removed from the list
09-06 19:03:57.886  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-06 19:03:57.886  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:03:57.886  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-06 19:03:57.886  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:03:57.886  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:03:57.886  3844  3894 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:03:57.887  4229  4245 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:03:57.887  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:03:57.887  4229  4248 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:03:57.891  3844  4311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
,09-06 19:03:57.892  3844  4311 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
09-06 19:03:57.892  3844  4311 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:03:57.893  4229  4245 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:03:57.893  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.893  4229  4248 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 19:03:57.894  3844  4312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
09-06 19:03:57.894  3844  4312 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
09-06 19:03:57.894  3844  4312 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:03:57.897  3844  3894 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-06 19:03:57.897  3844  3894 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:03:57.897  4229  4245 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:03:57.897  3844  3894 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:03:57.897  4229  4245 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:03:57.897  3844  3894 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:03:57.897  3844  3894 D com.test.thalitest.ThaliTestRunner: Total duration: 22965 ms
,09-06 19:03:57.899  3844  3894 I jxcore-log: *Native tests were executed*
09-06 19:03:57.899  3844  3894 I jxcore-log: 
,09-06 19:03:57.899  3844  3894 I jxcore-log: Total number of executed tests:  80
09-06 19:03:57.899  3844  3894 I jxcore-log: 
,09-06 19:03:57.900  3844  3894 I jxcore-log: Number of passed tests:  80
09-06 19:03:57.900  3844  3894 I jxcore-log: 
,09-06 19:03:57.900  3844  3894 I jxcore-log: Number of failed tests:  0
09-06 19:03:57.900  3844  3894 I jxcore-log: 
09-06 19:03:57.901  3844  3894 I jxcore-log: Number of ignored tests:  0
09-06 19:03:57.901  3844  3894 I jxcore-log: 
09-06 19:03:57.901  3844  3894 I jxcore-log: Total duration:  22965
09-06 19:03:57.901  3844  3894 I jxcore-log: 
,09-06 19:03:57.901  3844  3894 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:03:57.901  3844  3894 I jxcore-log: 
,09-06 19:03:57.904  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.904  3844  3894 I jxcore-log: 
09-06 19:03:57.906  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.906  3844  3894 I jxcore-log: 
09-06 19:03:57.907  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.907  3844  3894 I jxcore-log: 
09-06 19:03:57.907  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.907  3844  3894 I jxcore-log: 
09-06 19:03:57.908  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.908  3844  3894 I jxcore-log: 
09-06 19:03:57.909  3844  3844 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:03:57.909  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.909  3844  3894 I jxcore-log: 
09-06 19:03:57.911  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.911  3844  3894 I jxcore-log: 
,09-06 19:03:57.913  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.913  3844  3894 I jxcore-log: 
09-06 19:03:57.914  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.914  3844  3894 I jxcore-log: 
09-06 19:03:57.914  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:57.914  3844  3894 I jxcore-log: 
09-06 19:03:57.915  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:03:57.915  3844  3894 I jxcore-log: 
09-06 19:03:57.916  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:03:57.916  3844  3894 I jxcore-log: 
09-06 19:03:57.917  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.917  3844  3894 I jxcore-log: 
,09-06 19:03:57.918  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.918  3844  3894 I jxcore-log: 
,09-06 19:03:57.919  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:03:57.919  3844  3894 I jxcore-log: 
,09-06 19:03:57.920  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:03:57.920  3844  3894 I jxcore-log: 
,09-06 19:03:57.921  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.921  3844  3894 I jxcore-log: 
,09-06 19:03:57.922  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.922  3844  3894 I jxcore-log: 
,09-06 19:03:57.923  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.923  3844  3894 I jxcore-log: 
,09-06 19:03:57.923  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.923  3844  3894 I jxcore-log: 
,09-06 19:03:57.924  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.924  3844  3894 I jxcore-log: 
,09-06 19:03:57.925  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.925  3844  3894 I jxcore-log: 
,09-06 19:03:57.925  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.925  3844  3894 I jxcore-log: 
,09-06 19:03:57.926  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:03:57.926  3844  3894 I jxcore-log: 
,09-06 19:03:57.927  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:57.927  3844  3894 I jxcore-log: 
,09-06 19:03:57.927  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:03:57.927  3844  3894 I jxcore-log: 
,09-06 19:03:57.928  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.928  3844  3894 I jxcore-log: 
,09-06 19:03:57.929  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.929  3844  3894 I jxcore-log: 
,09-06 19:03:57.930  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.930  3844  3894 I jxcore-log: 
,09-06 19:03:57.930  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.930  3844  3894 I jxcore-log: 
,09-06 19:03:57.931  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.931  3844  3894 I jxcore-log: 
,09-06 19:03:57.932  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:03:57.932  3844  3894 I jxcore-log: 
,09-06 19:03:58.256  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:03:58.258  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:58.258  3844  3894 I jxcore-log: 
,09-06 19:03:58.320  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:03:58.323  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:58.323  3844  3894 I jxcore-log: 
,09-06 19:03:58.370  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:03:58.373  3844  3894 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:03:58.373  3844  3894 I jxcore-log: 
,09-06 19:03:58.634  4313  4313 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-06 19:03:58.639  4313  4313 D AndroidRuntime: CheckJNI is OFF
,09-06 19:03:58.682  4313  4313 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-06 19:03:58.731  4313  4313 I Radio-JNI: register_android_hardware_Radio DONE
09-06 19:03:58.754  4313  4313 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-06 19:03:58.767   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-06 19:03:58.768   871   884 I ActivityManager: Killing 3844:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-06 19:03:58.866   871  2014 D GraphicsStats: Buffer count: 2
09-06 19:03:58.866   871  1690 I WindowState: WIN DEATH: Window{ef8d038 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 19:03:58.867   871  1304 D WifiService: Client connection lost with reason: 4
,09-06 19:03:58.901   871   894 W PackageSettings: Skipping PackageSetting{fecc5b3 com.example.hello/10273} due to missing metadata
,09-06 19:03:58.933   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-06 19:03:58.934   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-06 19:03:58.936   871   894 I art     : Starting a blocking GC Explicit
,09-06 19:03:58.939   871   884 E ActivityManager: Failure starting process com.test.thalitest
09-06 19:03:58.939   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-06 19:03:58.939   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:58.939   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:58.939   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:03:58.939   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-06 19:03:58.942   871   884 I ActivityManager:   Force finishing activity ActivityRecord{ea447f9 u0 com.test.thalitest/.MainActivity t2}
,09-06 19:03:58.959   871  2014 W ActivityManager: Spurious death for ProcessRecord{b82f53d 0:com.test.thalitest/u0a0}, curProc for 3844: null
,09-06 19:03:59.000   871   894 I art     : Explicit concurrent mark sweep GC freed 54793(3MB) AllocSpace objects, 10(300KB) LOS objects, 33% free, 29MB/43MB, paused 1.220ms total 63.227ms
,09-06 19:03:59.050   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-06 19:03:59.052  4313  4313 I art     : System.exit called, status: 0
,09-06 19:03:59.052  4313  4313 I AndroidRuntime: VM exiting with result code 0.
09-06 19:03:59.056   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-06 19:03:59.064   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-06 19:03:59.069  4229  4229 D BluetoothMapAppObserver: onReceive
09-06 19:03:59.069  4229  4229 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-06 19:03:59.081   871  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:03:59.082  1860  2268 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:03:59.082  3660  3660 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-06 19:03:59.102  1981  1981 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-06 19:03:59.102   871  2013 I ActivityManager: Start proc 4326:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-06 19:03:59.105  1892  1892 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-06 19:03:59.125  1892  4337 I Keyboard.Facilitator.DecoderInitializer: run()
,09-06 19:03:59.132  1892  4337 I Decoder : createOrResetDecoder
,09-06 19:03:59.149  4326  4326 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-06 19:03:59.162  1497  1497 I ConfigService: onCreate
,09-06 19:03:59.170   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:03:59.177   871  1690 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3844 uid 10000
,09-06 19:03:59.178  1892  1892 I Keyboard.Facilitator: onFinishInput()
09-06 19:03:59.180  1892  4337 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-06 19:03:59.223  1996  2064 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-06 19:03:59.223   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-06 19:03:59.223   871   883 E PackageManager: Failed to write settings, restoring backup
09-06 19:03:59.223   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-06 19:03:59.223   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-06 19:03:59.223   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-06 19:03:59.223   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-06 19:03:59.223   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-06 19:03:59.223   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:59.223   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:59.223   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:03:59.225  4326  4326 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-06 19:03:59.227   871   884 E DropBoxManagerService: Can't write: system_server_wtf
09-06 19:03:59.227   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 19:03:59.227   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:03:59.227   871   884 E DropBoxManagerService: 	... 13 more
,09-06 19:03:59.234  1892  4337 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-06 19:03:59.235   871  1377 I ActivityManager: Start proc 4345:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-06 19:03:59.236  1996  2064 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-06 19:03:59.236  1996  2064 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1996
09-06 19:03:59.236  1996  2064 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:59.236  1996  2064 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:03:59.239   871  4351 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:03:59.239   871  4351 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:03:59.239   871  4351 E DropBoxManagerService: 	... 5 more
,09-06 19:03:59.249  1892  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-06 19:03:59.249  1892  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-06 19:03:59.249   871  1391 I ActivityManager: Start proc 4358:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-06 19:03:59.251  1892  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-06 19:03:59.251  1892  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-06 19:03:59.253   871  1690 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:03:59.253  1892  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-06 19:03:59.253  1892  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-06 19:03:59.264  1996  2064 I Process : Sending signal. PID: 1996 SIG: 9
,09-06 19:03:59.477   871  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-06 19:03:59.521  4326  4361 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:03:59.555  1892  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-06 19:03:59.555  1892  4337 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-06 19:03:59.555  1892  4337 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-06 19:03:59.555  1892  4337 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-06 19:03:59.555  1892  4337 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-06 19:03:59.556  1892  4337 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-06 19:03:59.575  4326  4342 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:59.575  4326  4342 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penInner(SQLiteDatabase.java:806)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:03:59.575  4326  4342 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
