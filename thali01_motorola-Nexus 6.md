#### Test 845006541b10566_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 16:06:19.184  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 16:06:19.190  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 16:06:19.191  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 16:06:19.210  1504  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 16:06:19.210  1504  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 16:06:19.210  1504  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:19.210  1504  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 16:06:19.224  3712  3712 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 16:06:19.224  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 16:06:19.225  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-09 16:06:19.881  3974  3974 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 16:06:19.886  3974  3974 D AndroidRuntime: CheckJNI is OFF
09-09 16:06:19.924  3974  3974 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 16:06:19.968  3974  3974 I Radio-JNI: register_android_hardware_Radio DONE
09-09 16:06:19.988  3974  3974 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 16:06:19.995   874  2063 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 16:06:20.044  2110  2133 W SearchService: Abort, client detached.
09-09 16:06:20.048  2110  2110 I HotwordDetector: Closing mic
09-09 16:06:20.049  2110  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d9f6e20
09-09 16:06:20.050  2110  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 16:06:20.051  3974  3974 D AndroidRuntime: Shutting down VM
09-09 16:06:20.074   874  1981 I ActivityManager: Start proc 3984:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 16:06:20.106   377  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 16:06:20.108   377  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 16:06:20.116   377  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 16:06:20.118  2110  2343 I MicroRecognitionRnrImpl: Detection finished
09-09 16:06:20.119  2110  2342 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 16:06:20.177  3984  3984 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 16:06:20.214  3984  3984 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 16:06:20.222  3984  3984 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4886-4889)
09-09 16:06:20.223  3984  3984 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:06:20.246  3984  3984 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {99ad7b4}
09-09 16:06:20.247  3984  3984 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:06:20.247  3984  3984 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 16:06:20.257  3984  3984 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 16:06:20.259  3984  3984 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 16:06:20.295  3984  3984 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 16:06:20.318  3984  3984 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:06:20.318  3984  3984 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:06:20.318  3984  3984 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:06:20.318  3984  3984 I Adreno  : Build Date                       : 10/20/15
09-09 16:06:20.318  3984  3984 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:06:20.318  3984  3984 I Adreno  : Local Branch                     : M14
09-09 16:06:20.318  3984  3984 I Adreno  : Remote Branch                    : 
09-09 16:06:20.318  3984  3984 I Adreno  : Remote Branch                    : 
09-09 16:06:20.318  3984  3984 I Adreno  : Reconstruct Branch               : 
09-09 16:06:20.425   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@46e5a4c:true
09-09 16:06:20.491  3984  3984 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 16:06:20.512  3984  3984 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-09 16:06:20.586  3984  4023 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-09 16:06:20.603  3984  4009 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-09 16:06:20.630  3984  4023 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 16:06:20.720   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +669ms
09-09 16:06:20.729  1896  1896 I Keyboard.Facilitator: onFinishInput()
09-09 16:06:20.817  3984  3984 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3984
09-09 16:06:20.861   874  2044 I ActivityManager: Killing 3242:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
09-09 16:06:20.905   874  2044 I ActivityManager: Killing 3297:com.google.android.apps.maps/u0a65 (adj 15): empty #18
09-09 16:06:20.905  3984  3984 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-09 16:06:21.081  3984  4025 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1679099600
09-09 16:06:21.092  3984  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 16:06:21.092  3984  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 16:06:21.092  3984  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 16:06:21.092  3984  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 16:06:21.092  3984  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 16:06:21.092  3984  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6eaa5b added. We now have 1 listener(s)
09-09 16:06:21.096  3984  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-09 16:06:21.097  3984  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:06:21.098  3984  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:21.098  3984  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 16:06:21.101  3984  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cc6e36 added. We now have 1 listener(s)
09-09 16:06:21.102  3984  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:21.105   874  1313 D WifiService: New client listening to asynchronous messages
09-09 16:06:21.107  3984  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:06:21.107  3984  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 16:06:21.107  3984  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 16:06:21.107  3984  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 16:06:21.107  3984  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 16:06:21.111  3984  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:21.111  3984  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-09 16:06:21.120  3984  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:21.120  3984  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:06:21.120  3984  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 16:06:21.120  3984  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:06:21.121  3984  4025 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 16:06:21.123  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:21.125  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:21.336  3984  3984 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 16:06:22.663  3984  4036 W jxcore-log: Initializing JXcore engine
,09-09 16:06:22.663  3984  4036 W jxcore-log: JXcore engine is ready
,09-09 16:06:22.696  4036  4036 W Thread-370: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-09 16:06:22.696  4036  4036 W Thread-370: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12658]" dev="sockfs" ino=12658 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-09 16:06:22.696  4036  4036 W Thread-370: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 16:06:22.696  4036  4036 W Thread-370: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26283]" dev="sockfs" ino=26283 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-09 16:06:22.713  3984  4036 W jxcore-log: Starting JXcore engine
,09-09 16:06:22.791  3984  4036 W jxcore-log: Platform android
09-09 16:06:22.791  3984  4036 W jxcore-log: 
,09-09 16:06:22.791  3984  4036 W jxcore-log: Process ARCH arm
09-09 16:06:22.791  3984  4036 W jxcore-log: 
,09-09 16:06:23.031  3984  4036 I jxcore-log: JXcore Cordova bridge is ready!
09-09 16:06:23.031  3984  4036 I jxcore-log: 
,09-09 16:06:23.031  3984  4036 W jxcore-log: JXcore engine is started
,09-09 16:06:23.048  3984  4025 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 16:06:23.055  3984  3984 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 16:06:24.222  1504  1922 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:06:24.222  1504  1922 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:06:24.222  1504  1922 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:06:24.222  1504  1922 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:24.244  3753  4039 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:06:24.244  3753  4039 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:06:24.244  3753  4039 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	... 12 more
09-09 16:06:24.244  3753  4039 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at fal.a(PG:38)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:06:24.244  3753  4039 E HttpOperation: 	... 14 more
,09-09 16:06:24.291  1504  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:06:24.291  1504  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:06:24.291  1504  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:24.291  1504  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:24.307  3753  4039 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:06:24.307  3753  4039 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at hec.a(PG:42)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at hee.a(PG:102)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at czr.a(PG:65)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at kka.a(PG:108)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:06:24.307  3753  4039 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	... 15 more
09-09 16:06:24.307  3753  4039 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at fal.a(PG:38)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:06:24.307  3753  4039 E HttpOperation: 	... 17 more
,09-09 16:06:24.307  3753  4039 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:06:24.307  3753  4039 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	... 15 more
09-09 16:06:24.307  3753  4039 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:06:24.307  3753  4039 E ExperimentLoader: 	... 17 more
,09-09 16:06:24.380   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128683, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:06:36.701  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 16:06:36.701  3984  4036 I jxcore-log: 
,09-09 16:06:36.704  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 16:06:36.704  3984  4036 I jxcore-log: 
,09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:36.717  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:36.721  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:36.723  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 16:06:36.723  3984  4036 I jxcore-log: 
,09-09 16:06:36.725  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 16:06:36.725  3984  4036 I jxcore-log: 
,09-09 16:06:37.078  3984  4036 D ExecuteNativeTests: Running unit tests
,09-09 16:06:37.161  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:06:37.161  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 added. We now have 2 listener(s)
,09-09 16:06:37.163  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:06:37.163  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:06:37.163  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:06:37.163  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:37.163  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 added. We now have 2 listener(s)
,09-09 16:06:37.163  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:37.163  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:06:37.167  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:37.177  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:37.187  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:37.187  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:06:37.191  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:37.192  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 16:06:37.192  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 16:06:37.192  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 16:06:37.193  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.193  3984  4036 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 16:06:37.194  3984  4036 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 16:06:37.194  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 16:06:37.194  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 16:06:37.194  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 16:06:37.194  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.194  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.195  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.195  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:37.195  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.195  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:06:37.195  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:37.195  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 removed from the list
,09-09 16:06:37.195  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.195  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 removed from the list
09-09 16:06:37.195  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 16:06:37.195  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.196  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.196  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.197  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:06:37.197  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.197  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.197  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.198  3984  4036 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 16:06:37.199  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.199  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.199  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.200  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:37.200  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.200  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.200  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.200  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.200  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.200  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:06:37.200  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.200  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.201  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.201  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.202  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,09-09 16:06:37.202  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.202  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 16:06:37.202  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.207  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-09 16:06:37.207  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 16:06:37.207  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 16:06:37.208  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 16:06:37.209  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 16:06:37.210  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.210  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.210  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.210  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:37.210  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.210  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.210  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.210  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.210  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.210  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.210  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.211  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.211  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.211  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.212  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.212  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.212  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.212  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.212  3984  4036 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 16:06:37.214  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:37.217  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:06:37.219  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.219  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:06:37.221  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.223  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.223  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:06:37.223  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:06:37.223  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:06:37.223  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.223  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:37.227  3984  4036 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.227  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:37.231  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:37.232  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:06:37.233  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:06:37.234  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 16:06:37.236  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 16:06:37.236  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:06:37.236  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 16:06:37.237  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:06:37.237  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.241  2688  2699 D BtGatt.GattService: registerClient() - UUID=7cf03833-d3bd-4e54-af69-771890b23a44
,09-09 16:06:37.241  2688  2711 D BtGatt.GattService: onClientRegistered() - UUID=7cf03833-d3bd-4e54-af69-771890b23a44, clientIf=5
,09-09 16:06:37.242  3984  3995 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:06:37.242  2688  2838 D BtGatt.GattService: start scan with filters
,09-09 16:06:37.245  2688  2715 D BtGatt.ScanManager: handling starting scan
,09-09 16:06:37.246  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:06:37.246  2688  2715 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
09-09 16:06:37.246  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 16:06:37.246  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:06:37.246  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:06:37.248  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:06:37.248  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:06:37.249  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:06:37.249  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:06:37.253  2688  2711 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 16:06:37.253  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.253  3984  4036 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 16:06:37.253  2688  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:06:37.255  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.255  3984  4036 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 16:06:37.255  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.255  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:06:37.255  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.255  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:37.255  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:06:37.255  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 16:06:37.255  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:06:37.255  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:06:37.256  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:06:37.256  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:06:37.257  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.257  2688  2701 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:06:37.257  2688  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:06:37.258  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.258  2688  2715 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:06:37.258  2688  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 16:06:37.258  2688  2699 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:06:37.258  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.259  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:06:37.259  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 16:06:37.259  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:06:37.259  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 16:06:37.260  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:37.260  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.260  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:06:37.260  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:37.260  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:06:37.261  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.261  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.261  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:37.263  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:37.263  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.263  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:37.263  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.263  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.263  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.263  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:06:37.263  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:37.263  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.263  3984  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:37.264  3984  4036 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 16:06:37.265  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.266  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:06:37.266  2688  2711 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:06:37.266  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:37.266  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:37.266  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:06:37.267  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:37.267  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:37.269  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:37.270  2688  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:06:37.270  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.270  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.270  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.270  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.270  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:37.270  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:06:37.271  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:06:37.271  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 16:06:37.272  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.272  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:37.272  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:37.274  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 16:06:37.274  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 16:06:37.274  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.274  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:37.276  2688  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:06:37.276  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.276  2688  2715 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:06:37.277  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:37.278  3984  4036 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:37.279  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.282  2688  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:06:37.282  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.282  2688  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:06:37.282  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:06:37.282  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 16:06:37.282  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:06:37.283  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.284  2688  2838 D BtGatt.GattService: registerClient() - UUID=2d5c69c6-1d44-4f37-8e29-0da2c31a7c95
09-09 16:06:37.286  2688  2711 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:06:37.286  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.287  2688  2711 D BtGatt.GattService: onClientRegistered() - UUID=2d5c69c6-1d44-4f37-8e29-0da2c31a7c95, clientIf=5
09-09 16:06:37.288  3984  3995 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:06:37.288  2688  2701 D BtGatt.GattService: start scan with filters
,09-09 16:06:37.291  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:06:37.291  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:06:37.291  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:06:37.291  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:06:37.291  2688  2715 D BtGatt.ScanManager: handling starting scan
,09-09 16:06:37.292  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:06:37.293  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:06:37.293  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 16:06:37.294  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:06:37.295  3984  4036 I io.jxcore.node.ConnectionHelper: start: OK
09-09 16:06:37.296  2688  2711 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:06:37.296  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.296  2688  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:06:37.297  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.297  3984  4036 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:06:37.297  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.298  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:06:37.298  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.298  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:37.298  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:06:37.298  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:06:37.298  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:06:37.298  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:06:37.298  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 16:06:37.298  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:06:37.298  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.299  2688  2699 D BtGatt.GattService: stopScan() - queue size =1
,09-09 16:06:37.300  2688  2838 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:06:37.300  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.300  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 16:06:37.300  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:06:37.300  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:06:37.300  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:06:37.300  2688  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:06:37.300  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:37.300  2688  2715 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:06:37.300  2688  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:06:37.301  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:37.301  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.301  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:06:37.301  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:37.301  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:37.302  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.302  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.302  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:37.302  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.302  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.302  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:37.302  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.302  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.303  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.303  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.304  3984  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:37.306  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:37.306  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:37.306  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-09 16:06:37.303  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.306  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:37.307  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:37.307  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.308  2688  2711 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:06:37.308  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:37.308  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.309  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.309  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:37.310  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:37.311  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:37.311  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.312  2688  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 16:06:37.312  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:37.312  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.313  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.313  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.314  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.314  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.314  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.314  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.314  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.314  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.314  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.314  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.315  3984  4036 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 16:06:37.316  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.318  2688  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:06:37.318  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.318  2688  2715 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:37.320  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:37.322  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:37.322  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:06:37.322  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:06:37.322  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:06:37.322  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 16:06:37.322  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.323  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:37.323  2688  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 16:06:37.323  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.323  2688  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:06:37.324  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:37.325  3984  4036 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:37.326  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:37.328  2688  2711 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:06:37.328  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:37.329  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:06:37.329  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:06:37.329  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:06:37.329  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.331  2688  2838 D BtGatt.GattService: registerClient() - UUID=9fa1b89e-2f9c-48ab-879d-6e375ae60687
,09-09 16:06:37.332  2688  2711 D BtGatt.GattService: onClientRegistered() - UUID=9fa1b89e-2f9c-48ab-879d-6e375ae60687, clientIf=5
09-09 16:06:37.332  3984  3996 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:06:37.332  2688  2701 D BtGatt.GattService: start scan with filters
,09-09 16:06:37.336  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:06:37.336  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:06:37.336  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 16:06:37.336  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:06:37.336  2688  2715 D BtGatt.ScanManager: handling starting scan
,09-09 16:06:37.338  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:06:37.338  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:06:37.338  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:06:37.339  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:06:37.341  2688  2711 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 16:06:37.341  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.341  2688  2715 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:06:37.341  3984  4036 I io.jxcore.node.ConnectionHelper: start: OK
09-09 16:06:37.341  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.341  3984  4036 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:06:37.341  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.341  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:06:37.341  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.341  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:37.341  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:06:37.341  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:06:37.341  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 16:06:37.341  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:06:37.341  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:06:37.341  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:06:37.342  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.342  2688  2699 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:06:37.343  2688  2838 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:06:37.343  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.343  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 16:06:37.343  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:06:37.343  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:06:37.343  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:06:37.344  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:37.344  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:06:37.344  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:06:37.344  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:37.345  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:37.345  2688  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:06:37.345  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:37.346  2688  2715 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:06:37.346  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.346  2688  2715 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 16:06:37.346  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.346  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:37.346  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.346  3984  4036 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:06:37.346  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.346  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.346  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.346  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.346  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 16:06:37.346  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.346  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.346  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.346  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.346  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:06:37.348  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.348  3984  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:37.351  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:06:37.352  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:37.352  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:06:37.352  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:37.352  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.354  2688  2711 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:06:37.354  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:37.355  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.355  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.355  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:37.357  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.357  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:37.357  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.358  2688  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:06:37.359  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.359  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:37.359  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.359  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.360  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.360  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.360  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.360  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.360  3984  4036 D BluetoothLeScanner: could not find callback wrapper
,09-09 16:06:37.360  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.360  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.360  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.361  3984  4036 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 16:06:37.361  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.361  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.361  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.362  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.362  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.362  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.362  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.362  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.362  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.362  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.362  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.362  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.362  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.362  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.363  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.363  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.363  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.363  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.363  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.363  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.363  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.363  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.364  2688  2711 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:06:37.364  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.364  2688  2715 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:06:37.364  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 16:06:37.364  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.364  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.364  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:06:37.365  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.365  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.365  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.365  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.365  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.365  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.365  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.365  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.365  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.365  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 16:06:37.365  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.366  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:06:37.366  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.366  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.367  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.367  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.367  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:06:37.367  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.367  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.367  3984  4036 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 16:06:37.367  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.367  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.367  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.368  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 16:06:37.368  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.368  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.368  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.368  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.368  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.368  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.368  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.368  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 16:06:37.368  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.368  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.369  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.369  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:06:37.369  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:37.369  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.369  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.369  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:06:37.369  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.369  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.369  2688  2711 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 16:06:37.369  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:37.370  2688  2715 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:06:37.370  3984  4036 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.370  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.370  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.370  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.370  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:37.370  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.370  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.370  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.370  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.370  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.370  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:06:37.371  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.371  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.371  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.371  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.371  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.371  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.371  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:37.372  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.372  3984  4036 D BluetoothLeScanner: could not find callback wrapper
,09-09 16:06:37.372  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.372  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.372  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.372  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 16:06:37.374  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 16:06:37.374  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 16:06:37.374  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 16:06:37.374  2688  2711 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:06:37.374  2688  2711 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-09 16:06:37.374  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 16:06:37.374  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 16:06:37.376  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.376  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.376  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.377  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.377  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.377  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.377  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.377  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.377  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.377  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.377  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.377  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.377  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.377  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.378  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.378  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.378  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:37.378  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.378  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.378  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.378  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.378  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.380  3984  4036 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:06:37.380  3984  4036 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 16:06:37.380  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 16:06:37.385  3984  4036 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:06:37.385  3984  4036 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-09 16:06:37.385  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 16:06:37.385  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 16:06:37.385  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 16:06:37.385  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 16:06:37.385  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 16:06:37.385  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 16:06:37.386  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 16:06:37.387  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 16:06:37.387  3984  4036 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 16:06:37.388  3984  4036 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:06:37.388  3984  4036 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 16:06:37.388  3984  4036 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:06:37.388  3984  4036 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:06:37.388  3984  4036 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-09 16:06:37.388  3984  4036 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:06:37.388  3984  4036 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:06:37.388  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-09 16:06:37.391  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 16:06:37.392  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 16:06:37.392  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 16:06:37.392  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-09 16:06:37.392  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-09 16:06:37.392  3984  4036 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 16:06:37.392  3984  4036 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:06:37.393  3984  4036 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 16:06:37.393  3984  4049 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 434)
09-09 16:06:37.393  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.393  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:37.393  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.393  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.394  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.394  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.394  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 16:06:37.394  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
,09-09 16:06:37.394  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.394  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.394  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.395  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.395  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.395  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.395  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.395  3984  4049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:06:37.395  3984  4050 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 434
09-09 16:06:37.395  3984  4050 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 434)
09-09 16:06:37.395  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.395  3984  4050 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 434)
09-09 16:06:37.395  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.396  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.396  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.396  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.396  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.396  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.396  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.397  3984  4036 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 16:06:37.397  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 16:06:37.397  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.397  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.397  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 16:06:37.397  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.397  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.397  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list,
09-09 16:06:37.398  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.398  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.398  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.398  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.398  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.398  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.398  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.399  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:06:37.399  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.399  3984  4049 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 434)
09-09 16:06:37.399  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:37.399  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.399  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.399  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.399  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.399  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.400  3984  4036 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-09 16:06:37.400  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.400  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.400  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.400  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.401  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.401  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.401  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
,09-09 16:06:37.401  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.401  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.401  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.401  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.401  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.401  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.401  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.402  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.402  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.402  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.402  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.402  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.402  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.402  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.403  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.403  3984  4036 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 16:06:37.403  3984  4036 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 16:06:37.403  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:06:37.403  3984  4036 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 16:06:37.403  3984  4036 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-09 16:06:37.403  3984  4036 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 16:06:37.403  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:06:37.403  3984  4036 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 16:06:37.404  3984  4036 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 16:06:37.404  3984  4036 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 16:06:37.404  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:06:37.404  3984  4036 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-09 16:06:37.404  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.404  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.404  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.404  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.404  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.404  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.404  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
,09-09 16:06:37.404  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.404  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.404  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.404  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.404  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.404  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.404  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.406  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:06:37.406  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.406  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.406  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.406  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.406  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.407  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.407  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.407  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.407  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.407  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.407  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.407  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.407  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.407  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.407  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.407  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.407  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.408  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.408  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.408  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.408  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.408  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.408  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.408  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.408  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.408  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.408  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.408  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.408  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.408  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.408  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.408  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.408  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.408  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.408  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.409  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.409  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.409  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.409  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:37.410  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.410  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.410  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.410  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.410  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.411  3984  4036 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 16:06:37.411  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.412  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 16:06:37.412  3984  4036 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 16:06:37.412  3984  4036 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 16:06:37.412  3984  3984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 16:06:37.413  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 16:06:37.413  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 16:06:37.413  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.413  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 16:06:37.413  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 16:06:37.413  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 16:06:37.413  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.413  3984  4036 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 16:06:37.413  3984  3984 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 16:06:37.413  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.413  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.413  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:06:37.413  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:06:37.413  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:06:37.414  3984  4051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:06:37.414  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:06:37.414  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.414  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.414  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.414  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.414  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:06:37.414  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.415  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.415  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:37.415  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.415  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.415  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:37.416  3984  4051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 16:06:37.416  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.416  3984  4051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 16:06:37.416  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.416  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.416  3984  4051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 16:06:37.416  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.416  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.416  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.417  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:37.416  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:37.417  3984  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:06:37.419  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.419  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.419  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.419  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.419  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.419  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:06:37.420  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:06:37.421  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:37.421  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:06:37.421  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:37.421  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.423  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:37.423  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:37.423  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:37.424  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:37.425  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:37.425  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.426  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 16:06:37.426  3984  3984 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 16:06:37.427  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.427  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.428  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.428  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.428  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:37.429  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.429  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.429  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:06:37.429  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.429  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.430  3984  4036 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-09 16:06:37.431  3984  4036 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 16:06:37.431  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 16:06:37.431  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 16:06:37.431  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.431  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.431  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:06:37.431  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.431  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.431  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.432  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.432  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.432  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.432  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.432  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.432  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.432  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.432  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.433  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.433  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:06:37.433  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.434  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.434  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.434  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.434  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.434  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.438  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:06:37.438  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.438  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:37.438  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:37.438  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.438  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.438  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
,09-09 16:06:37.438  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.438  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.438  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:06:37.438  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.438  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.438  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:37.438  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.439  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:37.439  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:06:37.439  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.439  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:37.440  3984  4036 D BluetoothLeScanner: could not find callback wrapper
,09-09 16:06:37.440  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.440  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.440  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.440  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:37.440  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:37.440  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:06:37.440  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:37.440  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.440  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.441  3984  4036 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a850122 not in the list
09-09 16:06:37.441  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:37.441  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
,09-09 16:06:37.441  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:37.441  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.441  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:37.441  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:37.441  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:37.441  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:06:37.441  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:37.442  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:37.442  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:37.442  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:37.442  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:37.442  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:37.442  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34607b3 not in the list
09-09 16:06:37.443  3984  4036 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-09 16:06:37.443  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:06:37.443  3984  4036 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 16:06:37.443  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-09 16:06:37.443  3984  4036 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 16:06:37.443  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:06:37.444  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 16:06:37.444  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 16:06:37.445  3984  4036 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-09 16:06:37.445  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 16:06:37.445  3984  4036 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 16:06:37.445  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 16:06:37.445  3984  4036 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 16:06:37.445  3984  4036 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 16:06:37.445  3984  4036 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed,
09-09 16:06:37.446  3984  4036 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 16:06:37.446  3984  4036 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 16:06:37.446  3984  4036 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 16:06:37.446  3984  4036 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 16:06:37.446  3984  4036 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 16:06:37.447  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:37.447  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f888391 added. We now have 2 listener(s)
09-09 16:06:37.447  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:37.448  3984  4036 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 16:06:37.448   874  2072 D WifiService: setWifiEnabled: true pid=3984, uid=10000
09-09 16:06:37.448   874  2072 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 16:06:37.449  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-09 16:06:37.449  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85c62f6 added. We now have 3 listener(s)
09-09 16:06:37.449  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:06:37.453  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:37.453  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c146f7 added. We now have 4 listener(s)
09-09 16:06:37.453  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:06:37.454  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:37.454  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4a964 added. We now have 5 listener(s)
09-09 16:06:37.454  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:06:37.455   874  1384 D WifiService: setWifiEnabled: false pid=3984, uid=10000
09-09 16:06:37.455   874  1384 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:06:37.460  2688  2707 D BluetoothAdapterState: Current state: ON, message: 23
09-09 16:06:37.460  2688  2707 D BluetoothAdapterProperties: Setting state to 13
,09-09 16:06:37.460  2688  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 16:06:37.460  2688  2707 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 16:06:37.460  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:37.461  2688  2707 I BluetoothAdapterState: Entering PendingCommandState
09-09 16:06:37.461  2688  2711 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:06:37.462  2688  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 16:06:37.463  2688  2688 D BluetoothMapService: onReceive
,09-09 16:06:37.463  2688  2688 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 16:06:37.463  2688  2688 D BluetoothMapService: STATE_TURNING_OFF
,09-09 16:06:37.464  2688  2688 D BluetoothMapService: MAP Service closeService in
,09-09 16:06:37.464  2688  2688 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 16:06:37.464  2688  2688 D ObexServerSockets0: shutdown(block = true)
09-09 16:06:37.464  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 16:06:37.464  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 16:06:37.465  2688  2864 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-09 16:06:37.465  2688  2834 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 16:06:37.465  2688  2863 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 16:06:37.466  2688  2688 I BtOppRfcommListener: stopping Accept Thread
,09-09 16:06:37.466  2688  3617 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 16:06:37.466  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:37.466  2688  3617 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:37.466  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:37.467  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.467  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:37.467  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:06:37.470  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 16:06:37.470  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:37.472   874  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 16:06:37.472   874  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 16:06:37.472   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:06:37.473   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:06:37.475  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:37.476   874   887 I ActivityManager: Start proc 4054:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-09 16:06:37.478  2688  2688 D HeadsetService: Received stop request...Stopping profile...
,09-09 16:06:37.481  1355  3983 D BluetoothHeadset: Proxy object disconnected
,09-09 16:06:37.481   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 16:06:37.481   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 16:06:37.481   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:06:37.481   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 16:06:37.481   874  2115 D DhcpClient: Clearing IP address
,09-09 16:06:37.483  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:37.484  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:06:37.484  2022  2188 D BluetoothHeadset: Proxy object disconnected
09-09 16:06:37.484   373   873 D CommandListener: Setting iface cfg
09-09 16:06:37.485  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.485  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:37.485  1504  2532 V NativeCrypto: Read error: ssl=0x9a57e800: I/O error during system call, Connection timed out
09-09 16:06:37.487  1504  2532 V NativeCrypto: SSL shutdown failed: ssl=0x9a57e800: I/O error during system call, Broken pipe
09-09 16:06:37.488  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.489   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 16:06:37.489   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 16:06:37.492  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:37.492  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:06:37.494  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.494  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:37.494   874  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 16:06:37.495   874  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 16:06:37.495   404   404 E Parcel  : Reading a NULL string not supported here.
09-09 16:06:37.496   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:06:37.497  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:37.497  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:06:37.497  1355  1355 D HeadsetProfile: Bluetooth service disconnected
09-09 16:06:37.498  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.498  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:37.498  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:37.498  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:37.498  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:37.498  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:37.498   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 16:06:37.499  2688  2688 D A2dpService: Received stop request...Stopping profile...
09-09 16:06:37.499  2688  2856 D A2dpStateMachine: Exit Disconnected: -1
09-09 16:06:37.501   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 16:06:37.501  1355  1355 D BluetoothA2dp: Proxy object disconnected
09-09 16:06:37.503  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 16:06:37.503  2688  2711 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 16:06:37.503  2688  2819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:37.503  2688  2819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:37.503  2688  2819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:37.503  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 16:06:37.503  2688  2711 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 16:06:37.504  2688  2688 D HidService: Received stop request...Stopping profile...
09-09 16:06:37.504  2688  2688 D HidService: Stopping Bluetooth HidService
09-09 16:06:37.506  2688  2688 D HealthService: Received stop request...Stopping profile...
09-09 16:06:37.508  2688  2688 D PanService: Received stop request...Stopping profile...
09-09 16:06:37.506   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 16:06:37.509  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:37.509  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:37.510  2688  2688 D BluetoothMapService: Received stop request...Stopping profile...
09-09 16:06:37.510  2688  2688 D BluetoothMapService: stop()
09-09 16:06:37.510  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.510  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:37.511  2688  2688 D BluetoothMapAppObserver: deinitObservers()
09-09 16:06:37.511  2688  2688 D BluetoothMapAppObserver: removeReceiver()
09-09 16:06:37.512  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:37.512  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:37.512   874  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 16:06:37.513  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:37.513  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:37.513  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:37.513  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:37.513  1355  1355 D BluetoothInputDevice: Proxy object disconnected
09-09 16:06:37.513  1355  1355 D HidProfile: Bluetooth service disconnected
09-09 16:06:37.513  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:06:37.513  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:37.513  1355  1355 D PanProfile: Bluetooth service disconnected
09-09 16:06:37.513  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:37.514  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 16:06:37.514  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:37.514  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:37.515  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 16:06:37.515  2688  2711 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:06:37.515  2688  2819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:37.515  2688  2711 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:06:37.515  2688  2819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:37.515  2688  2711 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 16:06:37.515  2688  2819 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:06:37.515  2688  2819 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:06:37.515  2688  2819 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:06:37.515  2688  2819 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:06:37.515  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 16:06:37.516  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:37.516  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:37.516  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:37.516  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:37.516  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 16:06:37.516  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 16:06:37.517  2688  2688 D BluetoothMapService: MAP Service closeService in
09-09 16:06:37.517  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:37.517  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:37.517  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:37.518  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:37.518  2688  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 16:06:37.518  2688  2707 D BluetoothAdapterProperties: Setting state to 15
09-09 16:06:37.518  2688  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 16:06:37.518  1355  1367 D BluetoothPan: onBluetoothStateChange on: false
09-09 16:06:37.519  1355  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 16:06:37.519  2688  2707 I BluetoothAdapterState: Entering BleOnState
09-09 16:06:37.520  1355  3983 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:37.520  1355  2145 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 16:06:37.520   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:06:37.520   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:37.521  1355  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:06:37.521  2022  2232 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:37.521   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:37.521   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:37.522  1355  1377 D BluetoothMap: onBluetoothStateChange: up=false
09-09 16:06:37.522  2688  2707 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 16:06:37.522  2688  2707 D BluetoothAdapterProperties: Setting state to 16
09-09 16:06:37.522  2688  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 16:06:37.523  2688  2707 D BluetoothAdapterProperties: onBleDisable
09-09 16:06:37.523  2688  2707 I BluetoothAdapterState: Entering PendingCommandState
09-09 16:06:37.523  2688  2708 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 16:06:37.524  2688  2711 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:06:37.525  2688  2819 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 16:06:37.525  2688  2819 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:37.524  2688  2688 D BluetoothMapService: cleanup()
09-09 16:06:37.525  2688  2688 D BluetoothMapService: MAP Service closeService in
09-09 16:06:37.528  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.530  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.532  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.533  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.539   874  2137 D DhcpClient: Receive thread stopped
09-09 16:06:37.540  1866  2287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 16:06:37.548   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 16:06:37.559  4054  4054 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-09 16:06:37.566   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 16:06:37.567   874  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 16:06:37.567   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 16:06:37.569   874   891 D Tethering: MasterInitialState.processMessage what=3
09-09 16:06:37.571  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.572  3618  3618 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@46872f8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-09 16:06:37.572  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:37.582  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 16:06:37.587  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 16:06:37.592   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9083822:true
,09-09 16:06:37.599   874  1681 I ActivityManager: Start proc 4072:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-09 16:06:37.607  4054  4054 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 16:06:37.609  4054  4054 D BluetoothMap: Create BluetoothMap proxy object
09-09 16:06:37.614  4054  4054 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-09 16:06:37.626  4054  4054 D DockEventReceiver: finishStartingService: stopping service
09-09 16:06:37.630   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-09 16:06:37.633   874  1384 I ActivityManager: Killing 3417:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 16:06:37.638  4072  4072 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 16:06:37.727  2688  2711 I bt_hci  : shut_down
,09-09 16:06:37.768  2688  2716 I bt_vendor: low_power_mode_cb
,09-09 16:06:37.774  2688  2716 D bt_hwcfg: hw_epilog_process
,09-09 16:06:37.780  2688  2716 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 16:06:37.780  2688  2716 I bt_vendor: epilog_cb
,09-09 16:06:37.780  2688  2716 I bt_hci  : epilog_finished_callback
,09-09 16:06:37.784  2688  2711 I bt_hci_h4: hal_close
,09-09 16:06:37.785  2688  2711 I bt_userial_vendor: device fd = 51 close
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:06:37.803  4072  4072 D StrictMode: 	,at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.803  4072  4072 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:06:37.803  4072  4072 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:06:37.840   874  2063 I ActivityManager: Start proc 4104:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 16:06:37.841   874  2063 I ActivityManager: Killing 3618:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 16:06:37.893  4104  4104 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 16:06:37.902  2688  2708 D bt_stack_manager: event_shut_down_stack finished.
,09-09 16:06:37.903  2688  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 16:06:37.905  2688  2707 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 16:06:37.905  2688  2688 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:06:37.906  2688  2688 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 16:06:37.906  2688  2688 D BtGatt.GattService: stop()
09-09 16:06:37.906  2688  2688 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 16:06:37.908  2688  2688 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:06:37.909  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:37.909  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:37.909  2688  2688 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 16:06:37.909  2688  2707 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 16:06:37.910  2688  2707 D BluetoothAdapterProperties: Setting state to 10
,09-09 16:06:37.910  2688  2707 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 16:06:37.911  2688  2707 I BluetoothAdapterState: Entering OffState
09-09 16:06:37.911   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 16:06:37.920  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 16:06:37.920  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 16:06:37.920  2688  2688 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 16:06:37.921  2688  2708 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 16:06:37.923  2688  2708 D bt_stack_manager: event_clean_up_stack finished.
,09-09 16:06:37.927  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:06:37.928  2688  2688 I art     : System.exit called, status: 0
09-09 16:06:37.928  2688  2688 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 16:06:37.943  4104  4104 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 16:06:37.976  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:06:37.980   874   884 I ActivityManager: Process com.android.bluetooth (pid 2688) has died
,09-09 16:06:37.995   874   885 I ActivityManager: Start proc 4130:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-09 16:06:37.997  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:06:37.998   874  2072 I ActivityManager: Killing 3364:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-09 16:06:38.102  4130  4130 D AdapterServiceConfig: Adding HeadsetService
,09-09 16:06:38.102  4130  4130 D AdapterServiceConfig: Adding A2dpService
09-09 16:06:38.102  4130  4130 D AdapterServiceConfig: Adding HidService
09-09 16:06:38.102  4130  4130 D AdapterServiceConfig: Adding HealthService
,09-09 16:06:38.102  4130  4130 D AdapterServiceConfig: Adding PanService
,09-09 16:06:38.102  4130  4130 D AdapterServiceConfig: Adding GattService
,09-09 16:06:38.102  4130  4130 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 16:06:38.106  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:06:38.128  4072  4091 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 16:06:38.131  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:06:38.135  1714  1714 D SystemUpdateService: onCreate
,09-09 16:06:38.138  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:06:38.149  1714  4144 I SystemUpdateService: active receiver: enabled
,09-09 16:06:38.151  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 16:06:38.154   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f9b8ef:true
,09-09 16:06:38.155  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:06:38.156  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:06:38.158  1714  2511 I iu.UploadsManager: num queued entries: 0
,09-09 16:06:38.158  1714  4144 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-09 16:06:38.158  1714  2511 I iu.UploadsManager: num updated entries: 0
09-09 16:06:38.159  1714  2511 I iu.SyncManager: NEXT; no task
,09-09 16:06:38.160  1714  4144 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 16:06:38.160  1714  4144 I SystemUpdateService: now status is 0 (complete)
09-09 16:06:38.160  1714  4144 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:06:38.161  1714  4144 I SystemUpdateService: file has been verified
09-09 16:06:38.161  1714  4144 I SystemUpdateService: OTA package size = 12249756
,09-09 16:06:38.166  1714  4144 I SystemUpdateService: showing system update notification
,09-09 16:06:38.174   874  1682 I ActivityManager: Start proc 4146:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 16:06:38.191  1714  1714 D SystemUpdateService: onDestroy
,09-09 16:06:38.204  4146  4146 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 16:06:38.207  4146  4146 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:06:38.215  4146  4146 D SprintDMHelper: simOperator: 
,09-09 16:06:38.215  4146  4146 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:06:38.227   874  1682 I ActivityManager: Start proc 4158:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 16:06:38.228   874  1682 I ActivityManager: Killing 3002:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 16:06:38.325   874  1987 I ActivityManager: Start proc 4173:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 16:06:38.328  2906  4172 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 16:06:38.334   874  1981 I ActivityManager: Killing 2764:android.process.acore/u0a5 (adj 15): empty #17
,09-09 16:06:38.378  4173  4173 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 16:06:38.425  4173  4173 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 16:06:38.425  4173  4173 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 16:06:38.425  4173  4173 I GAv4    :   adb logcat -s GAv4
,09-09 16:06:38.435  4173  4173 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:06:38.440  4173  4173 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:06:38.455  4173  4191 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:06:38.559  4173  4173 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 16:06:38.592  4173  4173 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 16:06:38.602  4173  4173 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3267-3269)
09-09 16:06:38.602  4173  4173 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 16:06:38.611  4173  4173 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e5a8a28}
,09-09 16:06:38.612  4173  4173 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:06:38.612  4173  4173 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 16:06:38.618  4173  4173 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 16:06:38.619  4173  4173 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 16:06:38.636  4173  4173 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 16:06:38.648  4173  4173 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:06:38.648  4173  4173 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:06:38.648  4173  4173 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:06:38.648  4173  4173 I Adreno  : Build Date                       : 10/20/15
09-09 16:06:38.648  4173  4173 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:06:38.648  4173  4173 I Adreno  : Local Branch                     : M14
09-09 16:06:38.648  4173  4173 I Adreno  : Remote Branch                    : 
09-09 16:06:38.648  4173  4173 I Adreno  : Remote Branch                    : 
09-09 16:06:38.648  4173  4173 I Adreno  : Reconstruct Branch               : 
,09-09 16:06:38.709  4173  4173 I NSApplication: Starting up...
,09-09 16:06:38.715  4173  4220 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 16:06:38.738   874  2072 I ActivityManager: Start proc 4225:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-09 16:06:38.739   874  2072 I ActivityManager: Killing 3866:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 16:06:38.808  4225  4225 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 16:06:38.977   874  2063 I ActivityManager: Killing 3832:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-09 16:06:40.470   874  1682 D WifiService: setWifiEnabled: true pid=3984, uid=10000
09-09 16:06:40.470   874  1682 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:06:40.483   874  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-09 16:06:40.491  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:40.491  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:40.491  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:40.492  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:40.494  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:40.495  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:40.495  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:40.495  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:06:40.528   874  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-09 16:06:40.529   874  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 16:06:40.530   874  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 16:06:40.531   874  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 16:06:40.531   874  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 16:06:40.531   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 16:06:40.532   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 16:06:40.546   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 16:06:40.546   874  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.38 rxSuccessRate=23.00 delta 1000 -> 994
,09-09 16:06:40.547   373   873 D CommandListener: Setting iface cfg
,09-09 16:06:40.548   874  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 16:06:40.548   874  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 16:06:40.554   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 16:06:40.555   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:06:40.561   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 16:06:40.608   874  1311 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 16:06:40.611   874  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 16:06:40.651   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 16:06:40.655  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 16:06:41.079  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 16:06:41.123  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 16:06:41.125  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 16:06:41.133   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:06:41.151   874  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:06:41.152   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 16:06:41.152   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 16:06:41.181   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:06:41.193   373   873 D CommandListener: Setting iface cfg
,09-09 16:06:41.196   874  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 16:06:41.200   874  4248 D DhcpClient: Receive thread started
,09-09 16:06:41.208   874  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-09 16:06:41.210   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 16:06:41.294   874  1312 E native  : do suspend false
,09-09 16:06:41.313   874  2115 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 16:06:41.328   874  4248 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172677, domain null
,09-09 16:06:41.329   874  2115 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172677 seconds
,09-09 16:06:41.332   874  2115 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 16:06:41.345   874  4248 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 16:06:41.346   874  2115 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 16:06:41.351   373   873 D CommandListener: Setting iface cfg
,09-09 16:06:41.361   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 16:06:41.364   874  2115 D DhcpClient: Scheduling renewal in 86399s,
,09-09 16:06:41.380   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 16:06:41.383   874  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 16:06:41.384   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 16:06:41.385   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 16:06:41.387   874  1314 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 16:06:41.403   874  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 16:06:41.446   874  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 16:06:41.446   874  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-09 16:06:41.447   874  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 16:06:41.449   874  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 16:06:41.450   874  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 16:06:41.460   874  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 16:06:41.466   874  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 16:06:41.467   874  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 16:06:41.467   874  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 16:06:41.467   874  1314 D ConnectivityService:    accepting network in place of null
09-09 16:06:41.467   874  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 16:06:41.468   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:06:41.468   874  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:06:41.480   874  4247 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 16:06:41.500   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:06:41.549   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:06:41.552   874  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 16:06:41.558   874  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 16:06:41.559   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:06:41.565   874  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 16:06:41.568   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:06:41.577  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:41.577  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:06:41.577  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:41.577  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:41.584  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:41.584  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:06:41.584  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:41.584  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:41.592  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 16:06:41.595  1714  1714 D SystemUpdateService: onCreate
,09-09 16:06:41.598  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:06:41.600  1714  4259 I SystemUpdateService: active receiver: enabled
,09-09 16:06:41.602  1714  4259 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:06:41.605  1714  4259 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true,
09-09 16:06:41.605  1714  4259 I SystemUpdateService: now status is 0 (complete)
09-09 16:06:41.605  1714  4259 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:06:41.605  1714  4259 I SystemUpdateService: file has been verified
,09-09 16:06:41.605  1714  4259 I SystemUpdateService: OTA package size = 12249756
,09-09 16:06:41.611  1714  4259 I SystemUpdateService: showing system update notification
,09-09 16:06:41.618  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 16:06:41.620  1714  1714 D SystemUpdateService: onDestroy
09-09 16:06:41.620  1714  2511 I iu.UploadsManager: num queued entries: 0
,09-09 16:06:41.621  1714  2511 I iu.UploadsManager: num updated entries: 0
09-09 16:06:41.622  1714  2511 I iu.SyncManager: NEXT; no task
,09-09 16:06:41.623   874  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 14:06:41 GMT], X-Android-Received-Millis=[1473430001622], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473430001600]}
09-09 16:06:41.624  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 16:06:41.625  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:06:41.627  1714  4263 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 16:06:41.627  1714  4263 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 16:06:41.628  4146  4146 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-09 16:06:41.629   874  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 16:06:41.629   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 16:06:41.629   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 16:06:41.629  1714  4263 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 16:06:41.630   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 16:06:41.633  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:41.634  4146  4146 D SprintDMHelper: simOperator: 
09-09 16:06:41.634  4146  4146 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:06:41.635  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:41.669  1504  1922 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 16:06:41.669  1504  1922 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 16:06:41.669  1504  1922 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:41.669  1504  1922 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:41.683  1714  4263 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-09 16:06:41.747  2906  4266 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 16:06:41.790   874   886 I ActivityManager: Start proc 4273:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-09 16:06:41.805  4273  4273 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-09 16:06:41.842  3793  4285 V KeepSync: Connecting to GoogleApiClient
,09-09 16:06:41.844   874  1987 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:06:41.914  4273  4273 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-09 16:06:41.943  4273  4273 I BooksApp: Created application version: 3.6.9 (30609)
,09-09 16:06:41.953  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:06:41.954  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:06:41.954  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:41.954  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:41.965  1714  4288 V BaseAuthAsyncOperation: access token request failed
,09-09 16:06:41.966  3793  4285 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:06:42.005  4273  4292 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:06:42.092  1504  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 16:06:42.092  1504  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 16:06:42.092  1504  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:42.093  1504  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:42.119  3793  4285 E KeepSync: IOException
09-09 16:06:42.119  3793  4285 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:06:42.119  3793  4285 E KeepSync: 	,at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:06:42.119  3793  4285 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:06:42.119  3793  4285 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:06:42.119  3793  4285 E KeepSync: 	... 10 more
09-09 16:06:42.119  3793  4285 W KeepSync: Sync result 2
,09-09 16:06:42.132   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 133408, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:06:42.187  4273  4298 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:06:42.274  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:06:42.274  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:06:42.274  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:42.274  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:42.291  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:42.350  1504  3190 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 16:06:42.351  1504  3190 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 16:06:42.351  1504  3190 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:42.351  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 16:06:42.352  1504  3190 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:42.352  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:06:42.352  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:42.352  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:42.388  3712  3712 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 16:06:42.389  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 16:06:42.389  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
09-09 16:06:42.390  4273  4298 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:06:42.393  4273  4292 E BooksSync: Soft error
09-09 16:06:42.393  4273  4292 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:06:42.393  4273  4292 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:06:42.394  4273  4292 E BooksSync: Sync error
09-09 16:06:42.394  4273  4292 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:06:42.394  4273  4292 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:06:42.394  4273  4292 I BooksSync: Finished books sync
,09-09 16:06:42.404   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129932, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:06:42.411   874  2031 I ActivityManager: Killing 3883:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 16:06:42.558   874  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 16:06:43.170   874  2070 I ActivityManager: Killing 3646:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 16:06:43.477   874  2031 D WifiService: setWifiEnabled: false pid=3984, uid=10000
,09-09 16:06:43.477   874  2031 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:06:43.495  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 16:06:43.497   874  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 16:06:43.497   874  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 16:06:43.497   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:06:43.498   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:06:43.516   874  2115 D DhcpClient: Clearing IP address
,09-09 16:06:43.517   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:06:43.520   373   873 D CommandListener: Setting iface cfg
,09-09 16:06:43.525  1504  4271 V NativeCrypto: Read error: ssl=0x9a57e000: I/O error during system call, Connection timed out
,09-09 16:06:43.530  1504  4271 V NativeCrypto: SSL shutdown failed: ssl=0x9a57e000: I/O error during system call, Broken pipe
,09-09 16:06:43.537   874  2072 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-09 16:06:43.537   874  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-09 16:06:43.539   874  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-09 16:06:43.541   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-09 16:06:43.542   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-09 16:06:43.542   874  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 16:06:43.544   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:06:43.544   874  4248 D DhcpClient: Receive thread stopped
09-09 16:06:43.547   404   404 E Parcel  : Reading a NULL string not supported here.
,09-09 16:06:43.550   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-09 16:06:43.555   874  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 16:06:43.559   874  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-09 16:06:43.568   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:06:43.571  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:43.571  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:06:43.571  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:43.571  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:43.572  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:43.572  1866  2287 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:43.572  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:43.572  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:43.572  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:06:43.575   874  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 16:06:43.591   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:06:43.616   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:06:43.617   874  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 16:06:43.617   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 16:06:43.619   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:06:43.622  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:43.623  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:43.636  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:06:43.641  1714  1714 D SystemUpdateService: onCreate
,09-09 16:06:43.645  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:06:43.655  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 16:06:43.661  1714  2511 I iu.UploadsManager: num queued entries: 0
,09-09 16:06:43.661  1714  2511 I iu.UploadsManager: num updated entries: 0
,09-09 16:06:43.663  1714  4310 I SystemUpdateService: active receiver: enabled
,09-09 16:06:43.665  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:06:43.667  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:06:43.670  4146  4146 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:06:43.677  4146  4146 D SprintDMHelper: simOperator: 
,09-09 16:06:43.677  4146  4146 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:06:43.680  1714  2511 I iu.SyncManager: NEXT; no task
,09-09 16:06:43.680  1714  4310 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:06:43.685  1714  4310 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-09 16:06:43.685  1714  4310 I SystemUpdateService: now status is 0 (complete)
,09-09 16:06:43.685  1714  4310 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 16:06:43.685  1714  4310 I SystemUpdateService: file has been verified
,09-09 16:06:43.686  1714  4310 I SystemUpdateService: OTA package size = 12249756
09-09 16:06:43.690  2906  4313 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 16:06:43.698  1714  4310 I SystemUpdateService: showing system update notification
,09-09 16:06:43.713   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-09 16:06:43.714   874  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 16:06:43.714   874  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 16:06:43.733  1714  1714 D SystemUpdateService: onDestroy
,09-09 16:06:45.304   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 16:06:45.311  1896  1896 I Keyboard.Facilitator: onFinishInput()
,09-09 16:06:45.324   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:06:45.324   874   894 I Adreno  : Build Date                       : 10/20/15
09-09 16:06:45.324   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:06:45.324   874   894 I Adreno  : Local Branch                     : M14
09-09 16:06:45.324   874   894 I Adreno  : Remote Branch                    : 
09-09 16:06:45.324   874   894 I Adreno  : Remote Branch                    : 
09-09 16:06:45.324   874   894 I Adreno  : Reconstruct Branch               : 
,09-09 16:06:45.364   280   684 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (313 us)
,09-09 16:06:46.025  3984  3984 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 16:06:46.025  3984  3984 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 16:06:46.063  3984  3984 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@39bfeaa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f63b882, 16908290=android.view.AbsSavedState$1@f63b882}, android:focusedViewId=100}]}]
,09-09 16:06:46.064  3984  3984 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 16:06:46.064  3984  3984 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 16:06:46.064  3984  3984 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-09 16:06:46.064   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 16:06:46.071   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 16:06:46.074   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 16:06:46.074   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
09-09 16:06:46.074   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 16:06:46.303   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 16:06:46.306   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 16:06:46.312   874  1336 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,09-09 16:06:46.318   874   894 I DreamManagerService: Entering dreamland.
,09-09 16:06:46.319   874   894 I PowerManagerService: Dozing...
,09-09 16:06:46.320   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 16:06:46.387   377  1283 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 16:06:46.388   377  1283 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 16:06:46.393   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:06:46.404   874  1312 E native  : do suspend false
,09-09 16:06:46.417  2010  4322 D NfcService: Discovery configuration equal, not updating.
,09-09 16:06:46.440   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:06:46.445   874  1312 E native  : do suspend true
,09-09 16:06:46.517   377  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 16:06:46.517   377  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 16:06:46.517   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a11be0:true
09-09 16:06:46.518  4130  4130 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 16:06:46.531  4130  4130 I bt_bluedroid: init
,09-09 16:06:46.531  4130  4324 I BluetoothAdapterState: Entering OffState
,09-09 16:06:46.539  4130  4325 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 16:06:46.539  4130  4325 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 16:06:46.539  4130  4325 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
09-09 16:06:46.540  4130  4325 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 16:06:46.543  4130  4130 I bt_bluedroid: get_profile_interface socket
,09-09 16:06:46.549  4130  4130 I bt_bluedroid: get_profile_interface sdp
,09-09 16:06:46.549  4130  4329 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:06:46.552  4130  4329 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:06:46.554  4130  4142 I bt_bluedroid: config_hci_snoop_log
,09-09 16:06:46.555   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 16:06:46.560  4130  4324 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 16:06:46.560  4130  4324 D BluetoothAdapterProperties: Setting state to 14
09-09 16:06:46.560  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 16:06:46.563  4130  4324 D BluetoothBondStateMachine: make
,09-09 16:06:46.566  4130  4331 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 16:06:46.571  4130  4324 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:06:46.572  4130  4130 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 16:06:46.574  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:46.575  4130  4130 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:06:46.576  4130  4130 D BtGatt.GattService: Received start request. Starting profile...
,09-09 16:06:46.577  4130  4130 D BtGatt.GattService: start()
09-09 16:06:46.577  4130  4130 I bt_bluedroid: get_profile_interface gatt
,09-09 16:06:46.578  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
09-09 16:06:46.578  4130  4130 D BtGatt.AdvertiseManager: advertise manager created
,09-09 16:06:46.585  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:06:46.585  4130  4130 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:46.585  4130  4130 V BluetoothAdapterState: isBleTurningOn()=true
09-09 16:06:46.585  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:46.585  4130  4324 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 16:06:46.586  4130  4324 I bt_bluedroid: enable
09-09 16:06:46.586  4130  4325 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 16:06:46.587  4130  4325 I bt_hci  : start_up
,09-09 16:06:46.594  4130  4325 I bt_vendor: alloc value 0xb3939189
,09-09 16:06:46.594  4130  4325 I bt_vendor: init
09-09 16:06:46.594  4130  4325 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 16:06:46.594  4130  4325 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 16:06:46.701  4130  4325 D bt_hci  : start_up starting async portion
,09-09 16:06:46.702  4130  4334 I bt_hci  : event_finish_startup
09-09 16:06:46.703  4130  4334 I bt_hci_h4: hal_open
,09-09 16:06:46.703  4130  4334 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 16:06:46.711  4130  4334 I bt_userial_vendor: device fd = 51 open
,09-09 16:06:46.743  4130  4334 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:06:46.775  4130  4334 D bt_hwcfg: Chipset BCM4354A2
,09-09 16:06:46.776  4130  4334 D bt_hwcfg: Target name = [BCM4354A2]
09-09 16:06:46.776  4130  4334 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 16:06:46.927  4273  4290 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 16:06:47.348  4130  4334 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 16:06:47.349  4130  4334 D bt_hwcfg: Settlement delay -- 100 ms
09-09 16:06:47.349  4130  4334 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 16:06:47.466  4130  4334 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-09 16:06:47.467  4130  4334 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 16:06:47.497  4130  4334 I bt_hwcfg: vendor lib fwcfg completed
,09-09 16:06:47.497  4130  4334 I bt_vendor: firmware callback
,09-09 16:06:47.497  4130  4334 I bt_hci  : firmware_config_callback
,09-09 16:06:47.508  4130  4338 I bt_btu  : btu_task pending for preload complete event
09-09 16:06:47.509  4130  4338 I bt_btu_task: Bluetooth chip preload is complete
,09-09 16:06:47.509  4130  4338 I bt_btu  : btu_task received preload complete event
,09-09 16:06:47.520  4130  4338 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 16:06:47.520  4130  4338 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 16:06:47.520  4130  4338 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 16:06:47.521  4130  4338 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 16:06:47.521  4130  4338 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 16:06:47.521  4130  4338 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 16:06:47.521  4130  4338 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 16:06:47.522  4130  4338 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 16:06:47.522  4130  4338 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 16:06:47.522  4130  4338 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 16:06:47.522  4130  4338 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 16:06:47.523  4130  4338 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 16:06:47.523  4130  4338 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 16:06:47.523  4130  4338 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 16:06:47.523  4130  4338 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 16:06:47.657  4130  4338 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,09-09 16:06:47.657  4130  4338 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d ,
,09-09 16:06:47.670  4130  4329 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 16:06:47.673  4130  4329 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 16:06:47.674  4130  4329 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:06:47.679  4130  4329 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:06:47.682  4130  4329 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:06:47.683  4130  4329 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 16:06:47.683  4130  4329 D bt_hci  : do_postload posting postload work item
,09-09 16:06:47.684  4130  4334 I bt_hci  : event_postload
,09-09 16:06:47.684  4130  4334 I bt_vendor: sco_config_cb
,09-09 16:06:47.684  4130  4334 I bt_hci  : sco_config_callback postload finished.
,09-09 16:06:47.687  4130  4329 D bt_bte_conf: Device ID record 1 : primary
09-09 16:06:47.687  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:47.687  4130  4329 D bt_bte_conf:   vendorId            = 000f
09-09 16:06:47.687  4130  4329 D bt_bte_conf:   vendorIdSource      = 0001
09-09 16:06:47.687  4130  4329 D bt_bte_conf:   product             = 1200
,09-09 16:06:47.688  4130  4329 D bt_bte_conf:   version             = 1436
09-09 16:06:47.688  4130  4329 D bt_bte_conf:   clientExecutableURL = 
,09-09 16:06:47.688  4130  4329 D bt_bte_conf:   serviceDescription  = 
,09-09 16:06:47.688  4130  4329 D bt_bte_conf:   documentationURL    = 
09-09 16:06:47.688  4130  4329 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 16:06:47.688  4130  4334 I bt_vendor: low_power_mode_cb
09-09 16:06:47.689  4130  4325 D bt_stack_manager: event_start_up_stack finished
,09-09 16:06:47.691  4130  4324 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-09 16:06:47.691  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 16:06:47.691  4130  4324 D BluetoothAdapterProperties: Setting state to 15
,09-09 16:06:47.691  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 16:06:47.692  4130  4324 I BluetoothAdapterState: Entering BleOnState
,09-09 16:06:47.698  4130  4324 D BluetoothAdapterState: Current state: BLE ON, message: 1,
,09-09 16:06:47.698  4130  4324 D BluetoothAdapterProperties: Setting state to 11
09-09 16:06:47.699  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 16:06:47.708  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:47.712  4130  4130 D HeadsetService: Received start request. Starting profile...
,09-09 16:06:47.714  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:47.718  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 16:06:47.720  4130  4130 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 16:06:47.720  4130  4130 D HeadsetStateMachine: make
,09-09 16:06:47.729  4130  4324 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:06:47.738  4130  4130 D HeadsetStateMachine: max_hf_connections = 1
,09-09 16:06:47.738  4130  4130 I bt_bluedroid: get_profile_interface handsfree
09-09 16:06:47.738  4130  4329 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040,
,09-09 16:06:47.739  4130  4329 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 16:06:47.743  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:47.743  4130  4130 D A2dpService: Received start request. Starting profile...
,09-09 16:06:47.744  4130  4130 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 16:06:47.745  4130  4130 I bt_bluedroid: get_profile_interface avrcp
,09-09 16:06:47.755  4130  4130 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 16:06:47.756  4130  4130 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 16:06:47.756  4130  4130 D A2dpStateMachine: make
,09-09 16:06:47.758  4130  4130 I bt_bluedroid: get_profile_interface a2dp
,09-09 16:06:47.759  4130  4329 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 16:06:47.762  4130  4347 D A2dpStateMachine: Enter Disconnected: -2
,09-09 16:06:47.763  4130  4130 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 16:06:47.764  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:47.765  4054  4054 D BluetoothInputDevice: Proxy object connected
09-09 16:06:47.765  4130  4130 D HidService: Received start request. Starting profile...
09-09 16:06:47.765  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 16:06:47.765  4130  4130 I bt_bluedroid: get_profile_interface hidhost
09-09 16:06:47.766  4130  4130 D HidService: setHidService(): set to: null
09-09 16:06:47.766  4130  4329 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
09-09 16:06:47.766  4130  4130 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 16:06:47.766  4130  4329 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 16:06:47.767  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
09-09 16:06:47.767  4130  4130 D HealthService: Received start request. Starting profile...
,09-09 16:06:47.768  4054  4054 D HidProfile: Bluetooth service connected
,09-09 16:06:47.769  4130  4130 I bt_bluedroid: get_profile_interface health
09-09 16:06:47.770  4130  4130 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 16:06:47.770  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:47.771  4130  4130 D PanService: Received start request. Starting profile...
,09-09 16:06:47.771  4054  4054 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:06:47.772  4130  4130 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 16:06:47.772  4130  4130 I bt_bluedroid: get_profile_interface pan
09-09 16:06:47.772  4054  4054 D PanProfile: Bluetooth service connected
09-09 16:06:47.773  4130  4329 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 16:06:47.775  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:47.776  4130  4130 D BluetoothMapService: Received start request. Starting profile...
09-09 16:06:47.776  4130  4130 D BluetoothMapService: start()
,09-09 16:06:47.776  4054  4054 D BluetoothMap: Proxy object connected
09-09 16:06:47.777  4054  4054 D MapProfile: Bluetooth service connected
09-09 16:06:47.777  4054  4054 D BluetoothMap: getConnectedDevices()
09-09 16:06:47.778  4054  4054 D BluetoothMap: Bluetooth is Not enabled
09-09 16:06:47.778  4130  4130 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-09 16:06:47.779  4130  4130 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 16:06:47.779  4130  4130 D BluetoothMapAppObserver: createReceiver()
,09-09 16:06:47.780  4130  4130 D BluetoothMapAppObserver: initObservers()
09-09 16:06:47.780  4130  4130 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 16:06:47.788  4130  4130 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:47.788  4130  4130 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:06:47.788  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:47.788  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isTurningOn()=true
09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isTurningOn()=true
09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:47.790  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:47.790  4130  4345 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:47.791  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:47.792  4130  4130 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:47.792  4130  4130 V BluetoothAdapterState: isTurningOn()=true
09-09 16:06:47.792  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:47.792  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:47.792  4130  4324 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 16:06:47.792  4130  4324 D BluetoothAdapterProperties: ScanMode =  20
09-09 16:06:47.792  4130  4324 D BluetoothAdapterProperties: State =  11
09-09 16:06:47.793  4130  4324 D BluetoothAdapterProperties: Setting state to 12
09-09 16:06:47.793  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 16:06:47.793  4054  4066 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:06:47.794  1355  1367 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:06:47.794  4130  4329 D BluetoothAdapterProperties: Scan Mode:21
09-09 16:06:47.794  4130  4329 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:06:47.794  4130  4324 I BluetoothAdapterState: Entering OnState
09-09 16:06:47.796  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:06:47.796  1355  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:06:47.796  1355  1355 D PanProfile: Bluetooth service connected
09-09 16:06:47.798  1355  1355 D BluetoothInputDevice: Proxy object connected
09-09 16:06:47.798  1355  1355 D HidProfile: Bluetooth service connected
09-09 16:06:47.798  4054  4065 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:06:47.798  1355  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:47.799  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:47.799  1355  3983 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 16:06:47.800   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:06:47.801   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:47.801  1355  2145 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:06:47.801  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:47.801   874   874 D BluetoothA2dp: Proxy object connected
09-09 16:06:47.802  1355  1355 D BluetoothA2dp: Proxy object connected
09-09 16:06:47.803  4054  4066 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 16:06:47.805  2022  2125 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:47.806   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:47.806   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:47.807  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:47.807  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:47.807  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:47.,807  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:47.807  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:47.807  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:47.807  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:47.807  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:47.807  1355  1367 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:06:47.807  4130  4130 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:06:47.808  4130  4130 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 16:06:47.808  1355  1355 D BluetoothMap: Proxy object connected
09-09 16:06:47.809  1355  1355 D MapProfile: Bluetooth service connected
09-09 16:06:47.809  1355  1355 D BluetoothMap: getConnectedDevices()
09-09 16:06:47.809  4054  4065 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:06:47.810  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:47.812   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 16:06:47.812  4130  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:06:47.815  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:47.816  4054  4054 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 16:06:47.816  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:47.818  4130  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:06:47.820  4130  4130 D ObexServerSockets: Succeed to create listening sockets 
09-09 16:06:47.820  4130  4130 D ObexServerSockets0: startAccept()
09-09 16:06:47.820  4130  4130 D ObexServerSockets0: prepareForNewConnect()
,09-09 16:06:47.822  4130  4130 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 16:06:47.823  4130  4130 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 16:06:47.823  4054  4054 D LocalBluetoothProfileManager: Adding local HEADSET profile,
09-09 16:06:47.823  4130  4130 D BluetoothMapService: onReceive
09-09 16:06:47.823  4130  4354 D ObexServerSockets0: Accepting socket connection...
09-09 16:06:47.823  4130  4130 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED,
09-09 16:06:47.823  4130  4355 D ObexServerSockets0: Accepting socket connection...
09-09 16:06:47.823  4130  4130 D BluetoothMapService: STATE_ON
,09-09 16:06:47.829  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:06:47.830  4054  4054 D BluetoothA2dp: Proxy object connected
,09-09 16:06:47.834  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:06:47.843  1355  1355 D BluetoothPbap: Proxy object connected
,09-09 16:06:47.844  1355  1355 D PbapServerProfile: Bluetooth service connected
,09-09 16:06:47.847  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:06:47.848  4054  4054 D BluetoothPbap: Proxy object connected
09-09 16:06:47.848  4054  4054 D PbapServerProfile: Bluetooth service connected
,09-09 16:06:47.849  4130  4130 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:06:47.849  4130  4130 D ObexServerSockets0: prepareForNewConnect()
09-09 16:06:47.853  4130  4359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:06:47.865  4130  4363 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:06:47.866  4130  4363 I BtOppRfcommListener: Accept thread started.
,09-09 16:06:47.903  1355  1367 D BluetoothHeadset: Proxy object connected
,09-09 16:06:47.904  1355  1355 D HeadsetProfile: Bluetooth service connected
,09-09 16:06:47.904   874   874 D BluetoothHeadset: Proxy object connected
09-09 16:06:47.904   874   874 D BluetoothHeadset: Proxy object connected
09-09 16:06:47.904   874   874 D BluetoothHeadset: Proxy object connected
09-09 16:06:47.905  2022  2188 D BluetoothHeadset: Proxy object connected
,09-09 16:06:47.907  2022  2033 D BluetoothHeadset: Proxy object connected
,09-09 16:06:47.908   874   891 D BluetoothHeadset: Proxy object connected
09-09 16:06:47.909   874   891 D BluetoothHeadset: Proxy object connected
,09-09 16:06:47.926  4054  4066 D BluetoothHeadset: Proxy object connected
,09-09 16:06:47.929  4054  4054 D HeadsetProfile: Bluetooth service connected
,09-09 16:06:49.473   874  1314 D ConnectivityService: handlePromptUnvalidated 101
,09-09 16:06:49.491  4130  4324 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 16:06:49.492  4130  4324 D BluetoothAdapterProperties: Setting state to 13
,09-09 16:06:49.492  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 16:06:49.494  4130  4324 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 16:06:49.500  4130  4324 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:06:49.500  4130  4329 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:06:49.502  4130  4324 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 16:06:49.508  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:49.508  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:06:49.511  4130  4130 D BluetoothMapService: onReceive
,09-09 16:06:49.511  4130  4130 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED,
09-09 16:06:49.511  4130  4130 D BluetoothMapService: STATE_TURNING_OFF
09-09 16:06:49.512  4130  4130 D BluetoothMapService: MAP Service closeService in
09-09 16:06:49.512  4130  4130 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 16:06:49.512  4130  4130 D ObexServerSockets0: shutdown(block = true)
09-09 16:06:49.513  4130  4354 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 16:06:49.514  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:49.514  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:49.516  4130  4130 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:06:49.517  4130  4355 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 16:06:49.517  4130  4130 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:06:49.518  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:49.518  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:49.518  4130  4341 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 16:06:49.519  3984  3984 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:06:49.519  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 16:06:49.519  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:06:49.520  4130  4130 D HeadsetService: Received stop request...Stopping profile...
09-09 16:06:49.521  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:49.523  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:49.528  4130  4130 I BtOppRfcommListener: stopping Accept Thread
,09-09 16:06:49.528  1355  2145 D BluetoothHeadset: Proxy object disconnected
09-09 16:06:49.528  4130  4363 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 16:06:49.529   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 16:06:49.529   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 16:06:49.529   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 16:06:49.529  2022  2034 D BluetoothHeadset: Proxy object disconnected
09-09 16:06:49.529  4130  4363 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 16:06:49.530  4054  4065 D BluetoothHeadset: Proxy object disconnected
09-09 16:06:49.531  4130  4130 D A2dpService: Received stop request...Stopping profile...
,09-09 16:06:49.531  4130  4347 D A2dpStateMachine: Exit Disconnected: -1
,09-09 16:06:49.533   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 16:06:49.533  1355  1355 D HeadsetProfile: Bluetooth service disconnected
09-09 16:06:49.533  1355  1355 D BluetoothA2dp: Proxy object disconnected
09-09 16:06:49.533  4130  4130 D HidService: Received stop request...Stopping profile...
09-09 16:06:49.533  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:06:49.533  4130  4130 D HidService: Stopping Bluetooth HidService
09-09 16:06:49.534  4054  4054 D HeadsetProfile: Bluetooth service disconnected
09-09 16:06:49.534  4130  4130 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:49.534  4130  4130 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:06:49.534  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:49.535  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:49.535  1355  1355 D BluetoothInputDevice: Proxy object disconnected
,09-09 16:06:49.535  1355  1355 D HidProfile: Bluetooth service disconnected
09-09 16:06:49.535  4130  4130 D HealthService: Received stop request...Stopping profile...
09-09 16:06:49.535  4054  4054 D BluetoothA2dp: Proxy object disconnected
09-09 16:06:49.538  4054  4054 D BluetoothInputDevice: Proxy object disconnected
09-09 16:06:49.538  4054  4054 D HidProfile: Bluetooth service disconnected
,09-09 16:06:49.540  4130  4130 D PanService: Received stop request...Stopping profile...
,09-09 16:06:49.541  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 16:06:49.542  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 16:06:49.542  1355  1355 D PanProfile: Bluetooth service disconnected
,09-09 16:06:49.544  4054  4054 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:06:49.544  4054  4054 D PanProfile: Bluetooth service disconnected
,09-09 16:06:49.544  4130  4130 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 16:06:49.544  4130  4130 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 16:06:49.544  4130  4329 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 16:06:49.545  4130  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:49.545  4130  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:49.545  4130  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:49.545  4130  4329 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-09 16:06:49.545  4130  4130 D BluetoothMapService: Received stop request...Stopping profile...
09-09 16:06:49.545  4130  4130 D BluetoothMapService: stop()
,09-09 16:06:49.546  4130  4130 D BluetoothMapAppObserver: deinitObservers()
09-09 16:06:49.546  4130  4130 D BluetoothMapAppObserver: removeReceiver()
09-09 16:06:49.547  1355  1355 D BluetoothMap: Proxy object disconnected
09-09 16:06:49.547  1355  1355 D MapProfile: Bluetooth service disconnected
09-09 16:06:49.547  4054  4054 D BluetoothMap: Proxy object disconnected
09-09 16:06:49.547  4054  4054 D MapProfile: Bluetooth service disconnected
,09-09 16:06:49.549  4130  4130 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:49.549  4130  4130 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:49.549  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:49.549  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:06:49.551  4130  4329 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 16:06:49.551  4130  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:49.551  4130  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:49.551  4130  4130 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:49.551  4130  4338 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:06:49.551  4130  4130 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:49.551  4130  4338 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:06:49.551  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:49.551  4130  4338 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:06:49.551  4130  4338 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 16:06:49.551  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:49.552  4130  4130 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 16:06:49.552  4130  4130 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 16:06:49.552  4130  4329 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 16:06:49.552  4130  4130 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:49.552  4130  4130 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:49.552  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:49.553  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:49.553  4130  4130 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 16:06:49.553  4130  4329 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 16:06:49.553  4130  4130 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 16:06:49.555  1355  1355 D BluetoothPbap: Proxy object disconnected
,09-09 16:06:49.555  1355  1355 D PbapServerProfile: Bluetooth service disconnected
09-09 16:06:49.556  4054  4054 D BluetoothPbap: Proxy object disconnected
09-09 16:06:49.556  4054  4054 D PbapServerProfile: Bluetooth service disconnected
,09-09 16:06:49.556  4130  4130 V BluetoothAdapterState: isTurningOff()=true
09-09 16:06:49.556  4130  4130 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:06:49.556  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:49.556  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:49.557  4130  4130 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 16:06:49.557  4130  4130 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 16:06:49.558  4130  4130 D BluetoothMapService: MAP Service closeService in
,09-09 16:06:49.558  4130  4130 V BluetoothAdapterState: isTurningOff()=true
,09-09 16:06:49.558  4130  4130 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:49.558  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:06:49.559  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:49.559  4130  4324 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-09 16:06:49.559  4130  4324 D BluetoothAdapterProperties: Setting state to 15
09-09 16:06:49.559  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 16:06:49.559  4130  4324 I BluetoothAdapterState: Entering BleOnState
,09-09 16:06:49.560  4130  4130 D BluetoothMapService: cleanup()
,09-09 16:06:49.560  4130  4130 D BluetoothMapService: MAP Service closeService in
09-09 16:06:49.560  4054  4066 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 16:06:49.561  1355  1367 D BluetoothPan: onBluetoothStateChange on: false
,09-09 16:06:49.564  1355  2145 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 16:06:49.565  4054  4065 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:06:49.566  4054  4066 D BluetoothPan: onBluetoothStateChange on: false
,09-09 16:06:49.566  1355  3983 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:06:49.567  1355  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 16:06:49.567   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:06:49.567   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:06:49.567  1355  1367 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:06:49.568  4054  4065 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 16:06:49.568  2022  2232 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:49.569  4054  4066 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:49.569   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:49.569   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:06:49.569  1355  2145 D BluetoothMap: onBluetoothStateChange: up=false
09-09 16:06:49.570  4054  4065 D BluetoothMap: onBluetoothStateChange: up=false
09-09 16:06:49.570  4130  4324 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-09 16:06:49.570  4130  4324 D BluetoothAdapterProperties: Setting state to 16
09-09 16:06:49.570  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 16:06:49.571  4130  4324 D BluetoothAdapterProperties: onBleDisable
09-09 16:06:49.573  4130  4324 I BluetoothAdapterState: Entering PendingCommandState
09-09 16:06:49.573  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:49.573  4130  4325 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 16:06:49.574  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:49.575  4130  4329 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:06:49.575  4130  4338 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 16:06:49.575  4130  4338 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:06:49.577  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:49.578  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 16:06:49.579  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:49.585  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:06:49.589  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:06:49.776  4130  4329 I bt_hci  : shut_down
,09-09 16:06:49.777  4130  4334 D bt_hwcfg: hw_epilog_process
,09-09 16:06:49.778  4130  4334 I bt_vendor: low_power_mode_cb
,09-09 16:06:49.803  4130  4334 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 16:06:49.803  4130  4334 I bt_vendor: epilog_cb
09-09 16:06:49.803  4130  4334 I bt_hci  : epilog_finished_callback
,09-09 16:06:49.815  4130  4329 I bt_hci_h4: hal_close
,09-09 16:06:49.816  4130  4329 I bt_userial_vendor: device fd = 51 close
,09-09 16:06:49.933  4130  4325 D bt_stack_manager: event_shut_down_stack finished.
,09-09 16:06:49.934  4130  4324 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 16:06:49.942  4130  4324 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 16:06:49.942  4130  4130 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 16:06:49.944  4130  4130 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 16:06:49.944  4130  4130 D BtGatt.GattService: stop()
,09-09 16:06:49.944  4130  4130 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 16:06:49.950  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:06:49.951  4130  4130 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:49.951  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:49.951  4130  4130 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 16:06:49.952  4130  4324 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 16:06:49.953  4130  4324 D BluetoothAdapterProperties: Setting state to 10
,09-09 16:06:49.953  4130  4324 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 16:06:49.955  4130  4324 I BluetoothAdapterState: Entering OffState
09-09 16:06:49.956   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 16:06:49.988  4130  4130 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 16:06:49.988  4130  4130 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-09 16:06:49.991  4130  4325 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 16:06:49.994  4130  4130 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 16:06:50.003  4130  4325 D bt_stack_manager: event_clean_up_stack finished.
,09-09 16:06:50.010  4130  4130 I art     : System.exit called, status: 0
09-09 16:06:50.011  4130  4130 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 16:06:50.066   874   884 I ActivityManager: Process com.android.bluetooth (pid 4130) has died
,09-09 16:06:52.019  3712  3774 D Finsky  : [338] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-09 16:06:52.038  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:52.051  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:52.056  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:52.120  1504  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 16:06:52.120  1504  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-09 16:06:52.120  1504  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:06:52.121  1504  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:52.174  3712  3774 D Finsky  : [338] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-09 16:06:52.488  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:06:52.489  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:54.522  1866  2788 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 16:06:55.496  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:55.497  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6395b93 added. We now have 6 listener(s)
09-09 16:06:55.497  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:06:55.501  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:55.501  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@704f7d0 added. We now have 7 listener(s)
09-09 16:06:55.502  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:55.503  3984  4036 I System.out: IsBluetoothEnabled
,09-09 16:06:55.516  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:55.567   874   891 I ActivityManager: Start proc 4378:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 16:06:55.684  4378  4378 D AdapterServiceConfig: Adding HeadsetService
,09-09 16:06:55.684  4378  4378 D AdapterServiceConfig: Adding A2dpService
09-09 16:06:55.685  4378  4378 D AdapterServiceConfig: Adding HidService
09-09 16:06:55.685  4378  4378 D AdapterServiceConfig: Adding HealthService
09-09 16:06:55.685  4378  4378 D AdapterServiceConfig: Adding PanService
09-09 16:06:55.685  4378  4378 D AdapterServiceConfig: Adding GattService
,09-09 16:06:55.685  4378  4378 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 16:06:55.697  4378  4378 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 16:06:55.697   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@59307ef:true
,09-09 16:06:55.702  4378  4378 I bt_bluedroid: init
,09-09 16:06:55.703  4378  4390 I BluetoothAdapterState: Entering OffState
,09-09 16:06:55.707  4378  4391 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 16:06:55.708  4378  4391 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 16:06:55.708  4378  4391 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 16:06:55.708  4378  4391 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 16:06:55.709  4378  4378 I bt_bluedroid: get_profile_interface socket
09-09 16:06:55.711  4378  4394 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:06:55.712  4378  4378 I bt_bluedroid: get_profile_interface sdp
09-09 16:06:55.713  4378  4394 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:06:55.718  4378  4389 I bt_bluedroid: config_hci_snoop_log
09-09 16:06:55.721   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 16:06:55.737  4378  4390 D BluetoothAdapterState: Current state: OFF, message: 0
09-09 16:06:55.738  4378  4390 D BluetoothAdapterProperties: Setting state to 14
09-09 16:06:55.738  4378  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-09 16:06:55.743  4378  4390 D BluetoothBondStateMachine: make
,09-09 16:06:55.750  4378  4395 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 16:06:55.757  4378  4390 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:06:55.760  4378  4378 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 16:06:55.771  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:55.774  4378  4378 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:06:55.775  4378  4378 D BtGatt.GattService: Received start request. Starting profile...
09-09 16:06:55.776  4378  4378 D BtGatt.GattService: start()
09-09 16:06:55.776  4378  4378 I bt_bluedroid: get_profile_interface gatt
,09-09 16:06:55.781  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:55.781  4378  4378 D BtGatt.AdvertiseManager: advertise manager created
,09-09 16:06:55.793  4378  4378 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:06:55.793  4378  4378 V BluetoothAdapterState: isTurningOn()=false
09-09 16:06:55.793  4378  4378 V BluetoothAdapterState: isBleTurningOn()=true
09-09 16:06:55.793  4378  4378 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:06:55.793  4378  4390 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 16:06:55.794  4378  4390 I bt_bluedroid: enable
09-09 16:06:55.795  4378  4391 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 16:06:55.796  4378  4391 I bt_hci  : start_up
,09-09 16:06:55.816  4378  4391 I bt_vendor: alloc value 0xb39a2189
,09-09 16:06:55.816  4378  4391 I bt_vendor: init
09-09 16:06:55.816  4378  4391 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 16:06:55.817  4378  4391 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 16:06:55.924  4378  4391 D bt_hci  : start_up starting async portion
,09-09 16:06:55.925  4378  4398 I bt_hci  : event_finish_startup
09-09 16:06:55.925  4378  4398 I bt_hci_h4: hal_open
,09-09 16:06:55.925  4378  4398 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 16:06:55.938  4378  4398 I bt_userial_vendor: device fd = 51 open
,09-09 16:06:55.968  4378  4398 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:06:55.999  4378  4398 D bt_hwcfg: Chipset BCM4354A2
,09-09 16:06:56.000  4378  4398 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 16:06:56.000  4378  4398 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 16:06:56.856  4378  4398 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 16:06:56.858  4378  4398 D bt_hwcfg: Settlement delay -- 100 ms
09-09 16:06:56.858  4378  4398 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 16:06:56.976  4378  4398 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:06:56.978  4378  4398 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 16:06:57.005  4378  4398 I bt_hwcfg: vendor lib fwcfg completed
,09-09 16:06:57.006  4378  4398 I bt_vendor: firmware callback
09-09 16:06:57.006  4378  4398 I bt_hci  : firmware_config_callback
,09-09 16:06:57.018  4378  4400 I bt_btu  : btu_task pending for preload complete event
,09-09 16:06:57.019  4378  4400 I bt_btu_task: Bluetooth chip preload is complete
,09-09 16:06:57.019  4378  4400 I bt_btu  : btu_task received preload complete event
,09-09 16:06:57.029  4378  4400 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 16:06:57.030  4378  4400 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 16:06:57.030  4378  4400 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 16:06:57.030  4378  4400 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 16:06:57.031  4378  4400 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 16:06:57.031  4378  4400 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 16:06:57.031  4378  4400 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 16:06:57.031  4378  4400 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 16:06:57.031  4378  4400 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 16:06:57.032  4378  4400 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 16:06:57.032  4378  4400 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 16:06:57.032  4378  4400 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 16:06:57.033  4378  4400 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 16:06:57.033  4378  4400 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 16:06:57.033  4378  4400 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 16:06:57.177  4378  4400 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391fd9d
,09-09 16:06:57.178  4378  4400 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391fd9d 
,09-09 16:06:57.209  4378  4394 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 16:06:57.210  4378  4394 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 16:06:57.211  4378  4394 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:06:57.213  4378  4394 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:06:57.216  4378  4394 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:06:57.216  4378  4394 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 16:06:57.216  4378  4394 D bt_hci  : do_postload posting postload work item
09-09 16:06:57.217  4378  4398 I bt_hci  : event_postload
09-09 16:06:57.218  4378  4398 I bt_vendor: sco_config_cb
09-09 16:06:57.218  4378  4398 I bt_hci  : sco_config_callback postload finished.
,09-09 16:06:57.220  4378  4394 D bt_bte_conf: Device ID record 1 : primary
09-09 16:06:57.220  4378  4394 D bt_bte_conf:   vendorId            = 000f,
09-09 16:06:57.220  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:57.220  4378  4394 D bt_bte_conf:   vendorIdSource      = 0001
09-09 16:06:57.220  4378  4394 D bt_bte_conf:   product             = 1200
09-09 16:06:57.221  4378  4394 D bt_bte_conf:   version             = 1436
,09-09 16:06:57.221  4378  4394 D bt_bte_conf:   clientExecutableURL = 
09-09 16:06:57.221  4378  4394 D bt_bte_conf:   serviceDescription  = 
09-09 16:06:57.221  4378  4394 D bt_bte_conf:   documentationURL    = 
,09-09 16:06:57.222  4378  4394 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 16:06:57.222  4378  4391 D bt_stack_manager: event_start_up_stack finished
09-09 16:06:57.224  4378  4390 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 16:06:57.224  4378  4390 D BluetoothAdapterProperties: Setting state to 15
09-09 16:06:57.225  4378  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 16:06:57.225  4378  4398 I bt_vendor: low_power_mode_cb
09-09 16:06:57.226  4378  4390 I BluetoothAdapterState: Entering BleOnState
,09-09 16:06:57.232  4378  4390 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 16:06:57.232  4378  4390 D BluetoothAdapterProperties: Setting state to 11
,09-09 16:06:57.232  4378  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 16:06:57.243  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
09-09 16:06:57.245  4378  4378 D HeadsetService: Received start request. Starting profile...
,09-09 16:06:57.248  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:57.249  4378  4378 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 16:06:57.250  4378  4378 D HeadsetStateMachine: make
,09-09 16:06:57.260  4378  4378 D HeadsetStateMachine: max_hf_connections = 1
09-09 16:06:57.261  4378  4378 I bt_bluedroid: get_profile_interface handsfree
09-09 16:06:57.261  4378  4394 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-09 16:06:57.261  4378  4394 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 16:06:57.264  4378  4390 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:06:57.266  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:57.267  4378  4378 D A2dpService: Received start request. Starting profile...
,09-09 16:06:57.268  4378  4378 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 16:06:57.268  4378  4378 I bt_bluedroid: get_profile_interface avrcp
,09-09 16:06:57.276  4378  4378 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 16:06:57.276  4378  4378 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 16:06:57.276  4378  4378 D A2dpStateMachine: make
,09-09 16:06:57.279  4378  4378 I bt_bluedroid: get_profile_interface a2dp
,09-09 16:06:57.280  4378  4394 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 16:06:57.281  4378  4408 D A2dpStateMachine: Enter Disconnected: -2
,09-09 16:06:57.282  4378  4378 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 16:06:57.283  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:57.283  4378  4378 D HidService: Received start request. Starting profile...
,09-09 16:06:57.284  4378  4378 I bt_bluedroid: get_profile_interface hidhost
09-09 16:06:57.284  4378  4394 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39013e5
,09-09 16:06:57.284  4378  4394 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 16:06:57.284  4378  4378 D HidService: setHidService(): set to: null
,09-09 16:06:57.287  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:06:57.287  4378  4378 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 16:06:57.289  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
09-09 16:06:57.290  4378  4378 D HealthService: Received start request. Starting profile...
,09-09 16:06:57.291  4378  4378 I bt_bluedroid: get_profile_interface health
,09-09 16:06:57.292  4378  4378 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 16:06:57.293  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
09-09 16:06:57.293  4378  4378 D PanService: Received start request. Starting profile...
09-09 16:06:57.294  4378  4378 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 16:06:57.294  4378  4378 I bt_bluedroid: get_profile_interface pan
09-09 16:06:57.295  4378  4394 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 16:06:57.297  4378  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
09-09 16:06:57.298  4378  4378 D BluetoothMapService: Received start request. Starting profile...
09-09 16:06:57.298  4378  4378 D BluetoothMapService: start()
,09-09 16:06:57.300  4378  4378 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 16:06:57.301  4378  4378 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 16:06:57.301  4378  4378 D BluetoothMapAppObserver: createReceiver()
,09-09 16:06:57.302  4378  4378 D BluetoothMapAppObserver: initObservers()
09-09 16:06:57.302  4378  4378 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 16:06:57.309  4378  4378 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:06:57.309  4378  4378 V BluetoothAdapterState: isTurningOn()=true
09-09 16:06:57.309  4378  4378 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:57.309  4378  4378 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:06:57.311  4378  4378 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:06:57.311  4378  4378 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:06:57.311  4378  4378 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:57.311  4378  4378 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:06:57.312  4378  4378 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:57.312  4378  4378 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:06:57.312  4378  4406 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 16:06:57.312  4378  4378 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:06:57.312  4378  4378 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:57.314  4378  4378 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:57.314  4378  4378 V BluetoothAdapterState: isTurningOn()=true
09-09 16:06:57.314  4378  4378 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isTurningOff()=false
09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:06:57.315  4378  4378 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:06:57.316  4378  4390 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 16:06:57.316  4378  4390 D BluetoothAdapterProperties: ScanMode =  20
09-09 16:06:57.316  4378  4390 D BluetoothAdapterProperties: State =  11
09-09 16:06:57.316  4378  4390 D BluetoothAdapterProperties: Setting state to 12
09-09 16:06:57.316  4378  4390 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 16:06:57.317  4378  4390 I BluetoothAdapterState: Entering OnState
,09-09 16:06:57.317  4054  4065 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:06:57.320  4378  4394 D BluetoothAdapterProperties: Scan Mode:21
09-09 16:06:57.320  4378  4394 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:06:57.323  1355  1367 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:06:57.326  1355  2145 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:06:57.327  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:06:57.327  1355  1355 D PanProfile: Bluetooth service connected
09-09 16:06:57.327  4054  4054 D BluetoothInputDevice: Proxy object connected
09-09 16:06:57.328  4054  4054 D HidProfile: Bluetooth service connected
,09-09 16:06:57.328  1355  1355 D BluetoothInputDevice: Proxy object connected
09-09 16:06:57.328  1355  1355 D HidProfile: Bluetooth service connected
09-09 16:06:57.328  4054  4369 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:57.329  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:06:57.330  4378  4378 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:06:57.330  4378  4378 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 16:06:57.332  4378  4378 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:06:57.332  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:57.333  4054  4065 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:06:57.336  1355  3983 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:57.336  4378  4378 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:06:57.336  4054  4054 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:06:57.337  4054  4054 D PanProfile: Bluetooth service connected
09-09 16:06:57.337  1355  2145 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 16:06:57.337  4378  4378 D ObexServerSockets: Succeed to create listening sockets 
09-09 16:06:57.337  4378  4378 D ObexServerSockets0: startAccept()
09-09 16:06:57.337  4378  4378 D ObexServerSockets0: prepareForNewConnect()
09-09 16:06:57.338   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:06:57.339   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:57.339  1355  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:06:57.340  4378  4378 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 16:06:57.340  4378  4378 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-09 16:06:57.341  4378  4416 D ObexServerSockets0: Accepting socket connection...
09-09 16:06:57.341   874   874 D BluetoothA2dp: Proxy object connected
09-09 16:06:57.341  4378  4415 D ObexServerSockets0: Accepting socket connection...
09-09 16:06:57.341  1355  1355 D BluetoothA2dp: Proxy object connected
09-09 16:06:57.342  4054  4369 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 16:06:57.342  4054  4054 D BluetoothA2dp: Proxy object connected
,09-09 16:06:57.349  2022  2034 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 16:06:57.350  4054  4065 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 16:06:57.351   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:57.352   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:06:57.352  1355  3983 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 16:06:57.355  4054  4066 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:06:57.357  1355  1355 D BluetoothMap: Proxy object connected
,09-09 16:06:57.357  1355  1355 D MapProfile: Bluetooth service connected
,09-09 16:06:57.357  1355  1355 D BluetoothMap: getConnectedDevices()
09-09 16:06:57.357  4054  4054 D BluetoothMap: Proxy object connected
09-09 16:06:57.357  4054  4054 D MapProfile: Bluetooth service connected
09-09 16:06:57.357  4054  4054 D BluetoothMap: getConnectedDevices()
,09-09 16:06:57.361   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 16:06:57.362  4378  4378 D BluetoothMapService: onReceive
,09-09 16:06:57.362  4378  4378 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 16:06:57.362  4378  4378 D BluetoothMapService: STATE_ON
09-09 16:06:57.364  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:57.370  4054  4054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:06:57.378  4054  4054 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:06:57.380  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:06:57.392  4054  4054 D BluetoothPbap: Proxy object connected
09-09 16:06:57.392  1355  1355 D BluetoothPbap: Proxy object connected
,09-09 16:06:57.392  4054  4054 D PbapServerProfile: Bluetooth service connected
09-09 16:06:57.393  1355  1355 D PbapServerProfile: Bluetooth service connected
09-09 16:06:57.393  4378  4378 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:06:57.393  4378  4378 D ObexServerSockets0: prepareForNewConnect()
,09-09 16:06:57.407  4378  4421 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:06:57.436  4378  4425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:06:57.437  4378  4425 I BtOppRfcommListener: Accept thread started.
,09-09 16:06:57.440  1355  1377 D BluetoothHeadset: Proxy object connected
,09-09 16:06:57.440  1355  1355 D HeadsetProfile: Bluetooth service connected
09-09 16:06:57.440   874   874 D BluetoothHeadset: Proxy object connected
09-09 16:06:57.440   874   874 D BluetoothHeadset: Proxy object connected
,09-09 16:06:57.440   874   874 D BluetoothHeadset: Proxy object connected
09-09 16:06:57.441  2022  2232 D BluetoothHeadset: Proxy object connected
09-09 16:06:57.441  4054  4369 D BluetoothHeadset: Proxy object connected
09-09 16:06:57.441  4054  4054 D HeadsetProfile: Bluetooth service connected
,09-09 16:06:57.451  2022  2125 D BluetoothHeadset: Proxy object connected
09-09 16:06:57.451  4054  4066 D BluetoothHeadset: Proxy object connected
09-09 16:06:57.451  4054  4054 D HeadsetProfile: Bluetooth service connected
,09-09 16:06:57.452   874   891 D BluetoothHeadset: Proxy object connected
,09-09 16:06:57.452   874   891 D BluetoothHeadset: Proxy object connected
,09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:57.538  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:06:57.546  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:06:57.549  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:57.550  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7f13c9 added. We now have 8 listener(s)
,09-09 16:06:57.550  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:06:57.556   874  1981 D WifiService: setWifiEnabled: false pid=3984, uid=10000
,09-09 16:06:57.556   874  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:06:57.571  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:57.572   874  2063 D WifiService: setWifiEnabled: true pid=3984, uid=10000
,09-09 16:06:57.573   874  2063 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:06:57.588   874  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:57.606  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:06:57.616  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:06:57.619   874  1312 D WifiConfigStore: loaded 0 passpoint configs
09-09 16:06:57.620   874  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 16:06:57.621   874  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 16:06:57.622   874  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 16:06:57.622   874  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 16:06:57.622   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 16:06:57.622   874  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 16:06:57.639   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 16:06:57.641   373   873 D CommandListener: Setting iface cfg
,09-09 16:06:57.641   874  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.15 rxSuccessRate=0.41 delta 1000 -> 1000
09-09 16:06:57.641   874  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-09 16:06:57.642   874  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 16:06:57.642   874  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 16:06:57.659   874  1311 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 16:06:57.660   874  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 16:06:57.663   874  1312 E native  : do suspend true
,09-09 16:06:57.714   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 16:06:57.714   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:06:57.728   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 16:06:57.818   874  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 16:06:57.821  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 16:06:58.257  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 16:06:58.312  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 16:06:58.313  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 16:06:58.324   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:06:58.335   874  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 16:06:58.335   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 16:06:58.336   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 16:06:58.358   874  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:06:58.375   373   873 D CommandListener: Setting iface cfg
,09-09 16:06:58.377   874  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 16:06:58.386   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 16:06:58.428   874  4432 D DhcpClient: Receive thread started
,09-09 16:06:58.511   874  1312 E native  : do suspend false
,09-09 16:06:58.531   874  2115 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 16:06:58.545   874  4432 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-09 16:06:58.546   874  2115 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-09 16:06:58.550   874  2115 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 16:06:58.562   874  4432 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 16:06:58.564   874  2115 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 16:06:58.570   373   873 D CommandListener: Setting iface cfg,
,09-09 16:06:58.582   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 16:06:58.582   874  2115 D DhcpClient: Scheduling renewal in 86399s
,09-09 16:06:58.588   874  1312 E native  : do suspend true
,09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:06:58.600  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:06:58.607  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:06:58.619  3984  4036 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 16:06:58.621  3984  4036 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 16:06:58.621   874  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 16:06:58.624   874  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 16:06:58.627   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 16:06:58.628  3984  4036 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@39bfeaa Bundle[{}]
,09-09 16:06:58.631   874  1314 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 16:06:58.633  3984  4036 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 16:06:58.634  3984  4036 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 16:06:58.635  3984  4036 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 16:06:58.639   874  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 16:06:58.641  3984  4036 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 16:06:58.644  3984  4036 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 16:06:58.645  3984  4036 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 16:06:58.652  3984  4036 I System.out: Running OutgoingSocketThread
,09-09 16:06:58.655  3984  4435 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 465)
,09-09 16:06:58.657  3984  4435 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40563
,09-09 16:06:58.657  3984  4435 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 16:06:58.668   874  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 16:06:58.668   874  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 16:06:58.669   874  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 16:06:58.670   874  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 16:06:58.671   874  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 16:06:58.680   874  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 16:06:58.684   874  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-09 16:06:58.684   874  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-09 16:06:58.685   874  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 16:06:58.685   874  1314 D ConnectivityService:    accepting network in place of null
09-09 16:06:58.685   874  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 16:06:58.685   874  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:06:58.686   874  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:06:58.700   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=163367, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 16:06:58.746   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:06:58.777   874  4430 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 16:06:58.781   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:06:58.786   874  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 16:06:58.786   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:06:58.791   874  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 16:06:58.793   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:58.811  3984  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:58.813  3984  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:58.831  1714  1714 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:06:58.834  1714  1714 D SystemUpdateService: onCreate
,09-09 16:06:58.839  1714  1714 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:06:58.848  1714  4443 I SystemUpdateService: active receiver: enabled
,09-09 16:06:58.857   874  4430 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 14:06:58 GMT], X-Android-Received-Millis=[1473430018856], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473430018827]}
,09-09 16:06:58.858   874  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 16:06:58.858   874  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 16:06:58.858   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 16:06:58.859   874  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 16:06:58.864  1714  4443 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:06:58.866  1714  1714 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 16:06:58.875  1714  4443 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 16:06:58.875  1714  4443 I SystemUpdateService: now status is 0 (complete)
09-09 16:06:58.875  1714  4443 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 16:06:58.875  1714  4443 I SystemUpdateService: file has been verified
,09-09 16:06:58.876  1714  4443 I SystemUpdateService: OTA package size = 12249756
09-09 16:06:58.876  1714  2511 I iu.UploadsManager: num queued entries: 0
,09-09 16:06:58.877  1714  2511 I iu.UploadsManager: num updated entries: 0
09-09 16:06:58.878  1714  2511 I iu.SyncManager: NEXT; no task
,09-09 16:06:58.880  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:06:58.882  1714  1714 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:06:58.884  4146  4146 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:06:58.889  1714  4443 I SystemUpdateService: showing system update notification
,09-09 16:06:58.890  4146  4146 D SprintDMHelper: simOperator: 
09-09 16:06:58.890  4146  4146 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:06:58.962  1714  4447 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 16:06:58.962  1714  4447 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 16:06:58.965  1714  4447 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 16:06:58.986  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:59.005  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:06:59.018  2906  4449 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 16:06:59.021  1714  1714 D SystemUpdateService: onDestroy
,09-09 16:06:59.043  1504  3190 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 16:06:59.043  1504  3190 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 16:06:59.043  1504  3190 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:06:59.043  1504  3190 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:06:59.055  1714  4447 E MDM     : [187] SitrepService.a: Error sending sitrep.
,09-09 16:06:59.655  3984  4036 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 466)
09-09 16:06:59.656  3984  4036 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 466)
,09-09 16:06:59.665  3984  4036 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 471)
,09-09 16:06:59.668  3984  4036 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 16:06:59.668  3984  4036 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 472)
,09-09 16:06:59.676  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:06:59.676  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398dace added. We now have 2 listener(s)
,09-09 16:06:59.683  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:06:59.684  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.684  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:59.684  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:59.684  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4141def added. We now have 9 listener(s)
,09-09 16:06:59.684  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,09-09 16:06:59.685  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:06:59.687  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:59.696  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:59.699  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:59.699  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:06:59.699  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:06:59.699  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95c2385 added. We now have 3 listener(s)
,09-09 16:06:59.702  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:06:59.702  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:06:59.702  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:06:59.702  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:59.702  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cebd5da added. We now have 10 listener(s)
,09-09 16:06:59.703  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:06:59.703  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:59.703  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:59.703  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:59.703  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:59.703  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.703  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.703  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:59.703  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398dace removed from the list
09-09 16:06:59.704  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.704  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4141def removed from the list
,09-09 16:06:59.704  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.704  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:59.705  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.705  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.705  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.716  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.716  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:59.716  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.717  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4141def not in the list
,09-09 16:06:59.717  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.717  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.718  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:59.718  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.718  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:59.719  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cebd5da removed from the list
09-09 16:06:59.719  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:59.719  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.719  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.719  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:59.719  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95c2385 removed from the list
09-09 16:06:59.720  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:06:59.720  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2eaa0b added. We now have 2 listener(s)
09-09 16:06:59.720  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.722  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:06:59.722  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.722  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:59.722  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:59.722  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72ff0e8 added. We now have 9 listener(s)
09-09 16:06:59.722  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:59.723  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:06:59.725  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:59.733  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:59.736  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:59.736  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:06:59.737  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:06:59.737  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4175a6 added. We now have 3 listener(s)
09-09 16:06:59.738  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.739  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:06:59.739  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.739  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:59.739  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:59.740  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21bdbe7 added. We now have 10 listener(s)
09-09 16:06:59.740  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:59.740  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:06:59.740  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:06:59.740  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:06:59.740  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.740  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:59.741  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.744  3984  4036 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:59.744  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:59.748  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:59.750  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:06:59.750  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:06:59.754  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:06:59.754  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 16:06:59.754  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:06:59.755  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:59.759  4378  4389 D BtGatt.GattService: registerClient() - UUID=1c06f024-7d98-4b0d-b0a2-fe4bbbf816c9
,09-09 16:06:59.760  4378  4394 D BtGatt.GattService: onClientRegistered() - UUID=1c06f024-7d98-4b0d-b0a2-fe4bbbf816c9, clientIf=5
,09-09 16:06:59.761  3984  3995 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:06:59.762  4378  4414 D BtGatt.GattService: start scan with filters
,09-09 16:06:59.766  4378  4397 D BtGatt.ScanManager: handling starting scan
09-09 16:06:59.766  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:06:59.767  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:06:59.767  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:06:59.767  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:06:59.769  4378  4397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b9169e
,09-09 16:06:59.772  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:06:59.772  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:06:59.773  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 16:06:59.775  4378  4394 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 16:06:59.776  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.776  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:06:59.776  4378  4397 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:06:59.781  3984  4036 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 16:06:59.781  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:59.781  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 16:06:59.781  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.781  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:59.782  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:06:59.782  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:06:59.782  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 16:06:59.782  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 16:06:59.783  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 16:06:59.783  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:06:59.784  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:59.785  4378  4389 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:06:59.786   874  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network,
,09-09 16:06:59.787  4378  4414 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 16:06:59.787  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:06:59.788  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 16:06:59.788  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:06:59.788  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:06:59.788  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:06:59.790  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 16:06:59.790  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:59.791  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:06:59.791  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:59.792  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.793  4378  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:06:59.793  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.794  4378  4397 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:06:59.795  4378  4397 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 16:06:59.799  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:06:59.799  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-09 16:06:59.799  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:59.805  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:59.805  3984  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:06:59.805  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:59.805  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:59.805  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:59.805  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:59.805  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.805  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:59.805  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:59.806  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2eaa0b removed from the list
09-09 16:06:59.806  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.806  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72ff0e8 removed from the list
,09-09 16:06:59.806  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:59.806  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.807  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.807  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 16:06:59.807  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.807  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.808  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.808  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:59.808  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.808  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72ff0e8 not in the list
09-09 16:06:59.812  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:59.814  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:59.814  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:06:59.814  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:59.815  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.815  4378  4394 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:06:59.815  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.818  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.818  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.819  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:59.820  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:59.820  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:59.820  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:59.820  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.821  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:59.821  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:59.821  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:59.821  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.821  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21bdbe7 removed from the list
,09-09 16:06:59.821  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:59.821  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:59.821  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.821  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.821  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:06:59.821  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4175a6 removed from the list
,09-09 16:06:59.822  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:06:59.822  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ae60df added. We now have 2 listener(s)
09-09 16:06:59.824  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:06:59.825  4378  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 16:06:59.825  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.826  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:59.824  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.827  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:59.827  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:06:59.827  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:59.827  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d612c added. We now have 9 listener(s)
,09-09 16:06:59.827  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:06:59.827  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.827  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:06:59.831  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-09 16:06:59.833  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:59.839  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:59.840  4378  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:06:59.840  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.841  4378  4397 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:06:59.842  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:59.842  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:06:59.842  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:06:59.842  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c55698a added. We now have 3 listener(s)
,09-09 16:06:59.845  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:06:59.845  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.845  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:59.845  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:59.845  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.845  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1422bfb added. We now have 10 listener(s)
09-09 16:06:59.845  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:59.845  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:06:59.846  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:06:59.846  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:06:59.846  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 16:06:59.846  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.847  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:06:59.849  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.850  3984  4036 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:59.850  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:59.854  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:59.855  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:06:59.856  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:06:59.856  4378  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:06:59.856  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.857  4378  4397 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:06:59.859  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:06:59.859  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 16:06:59.860  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:06:59.860  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:59.862  4378  4413 D BtGatt.GattService: registerClient() - UUID=b88fa868-ab75-4745-bc03-8df41be387c7
,09-09 16:06:59.863  4378  4394 D BtGatt.GattService: onClientRegistered() - UUID=b88fa868-ab75-4745-bc03-8df41be387c7, clientIf=5
09-09 16:06:59.863  3984  4181 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:06:59.863  4378  4414 D BtGatt.GattService: start scan with filters
,09-09 16:06:59.865  4378  4394 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:06:59.865  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.867  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:06:59.867  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:06:59.867  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:06:59.867  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:06:59.868  4378  4397 D BtGatt.ScanManager: handling starting scan
,09-09 16:06:59.870  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:06:59.870  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:06:59.870  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:06:59.872  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:06:59.874  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:06:59.874  3984  4036 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 16:06:59.875  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:59.875  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:59.875  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:59.875  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:59.875  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.875  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:59.875  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:59.875  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ae60df removed from the list
,09-09 16:06:59.876  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.876  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d612c removed from the list
,09-09 16:06:59.876  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:59.876  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.876  4378  4394 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:06:59.876  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.876  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 16:06:59.876  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.876  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.876  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.877  4378  4397 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:06:59.877  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.877  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:59.877  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:59.878  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d612c not in the list
,09-09 16:06:59.878  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:06:59.878  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:06:59.878  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:06:59.878  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:06:59.878  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:06:59.879  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:59.879  4378  4414 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:06:59.880  4378  4389 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:06:59.880  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:59.880  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 16:06:59.881  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:06:59.881  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:06:59.881  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 16:06:59.882  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:59.882  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:59.882  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:06:59.882  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:59.883  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.883  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:59.883  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.884  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:59.887  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:59.887  3984  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:59.890  4378  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 16:06:59.890  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.890  4378  4397 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:06:59.890  4378  4397 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:06:59.891  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:59.892  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:59.892  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:06:59.892  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:59.893  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.895  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:06:59.895  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:59.895  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:59.898  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:06:59.898  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:59.899  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.901  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 16:06:59.901  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:59.902  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:59.902  3984  4036 D BluetoothLeScanner: could not find callback wrapper
09-09 16:06:59.902  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:59.902  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.902  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:06:59.902  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.902  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1422bfb removed from the list
09-09 16:06:59.902  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:59.902  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.902  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.903  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:59.903  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c55698a removed from the list
09-09 16:06:59.903  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:06:59.903  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a41f73 added. We now have 2 listener(s)
,09-09 16:06:59.905  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:06:59.905  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.905  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:59.905  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:59.905  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8689e30 added. We now have 9 listener(s)
09-09 16:06:59.905  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:59.906  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:06:59.909  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:06:59.911  4378  4394 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 16:06:59.911  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:59.914  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:59.916  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:59.917  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:06:59.918  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:06:59.918  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dd82e added. We now have 3 listener(s)
09-09 16:06:59.919  4378  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:06:59.919  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.920  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:59.922  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:06:59.922  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.922  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:06:59.923  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:59.923  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.923  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a973fcf added. We now have 10 listener(s)
09-09 16:06:59.923  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:59.923  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:06:59.923  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:06:59.924  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:06:59.924  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.924  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:59.928  3984  4036 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:59.928  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:06:59.929  4378  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:06:59.929  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.930  4378  4397 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:06:59.932  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:59.933  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:59.933  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:06:59.936  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:06:59.936  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:06:59.936  3984  4036 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:06:59.936  3984  4036 D BluetoothAdapter: STATE_ON
,09-09 16:06:59.938  4378  4417 D BtGatt.GattService: registerClient() - UUID=b4d19550-ceac-4fbc-848e-88bb02ee6b3d
,09-09 16:06:59.939  4378  4394 D BtGatt.GattService: onClientRegistered() - UUID=b4d19550-ceac-4fbc-848e-88bb02ee6b3d, clientIf=5
,09-09 16:06:59.939  3984  4181 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:06:59.939  4378  4414 D BtGatt.GattService: start scan with filters
,09-09 16:06:59.942  4378  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 16:06:59.942  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:06:59.942  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.942  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:06:59.942  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 16:06:59.942  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:06:59.942  4378  4397 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:06:59.945  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:06:59.945  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:06:59.945  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:06:59.946  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:06:59.950  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:59.950  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:06:59.951  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:59.951  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:59.951  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.951  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:06:59.951  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:59.951  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a41f73 removed from the list
09-09 16:06:59.951  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:59.951  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8689e30 removed from the list
09-09 16:06:59.951  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:59.951  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.952  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.952  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 16:06:59.952  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.952  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.953  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.953  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:59.953  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.953  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8689e30 not in the list
09-09 16:06:59.953  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:06:59.953  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:06:59.953  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 16:06:59.953  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:06:59.953  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:06:59.954  3984  4036 D BluetoothAdapter: STATE_ON
09-09 16:06:59.954  4378  4394 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:06:59.954  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.955  4378  4417 D BtGatt.GattService: stopScan() - queue size =0
,09-09 16:06:59.956  4378  4414 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:06:59.956  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:06:59.956  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:06:59.956  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:06:59.957  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:06:59.957  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 16:06:59.957  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:59.958  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:06:59.957  4378  4397 D BtGatt.ScanManager: handling starting scan
09-09 16:06:59.958  3984  4036 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:06:59.958  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:59.958  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.960  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:06:59.960  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:06:59.960  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.960  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a973fcf removed from the list
,09-09 16:06:59.960  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:59.960  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.960  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.960  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:06:59.960  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:06:59.960  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.960  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dd82e removed from the list
,09-09 16:06:59.960  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:59.961  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:06:59.961  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d60348 added. We now have 2 listener(s)
,09-09 16:06:59.963  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:59.963  3984  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:06:59.963  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:06:59.963  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:06:59.963  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:59.963  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:06:59.963  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cf85e1 added. We now have 9 listener(s)
,09-09 16:06:59.963  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:59.964  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:06:59.967  4378  4394 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 16:06:59.967  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.967  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.967  4378  4397 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:06:59.967  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:06:59.968  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:06:59.968  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:06:59.968  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:06:59.968  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:06:59.971  3984  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:06:59.971  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:06:59.971  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:06:59.973  4378  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 16:06:59.973  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:06:59.974  4378  4397 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 16:06:59.974  4378  4397 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:06:59.974  3984  3984 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:06:59.974  3984  3984 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:06:59.974  3984  4036 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:06:59.974  3984  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.977  3984  3984 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:06:59.979  3984  4036 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:06:59.979  3984  4036 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:06:59.980  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:06:59.980  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ec0bf4 added. We now have 3 listener(s)
09-09 16:06:59.982  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:06:59.983  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:06:59.983  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:06:59.983  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:06:59.983  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:06:59.983  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd9f1d added. We now have 10 listener(s)
,09-09 16:06:59.983  3984  4036 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:06:59.983  3984  4036 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:06:59.983  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:06:59.983  3984  4036 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:06:59.984  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:06:59.984  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.984  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:06:59.984  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:06:59.984  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d60348 removed from the list
09-09 16:06:59.984  4378  4394 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:06:59.984  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:06:59.984  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.984  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cf85e1 removed from the list
,09-09 16:06:59.985  3984  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:06:59.985  3984  4036 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:06:59.985  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.985  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.985  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.986  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.986  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:59.986  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:59.986  3984  4036 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cf85e1 not in the list
09-09 16:06:59.986  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:06:59.986  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:06:59.987  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:06:59.987  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:06:59.987  3984  4036 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:06:59.987  3984  4036 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd9f1d removed from the list
09-09 16:06:59.987  3984  4036 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:06:59.988  3984  4036 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:06:59.988  3984  4036 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:06:59.988  3984  4036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:06:59.988  3984  4036 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ec0bf4 removed from the list
09-09 16:06:59.989  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 16:06:59.989  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 16:06:59.989  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 16:06:59.989  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:06:59.989  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 16:06:59.989  3984  4036 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
09-09 16:06:59.990  4378  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:06:59.990  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.995  3984  4455 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 479, name: My test thread name),
09-09 16:06:59.995  3984  4455 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 479, thread name: My test thread name)
09-09 16:06:59.995  3984  4455 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 479, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-09 16:06:59.997  4378  4394 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:06:59.997  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:06:59.997  4378  4397 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:07:00.000  3984  4456 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 481, name: My test thread name)
09-09 16:07:00.000  3984  4456 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 481, thread name: My test thread name)
,09-09 16:07:00.000  3984  4456 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 481, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 16:07:00.002  3984  4036 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 16:07:00.002  3984  4036 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 16:07:00.002  3984  4036 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 16:07:00.002  3984  4036 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 16:07:00.002  3984  4036 D com.test.thalitest.ThaliTestRunner: Total duration: 22843 ms,
,09-09 16:07:00.004  4378  4394 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:07:00.004  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:07:00.004  3984  4036 I jxcore-log: Total number of executed tests:  80
09-09 16:07:00.004  3984  4036 I jxcore-log: 
09-09 16:07:00.004  4378  4397 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
09-09 16:07:00.004  3984  4036 I jxcore-log: Number of passed tests:  80
09-09 16:07:00.004  3984  4036 I jxcore-log: 
09-09 16:07:00.004  3984  4036 I jxcore-log: Number of failed tests:  0
09-09 16:07:00.004  3984  4036 I jxcore-log: 
09-09 16:07:00.004  3984  4036 I jxcore-log: Number of ignored tests:  0
09-09 16:07:00.004  3984  4036 I jxcore-log: 
09-09 16:07:00.005  3984  4036 I jxcore-log: Total duration:  22843
09-09 16:07:00.005  3984  4036 I jxcore-log: ,
,09-09 16:07:00.007  3984  4036 I jxcore-log: Unit Test app is loaded
09-09 16:07:00.007  3984  4036 I jxcore-log: 
,09-09 16:07:00.010  4378  4394 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:07:00.010  4378  4394 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:07:00.015  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.015  3984  4036 I jxcore-log: 
,09-09 16:07:00.016  3984  3984 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,09-09 16:07:00.019  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.019  3984  4036 I jxcore-log: 
,09-09 16:07:00.021  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.021  3984  4036 I jxcore-log: 
,09-09 16:07:00.022  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.022  3984  4036 I jxcore-log: 
,09-09 16:07:00.023  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.023  3984  4036 I jxcore-log: 
,09-09 16:07:00.025  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.025  3984  4036 I jxcore-log: 
,09-09 16:07:00.027  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:07:00.027  3984  4036 I jxcore-log: 
,09-09 16:07:00.029  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:07:00.029  3984  4036 I jxcore-log: 
,09-09 16:07:00.030  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.030  3984  4036 I jxcore-log: 
,09-09 16:07:00.031  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.031  3984  4036 I jxcore-log: 
,09-09 16:07:00.033  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.033  3984  4036 I jxcore-log: 
,09-09 16:07:00.034  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 16:07:00.034  3984  4036 I jxcore-log: 
,09-09 16:07:00.036  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:07:00.036  3984  4036 I jxcore-log: 
,09-09 16:07:00.037  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:07:00.037  3984  4036 I jxcore-log: 
,09-09 16:07:00.038  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.038  3984  4036 I jxcore-log: 
,09-09 16:07:00.040  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.040  3984  4036 I jxcore-log: 
,09-09 16:07:00.041  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.041  3984  4036 I jxcore-log: 
,09-09 16:07:00.042  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.042  3984  4036 I jxcore-log: 
,09-09 16:07:00.044  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.044  3984  4036 I jxcore-log: 
,09-09 16:07:00.045  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.045  3984  4036 I jxcore-log: 
,09-09 16:07:00.046  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.046  3984  4036 I jxcore-log: 
,09-09 16:07:00.048  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.048  3984  4036 I jxcore-log: 
,09-09 16:07:00.049  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.049  3984  4036 I jxcore-log: 
,09-09 16:07:00.050  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:07:00.050  3984  4036 I jxcore-log: 
,09-09 16:07:00.051  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:07:00.051  3984  4036 I jxcore-log: 
,09-09 16:07:00.052  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:07:00.052  3984  4036 I jxcore-log: 
,09-09 16:07:00.053  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.053  3984  4036 I jxcore-log: 
,09-09 16:07:00.054  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.054  3984  4036 I jxcore-log: 
09-09 16:07:00.055  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.055  3984  4036 I jxcore-log: 
09-09 16:07:00.055  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.055  3984  4036 I jxcore-log: 
,09-09 16:07:00.056  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.056  3984  4036 I jxcore-log: 
,09-09 16:07:00.056  3984  4036 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:07:00.056  3984  4036 I jxcore-log: 
09-09 16:07:00.059  3984  4036 I jxcore-log: My device name is: motorola-Nexus 6
09-09 16:07:00.059  3984  4036 I jxcore-log: 
,09-09 16:07:00.333  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:07:00.401  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:07:00.477  3984  3984 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:07:01.450   874  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-09 16:07:02.645  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-09 16:07:02.645  3984  4036 I jxcore-log: 
,09-09 16:07:03.100  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-09 16:07:03.100  3984  4036 I jxcore-log: 
,09-09 16:07:03.124  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-09 16:07:03.124  3984  4036 I jxcore-log: 
,09-09 16:07:04.501  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-09 16:07:04.501  3984  4036 I jxcore-log: 
,09-09 16:07:04.741  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-09 16:07:04.741  3984  4036 I jxcore-log: 
,09-09 16:07:04.747  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-09 16:07:04.747  3984  4036 I jxcore-log: 
,09-09 16:07:04.765  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-09 16:07:04.765  3984  4036 I jxcore-log: 
,09-09 16:07:04.771  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-09 16:07:04.771  3984  4036 I jxcore-log: 
,09-09 16:07:05.641  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-09 16:07:05.641  3984  4036 I jxcore-log: 
,09-09 16:07:05.654  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js
09-09 16:07:05.654  3984  4036 I jxcore-log: 
,09-09 16:07:05.833  3984  4036 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-09 16:07:05.833  3984  4036 I jxcore-log: 
,09-09 16:07:06.049  3984  4036 W jxcore-log: !!! js_ReportOverRecursed called !!!
,09-09 16:07:06.109  4458  4036 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
,09-09 16:07:06.110  4458  4036 W google-breakpad: O A arm 04 armv7l 3.10.40-geb6cc9d #1 SMP PREEMPT Wed Apr 20 00:05:01 UTC 2016
09-09 16:07:06.110  4458  4036 W google-breakpad: S 0 99C76300 99C76000 00008000
,09-09 16:07:06.181  4458  4036 W google-breakpad: S 99C76000 2064C7990000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,09-09 16:07:06.181  4458  4036 W google-breakpad: S 99C76180 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BDC07ECBB61862C79980DFCB9FC862C7992862C799C86EAA8C8462C79934122D9500000000000000000000000040B0B2912862C79901000000106FC799F6FFFFFF8CDFCB9F0000000080DFCB9F1862C7990300000008000000403FB79188FFFFFF40B0B29188FFFFFF10C41B9085FFFFFF08B6D29FC06EAA8C00D018AA4863C7990C03CCB600B6D29F9435CBB608B6D29FC06EAA8C5B62C9B6000000006C62C7990100000080DFCB9F8462C799E4A81D959465C799B46EC79980DFCB9F00000000B462C799ACFC1C95C06EAA8CD062C79940B0B29169090000E06C729A10709196DC62C79960EBFD94000000004863C7992C000000F862C799D062C7990700000058DB6D957C06589580DFCB9F0000000085FFFFFF0080BB993463C79970F0FD9400000000F862C79980DFCB9F00000000740658954863C7997C0658953463C799
,09-09 16:07:06.181  4458  4036 W google-breakpad: S 99C76300 07000000000000000000000090B8E0E640C41B9085FFFFFFE01DC19180DFCB9FB863C7996463C7993C63C79985FFFFFF5C63C79970D51C9500000000E01DC191220000002864C7996463C799B863C7997C06589540C41B908463C799887E3E956C09528D000000000000000082FFFFFFB863C7992864C799A863C79980DFCB9FEC63C7996C123795ECC7579558CB579558DB6D95220000006C09528D3CC5AE8C00000000BC63C79940C41B9085FFFFFF80DFCB9F0000000040C41B9085FFFFFF7064C7994065C799C0C36E953864C79900000000010000002864C7991864C7992200000080DFCB9F7C65C799783B3A95B06EAA8CF6FFFFFF8CDFCB9F0000000080DFCB9F5064C799020000007064C799D0CDFD8C88FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFF80DFCB9F000000000000000080DFCB9F01000000A065C799B065C79901000000B06EAA8C070000000700000001000000B0C21B900000000080DFCB9F000000000000000006000000E4C36E95E4C36E95
,09-09 16:07:06.182  4458  4036 W google-breakpad: S 99C76480 06000000C0C36E9500000000FFFFFFFF00000000B86EAA8C22000000B8C21B900700000000000000010000001800C0915050A19181FFFFFFDC64C7993052279507000000B0C21B9080DFCB9F000000001000C091E864C7991C65C79938942795000000000000000000000000DCA4B8945065C799010000000000000050EE538EE01BC191B0C21B9000000000FFFFFFFF5050A19181FFFFFFB865C79980A5B8941066C7992C65C7997865C799000000000000000048A5B8944003000001000000FFFFFFFF81FFFFFFB0C21B9085FFFFFF1000C09185FFFFFFB065C7994049B69188FFFFFF90022E9200000000FFFFFFFFC050A19181FFFFFFB865C799388FD099000000008C65C7998C99D099000000000000000090022E9242020000010000004049B69188FFFFFF00EAB29188FFFFFFB0C21B9085FFFFFF1466C799C050A19190022E9201050000B0C21B9085FFFFFF00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291
,09-09 16:07:06.182  4458  4036 W google-breakpad: S 99C76600 F0D9C19185FFFFFF4466C7995C66C799000000003866C7998C99D099820100006086B691010000000000000082FFFFFFB0C21B9085FFFFFFE466C799C018D991A4252D92010A0000B0C21B9085FFFFFF0000000082FFFFFF6086B69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007C09185FFFFFFF0D9C19185FFFFFF82FFFFFF001B7795F0FBC191BC8F2E8AA000000030BDB2910000000083FFFFFFB0902E8A02000000000000001067C7998C99D09902020000A04CB69102000000A0C6B59188FFFFFFB0C21B9085FFFFFF00A6B58E88FFFFFF8467C7998048ED8DCCD02E8A81060000F0D9C19185FFFFFFB0C21B9085FFFFFFA0C6B59188FFFFFFA04CB69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300006867C7990000000083FFFFFF68000000C0DD2A8FB8C21B900100000030000000C0DD2A8F
,09-09 16:07:06.182  4458  4036 W google-breakpad: S 99C76780 00000000A867C7998C99D09982010000E0F1198E010000000000000082FFFFFFB0C21B9085FFFFFF2C68C7997041ED8D04C92E8A81070000B0C21B9085FFFFFF0000000082FFFFFFE0F1198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF4868C7994068C7993868C799AC68C79978000000C0DD2A8F0000000016EA388F58DB6D9580DFCB9F000000005068C7998C99D0998201000020F2198E010000000000000082FFFFFFB0C21B9085FFFFFFBC68C79998D9E18DE4BE2E8A01060000B0C21B9085FFFFFF0000000082FFFFFF20F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5B391C868C799E068C7990400000060000000C0DD2A8FE058C08D81FFFFFF4C69C799F84FD09900000000E068C7998C99D0998201000040F2198E010000000000000082FFFFFFB0C21B9085FFFFFF4C69C79998D3E18DF0B52E8A01060000B0C21B9085FFFFFF0000000082FFFFFF
,09-09 16:07:06.182  4458  4036 W google-breakpad: S 99C76900 40F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F0ED538E00000000F8128D8F6000000020EE538E04000000B0902E8A5C69C799C8AB0995040000007069C7998C99D0998201000060F2198E010000000000000082FFFFFFF0ED538E88FFFFFFEC69C7999057C08DFCAC2E8A01070000F0ED538E88FFFFFF0000000082FFFFFF60F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013C19185FFFFFFB0C21B9085FFFFFF00000000E069C799DC69C79988FFFFFF70000000C0ED538EE0025191D4881C95000000000000000004000000106AC7998C99D09982010000E0F2198E01000000E05B4B8F88FFFFFF30EA538E88FFFFFF6C6AC7996070888D68A62E8A0105000030EA538E88FFFFFFE05B4B8F88FFFFFFE0F2198E88FFFFFFC0D3C19185FFFFFFE0025191010000009C6AC799B46AC79950000000F0D12A8F0200000070DE84908C6AC79918AB099500000000A06AC7990CB52592820200006023CC8F03000000
09-09 16:07:06.183  4458  4036 W google-breakpad: S 99C76A80 0000000082FFFFFF30EA538E88FFFFFF0000000081FFFFFFE002519188FFFFFF3C6BC799D0AB8C8D0031E59101090000E002519188FFFFFF0000000081FFFFFF30EA538E88FFFFFF0000000082FFFFFF6023CC8F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFA0CBBE8E88FFFFFF0000000082FFFFFF0900000081FFFFFFE002519188FFFFFF30035191000000006C6BC799C0D6B2919000000020C0B291B0902E8A0200000070985F8D81FFFFFF00000000606BC7998C99D09982010000B002B39101000000E002519188FFFFFF6023CC8F88FFFFFFE46BC799289F5F8D38A02E8A810700006023CC8F88FFFFFFE002519188FFFFFFB002B39188FFFFFF3003519188FFFFFFC0D6B29188FFFFFFC0D0B29188FFFFFF0000000082FFFFFF3003519188FFFFFF0000000082FFFFFF086CC799388FD09900000000CC6BC79978000000F0D12A8F00000000EC962E8A420300000300000000000000106CC7998C99D099020200008023CC8F0200000070869F8D88FFFFFF
,09-09 16:07:06.183  4458  4036 W google-breakpad: S 99C76C00 D0CDFD8C88FFFFFFE002519188FFFFFF7C6CC79978925F8DB89B2E8A01060000E002519188FFFFFFD0CDFD8C88FFFFFF70869F8D88FFFFFF8023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFF486CC799D0B0B2918035B49188FFFFFF60000000F0D12A8F8018C09190182D8A85FFFFFF7C6CC79900000000E036B49164232D8A000C0000C023CC8F02000000E036B49188FFFFFFD0CDFD8C88FFFFFFE0EC558E88FFFFFFF0C31B9085FFFFFF9002519188FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFFC6CC79950EB538EE0EC558E8035B49100ADC4908A00000000ED538EF0C31B90E0EC558E88FFFFFF90025191E0EC558E8035B491E0C31B908018C09160ADC49009000000A0A5B58ED0B0B291D0B0B291E0EC558E88FFFFFF090000004011C19109000000E036B491D0CDFD8C00EA538EA0A5B58E88FFFFFF00000000BC9F688D60A1688D000400006036B49101000000E036B49188FFFFFFD0CDFD8C88FFFFFF0000000082FFFFFF982D7795D0CDFD8C
,09-09 16:07:06.183  4458  4036 W google-breakpad: S 99C76D80 D0E9538EA0E9538E0000000087FFFFFFA00FB39170E9538EA0E9538E80A5B58E90C2009280020000A036B491020000000000000082FFFFFFA00FB39188FFFFFF70E9538E88FFFFFFC07ECBB670E9538EE0E8538E40E9538E9CD1B89480020000E036B49100000000E0E8538E88FFFFFF0000000000000000504638908A0000000700000040B0B291F0ACC490E036B49120C8CF9903020000403FB7910100000040B0B29188FFFFFFF0ACC49085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080DFCB9FC07ECBB6D86FC7990100000081FFFFFF306FC7999C6FC799646B0F95403FB7910000000000000000006FC799B46EC79938C7CF9958DB6D9580DFCB9F80E9E3912480C799000000000000000000000000010000000477C79980DFCB9F000100000000000050D0B89400000000403FB7919073C79902000000010000000000000000000000
,09-09 16:07:06.183  4458  4036 W google-breakpad: S 99C76F00 0100000081FFFFFF00000000000000006873C799F6FFFFFF8CDFCB9F0100000080DFCB9F306FC799000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000D86FC79980DFCB9F203E77950052BB9100000000A86EAA8C9C6FC7990F2D55BD0000000080DFCB9FD86FC799A06FC799403FB7910052BB9100000000A86EAA8CC46FC7997C0C2D95000000000000000000000000C07ECBB60100000080DFCB9F9873C799D06FC7994C73C799740D2D9500000000000000009873C79901000000780B6D95010000000052BB91D06FC7990000000000000000901E838DCE1E838D0200000002000000010000000000000010B96C955C0000000600000000000000107FC79900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.184  4458  4036 W google-breakpad: S 99C77080 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000014838D00000000000000000100000002000000E0A1B58E0053BB916574C49F00000000000000000F2D55BD00000000C07ECBB60000000080DFCB9F18621F957071C799EC74C799F80D2D9500000000000000009075C7990000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.184  4458  4036 W google-breakpad: S 99C77200 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BDC07ECBB68873C79980DFCB9F3874C7999873C799A86EAA8CF473C79934122D9500000000000000000000000040B0B2919873C799010000008080C799F6FFFFFF8CDFCB9F0000000080DFCB9F8873C799
09-09 16:07:06.184  4458  4036 W google-breakpad: S 99C77380 0300000008000000403FB79188FFFFFF40B0B29188FFFFFFF0ACC49085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BD0000000080DFCB9F4874C7993874C7994074C7993474C79982FFFFFFA06EAA8C2474C79988FC1C95A06EAA8C4074C79940B0B29188FFFFFFA874C799B874C7999875C799010000005074C799000000008474C79950923E954074C799000000001800000040B0B291403FB79188FFFFFF0000000082FFFFFF01000000A06EAA8C0000000082FFFFFF80DFCB9F0000000074065895B874C799A874C799804DD09A1850D09A80DFCB9F9875C79974065895F474C79908A23595B874C7990C75C799070000004F000000CCC10E8D1C09528D000000001009528D40B0B29188FFFFFF80DFCB9F00000000F0ACC49085FFFFFF80DFCB9F000000000875C799205F59953D09528D2875C7999875C7991875C79980DFCB9F0C75C79922000000804DD09A5C75C7993C123795ECC7579558CB5795
09-09 16:07:06.184  4458  4036 W google-breakpad: S 99C77500 58DB6D95220000001C09528D0CC5AE8C000000002C75C7992200000000000000B076C799000000004475C79964DCF494E075C799B076C799C0C36E95A875C79900000000010000009875C7998875C7992200000080DFCB9FEC76C799783B3A95906EAA8CF6FFFFFF8CDFCB9F0000000080DFCB9FC075C79902000000E075C79980CDFD8C88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080DFCB9F010000001077C7992077C79901000000906EAA8C07000000070000000100000090ABC4900000000080DFCB9F000000000000000006000000E4C36E95E4C36E9506000000C0C36E9500000000FFFFFFFF00000000986EAA8C2200000098ABC4900700000000000000010000001800C0915050A19181FFFFFF4C76C799305227950700000090ABC49080DFCB9F000000001000C0915876C7998C76C79938942795000000000000000000000000DCA4B894C076C7990100000000000000B0E8538EE01BC19190ABC49000000000FFFFFFFF
09-09 16:07:06.184  4458  4036 W google-breakpad: S 99C77680 5050A19181FFFFFF2877C79980A5B8948077C7999C76C799E876C799000000000000000048A5B8944003000001000000FFFFFFFF81FFFFFF90ABC49085FFFFFF1000C09185FFFFFF2077C7994049B69188FFFFFF90022E9200000000FFFFFFFFC050A19181FFFFFF2877C799388FD09900000000FC76C7998C99D099000000000000000090022E9242020000010000004049B69188FFFFFF00EAB29188FFFFFF90ABC49085FFFFFF8477C799C050A19190022E920105000090ABC49085FFFFFF00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291F0D9C19185FFFFFFB477C799CC77C79900000000A877C7998C99D099820100006086B691010000000000000082FFFFFF90ABC49085FFFFFF5478C799C018D991A4252D92010A000090ABC49085FFFFFF0000000082FFFFFF6086B69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
09-09 16:07:06.185  4458  4036 W google-breakpad: S 99C77800 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007C09185FFFFFFF0D9C19185FFFFFF82FFFFFF001B7795F0FBC191BC8F2E8AA000000030BDB2910000000083FFFFFFB0902E8A02000000000000008078C7998C99D09902020000A04CB69102000000A0C6B59188FFFFFF90ABC49085FFFFFF60A5B58E88FFFFFFF478C7998048ED8DCCD02E8A81060000F0D9C19185FFFFFF90ABC49085FFFFFFA0C6B59188FFFFFFA04CB69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000D878C7990000000083FFFFFF68000000C0DD2A8F98ABC4900100000030000000C0DD2A8F000000001879C7998C99D09982010000E0F1198E010000000000000082FFFFFF90ABC49085FFFFFF9C79C7997041ED8D04C92E8A8107000090ABC49085FFFFFF0000000082FFFFFFE0F1198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFB879C799B079C799A879C7991C7AC799
09-09 16:07:06.185  4458  4036 W google-breakpad: S 99C77980 78000000C0DD2A8F0000000016EA388F58DB6D9580DFCB9F00000000C079C7998C99D0998201000020F2198E010000000000000082FFFFFF90ABC49085FFFFFF2C7AC79998D9E18DE4BE2E8A0106000090ABC49085FFFFFF0000000082FFFFFF20F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5B391387AC799507AC7990400000060000000C0DD2A8FE058C08D81FFFFFFBC7AC799F84FD09900000000507AC7998C99D0998201000040F2198E010000000000000082FFFFFF90ABC49085FFFFFFBC7AC79998D3E18DF0B52E8A0106000090ABC49085FFFFFF0000000082FFFFFF40F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000050E8538E00000000F8128D8F6000000080E8538E04000000B0902E8ACC7AC799C8AB099504000000E07AC7998C99D0998201000060F2198E010000000000000082FFFFFF50E8538E88FFFFFF5C7BC7999057C08DFCAC2E8A0107000050E8538E88FFFFFF0000000082FFFFFF
09-09 16:07:06.185  4458  4036 W google-breakpad: S 99C77B00 60F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013C19185FFFFFF90ABC49085FFFFFF00000000507BC7994C7BC79988FFFFFF7000000020E8538E40EC558ED4881C95000000000000000004000000807BC7998C99D09982010000E0F2198E01000000E05B4B8F88FFFFFF90E4538E88FFFFFFDC7BC7996070888D68A62E8A0105000090E4538E88FFFFFFE05B4B8F88FFFFFFE0F2198E88FFFFFFC0D3C19185FFFFFF40EC558E010000000C7CC799247CC79950000000F0D12A8F0200000070DE8490FC7BC79918AB099500000000107CC7990CB52592820200006023CC8F030000000000000082FFFFFF90E4538E88FFFFFF0000000081FFFFFF40EC558E88FFFFFFAC7CC799D0AB8C8D0031E5910109000040EC558E88FFFFFF0000000081FFFFFF90E4538E88FFFFFF0000000082FFFFFF6023CC8F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF30CBBE8E88FFFFFF0000000082FFFFFF0900000081FFFFFF40EC558E88FFFFFF
09-09 16:07:06.185  4458  4036 W google-breakpad: S 99C77C80 90EC558E00000000DC7CC799C0D6B2919000000020C0B291B0902E8A0200000070985F8D81FFFFFF00000000D07CC7998C99D09982010000B002B3910100000040EC558E88FFFFFF6023CC8F88FFFFFF547DC799289F5F8D38A02E8A810700006023CC8F88FFFFFF40EC558E88FFFFFFB002B39188FFFFFF90EC558E88FFFFFFC0D6B29188FFFFFFC0D0B29188FFFFFF0000000082FFFFFF90EC558E88FFFFFF0000000082FFFFFF787DC799388FD099000000003C7DC79978000000F0D12A8F00000000EC962E8A420300000300000000000000807DC7998C99D099020200008023CC8F0200000070869F8D88FFFFFF80CDFD8C88FFFFFF40EC558E88FFFFFFEC7DC79978925F8DB89B2E8A0106000040EC558E88FFFFFF80CDFD8C88FFFFFF70869F8D88FFFFFF8023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFFB87DC799D0B0B2918035B49188FFFFFF60000000F0D12A8F8018C09190182D8A85FFFFFFEC7DC79900000000E036B49164232D8A000C0000C023CC8F02000000
09-09 16:07:06.186  4458  4036 W google-breakpad: S 99C77E00 E036B49188FFFFFF80CDFD8C88FFFFFF60E5558E88FFFFFFD0ACC49085FFFFFFF0EB558E88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF6C7EC799B0E5538E60E5558E8035B491504638908A00000060E7538ED0ACC49060E5558E88FFFFFFF0EB558E60E5558E8035B491C0ACC4908018C091B04638900900000000A5B58ED0B0B291D0B0B29160E5558E88FFFFFF090000004011C19109000000E036B49180CDFD8C60E4538E00A5B58E88FFFFFF00000000BC9F688D60A1688D000400006036B49101000000E036B49188FFFFFF80CDFD8C88FFFFFF0000000082FFFFFF982D779580CDFD8C30E4538E00E4538E0000000087FFFFFFA00FB391D0E3538E00E4538EE0A1B58E90C2009280020000A036B491020000000000000082FFFFFFA00FB39188FFFFFFD0E3538E88FFFFFFC07ECBB6D0E3538E70E3538EA0E3538E9CD1B89480020000E036B4910000000070E3538E88FFFFFF0000000000000000B070578E8A0000000700000040B0B29140463890E036B491
09-09 16:07:06.186  4458  4036 W google-breakpad: S 99C77F80 20C8CF9903020000403FB7910100000040B0B29188FFFFFF4046389085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080DFCB9FC07ECBB64881C7990100000081FFFFFFA080C7990C81C799646B0F95403FB79100000000000000007080C7992480C79938C7CF9958DB6D9580DFCB9F80E9E3919491C799000000000000000000000000010000007488C79980DFCB9F000100000000000050D0B89400000000403FB7910085C799020000000100000000000000000000000100000081FFFFFF0000000000000000D884C799F6FFFFFF8CDFCB9F0100000080DFCB9FA080C7990000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000004881C79980DFCB9F203E77950052BB9100000000886EAA8C0C81C7990F2D55BD0000000080DFCB9F4881C7991081C799403FB7910052BB91
09-09 16:07:06.186  4458  4036 W google-breakpad: S 99C78100 00000000886EAA8C3481C7997C0C2D95000000000000000000000000C07ECBB60100000080DFCB9F0885C7994081C799BC84C799740D2D9500000000000000000885C79901000000780B6D95010000000052BB914081C7990000000000000000901E838DCE1E838D0200000002000000010000000000000010B96C955C00000006000000000000008090C79900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.186  4458  4036 W google-breakpad: S 99C78280 0000000000000000000000000014838D00000000000000000100000002000000C0EF168E0053BB916574C49F00000000000000000F2D55BD00000000C07ECBB60000000080DFCB9F18621F95E082C7995C86C799F80D2D9500000000000000000087C7990000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.186  4458  4036 W google-breakpad: S 99C78400 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BDC07ECBB6F884C79980DFCB9FA885C7990885C799886EAA8C6485C79934122D9500000000000000000000000040B0B2910885C79901000000F091C799F6FFFFFF8CDFCB9F0000000080DFCB9FF884C7990300000008000000403FB79188FFFFFF40B0B29188FFFFFF4046389085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BD0000000080DFCB9FB885C799A885C799B085C799A485C79982FFFFFF806EAA8C9485C79988FC1C95806EAA8CB085C79940B0B29188FFFFFF1886C7992886C799
09-09 16:07:06.187  4458  4036 W google-breakpad: S 99C78580 0887C79901000000C085C79900000000F485C79950923E95B085C799000000001800000040B0B291403FB79188FFFFFF0000000082FFFFFF01000000806EAA8C0000000082FFFFFF80DFCB9F00000000740658952886C7991886C799804DD09A1850D09A80DFCB9F0887C799740658956486C79908A235952886C7997C86C799070000004F000000CCC10E8D7C08528D000000007008528D40B0B29188FFFFFF80DFCB9F000000004046389085FFFFFF80DFCB9F000000007886C799205F59959D08528D9886C7990887C7998886C79980DFCB9F7C86C79922000000804DD09ACC86C7993C123795ECC7579558CB579558DB6D95220000007C08528DDCC4AE8C000000009C86C79922000000000000002088C79900000000B486C79964DCF4945087C7992088C799C0C36E951887C79900000000010000000887C799F886C7992200000080DFCB9F5C88C799783B3A95706EAA8CF6FFFFFF8CDFCB9F0000000080DFCB9F3087C799020000005087C79930CDFD8C88FFFFFF0000000082FFFFFF
09-09 16:07:06.187  4458  4036 W google-breakpad: S 99C78700 0000000000010000220000000000000000000000000000000000000080DFCB9F010000008088C7999088C79901000000706EAA8C070000000700000001000000E04438900000000080DFCB9F000000007C02649006000000E4C36E95E4C36E9506000000C0C36E9500000000FFFFFFFF00000000786EAA8C22000000E84438900700000000000000010000001800C0915050A19181FFFFFFBC87C7993052279507000000E044389080DFCB9F000000001000C091C887C799FC87C79938942795000000000000000000000000DCA4B8943088C799010000000000000040E3538EE01BC191E044389000000000FFFFFFFF5050A19181FFFFFF9888C79980A5B894F088C7990C88C7995888C799000000000000000048A5B8944003000001000000FFFFFFFF81FFFFFFE044389085FFFFFF1000C09185FFFFFF9088C7994049B69188FFFFFF90022E9200000000FFFFFFFFC050A19181FFFFFF9888C799388FD099000000006C88C7998C99D099000000000000000090022E924202000001000000
09-09 16:07:06.187  4458  4036 W google-breakpad: S 99C78880 4049B69188FFFFFF00EAB29188FFFFFFE044389085FFFFFFF488C799C050A19190022E9201050000E044389085FFFFFF00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291F0D9C19185FFFFFF2489C7993C89C799000000001889C7998C99D099820100006086B691010000000000000082FFFFFFE044389085FFFFFFC489C799C018D991A4252D92010A0000E044389085FFFFFF0000000082FFFFFF6086B69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007C09185FFFFFFF0D9C19185FFFFFF82FFFFFF001B7795F0FBC191BC8F2E8AA000000030BDB2910000000083FFFFFFB0902E8A0200000000000000F089C7998C99D09902020000A04CB69102000000A0C6B59188FFFFFFE044389085FFFFFFC0A1B58E88FFFFFF648AC7998048ED8DCCD02E8A81060000
09-09 16:07:06.187  4458  4036 W google-breakpad: S 99C78A00 F0D9C19185FFFFFFE044389085FFFFFFA0C6B59188FFFFFFA04CB69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000488AC7990000000083FFFFFF68000000C0DD2A8FE84438900100000030000000C0DD2A8F00000000888AC7998C99D09982010000E0F1198E010000000000000082FFFFFFE044389085FFFFFF0C8BC7997041ED8D04C92E8A81070000E044389085FFFFFF0000000082FFFFFFE0F1198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF288BC799208BC799188BC7998C8BC79978000000C0DD2A8F0000000016EA388F58DB6D9580DFCB9F00000000308BC7998C99D0998201000020F2198E010000000000000082FFFFFFE044389085FFFFFF9C8BC79998D9E18DE4BE2E8A01060000E044389085FFFFFF0000000082FFFFFF20F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5B391A88BC799C08BC79904000000
09-09 16:07:06.188  4458  4036 W google-breakpad: S 99C78B80 60000000C0DD2A8FE058C08D81FFFFFF2C8CC799F84FD09900000000C08BC7998C99D0998201000040F2198E010000000000000082FFFFFFE044389085FFFFFF2C8CC79998D3E18DF0B52E8A01060000E044389085FFFFFF0000000082FFFFFF40F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E0E2538E00000000F8128D8F6000000010E3538E04000000B0902E8A3C8CC799C8AB099504000000508CC7998C99D0998201000060F2198E010000000000000082FFFFFFE0E2538E88FFFFFFCC8CC7999057C08DFCAC2E8A01070000E0E2538E88FFFFFF0000000082FFFFFF60F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013C19185FFFFFFE044389085FFFFFF00000000C08CC799BC8CC79988FFFFFF70000000B0E2538EC0E4558ED4881C95000000000000000004000000F08CC7998C99D09982010000E0F2198E01000000E05B4B8F88FFFFFF802E298F88FFFFFF4C8DC7996070888D68A62E8A01050000
09-09 16:07:06.188  4458  4036 W google-breakpad: S 99C78D00 802E298F88FFFFFFE05B4B8F88FFFFFFE0F2198E88FFFFFFC0D3C19185FFFFFFC0E4558E010000007C8DC799948DC79950000000F0D12A8F0200000070DE84906C8DC79918AB099500000000808DC7990CB52592820200006023CC8F030000000000000082FFFFFF802E298F88FFFFFF0000000081FFFFFFC0E4558E88FFFFFF1C8EC799D0AB8C8D0031E59101090000C0E4558E88FFFFFF0000000081FFFFFF802E298F88FFFFFF0000000082FFFFFF6023CC8F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF70C9BE8E88FFFFFF0000000082FFFFFF0900000081FFFFFFC0E4558E88FFFFFF10E5558E000000004C8EC799C0D6B2919000000020C0B291B0902E8A0200000070985F8D81FFFFFF00000000408EC7998C99D09982010000B002B39101000000C0E4558E88FFFFFF6023CC8F88FFFFFFC48EC799289F5F8D38A02E8A810700006023CC8F88FFFFFFC0E4558E88FFFFFFB002B39188FFFFFF10E5558E88FFFFFFC0D6B29188FFFFFFC0D0B29188FFFFFF
09-09 16:07:06.188  4458  4036 W google-breakpad: S 99C78E80 0000000082FFFFFF10E5558E88FFFFFF0000000082FFFFFFE88EC799388FD09900000000AC8EC79978000000F0D12A8F00000000EC962E8A420300000300000000000000F08EC7998C99D099020200008023CC8F0200000070869F8D88FFFFFF30CDFD8C88FFFFFFC0E4558E88FFFFFF5C8FC79978925F8DB89B2E8A01060000C0E4558E88FFFFFF30CDFD8C88FFFFFF70869F8D88FFFFFF8023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFF288FC799D0B0B2918035B49188FFFFFF60000000F0D12A8F8018C09190182D8A85FFFFFF5C8FC79900000000E036B49164232D8A000C0000C023CC8F02000000E036B49188FFFFFF30CDFD8C88FFFFFFC07E548E88FFFFFF2046389085FFFFFF70E4558E88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFDC8FC799D02F298FC07E548E8035B491B070578E8A00000090E1538E20463890C07E548E88FFFFFF70E4558EC07E548E8035B491104638908018C0911071578E09000000E0EF168ED0B0B291D0B0B291
09-09 16:07:06.188  4458  4036 W google-breakpad: S 99C79000 C07E548E88FFFFFF090000004011C19109000000E036B49130CDFD8C502E298FE0EF168E88FFFFFF00000000BC9F688D60A1688D000400006036B49101000000E036B49188FFFFFF30CDFD8C88FFFFFF0000000082FFFFFF982D779530CDFD8C202E298FF02D298F0000000087FFFFFFA00FB391C02D298FF02D298FC0EF168E90C2009280020000A036B491020000000000000082FFFFFFA00FB39188FFFFFFC02D298F88FFFFFFC07ECBB6C02D298F602D298F902D298F9CD1B89480020000E036B49100000000602D298F88FFFFFF0000000000000000B03BAD8F8A0000000700000040B0B291A070578EE036B49120C8CF9903020000403FB7910100000040B0B29188FFFFFFA070578E85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080DFCB9FC07ECBB6B892C7990100000081FFFFFF1092C7997C92C799646B0F95403FB79100000000
09-09 16:07:06.188  4458  4036 W google-breakpad: S 99C79180 00000000E091C7999491C79938C7CF9958DB6D9580DFCB9F80E9E39104A3C79900000000000000000000000001000000E499C79980DFCB9F000100000000000050D0B89400000000403FB7917096C799020000000100000000000000000000000100000081FFFFFF00000000000000004896C799F6FFFFFF8CDFCB9F0100000080DFCB9F1092C799000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000B892C79980DFCB9F203E77950052BB9100000000686EAA8C7C92C7990F2D55BD0000000080DFCB9FB892C7998092C799403FB7910052BB9100000000686EAA8CA492C7997C0C2D95000000000000000000000000C07ECBB60100000080DFCB9F7896C799B092C7992C96C799740D2D9500000000000000007896C79901000000780B6D95010000000052BB91B092C7990000000000000000901E838DCE1E838D0200000002000000010000000000000010B96C955C0000000600000000000000F0A1C79900000000
09-09 16:07:06.189  4458  4036 W google-breakpad: S 99C79300 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000014838D00000000000000000100000002000000E0EE168E0053BB916574C49F00000000000000000F2D55BD00000000C07ECBB60000000080DFCB9F18621F955094C799CC97C799F80D2D9500000000000000007098C7990000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.189  4458  4036 W google-breakpad: S 99C79480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.189  4458  4036 W google-breakpad: S 99C79600 0000000000000000000000000F2D55BDC07ECBB66896C79980DFCB9F1897C7997896C799686EAA8CD496C79934122D9500000000000000000000000040B0B2917896C7990100000060A3C799F6FFFFFF8CDFCB9F0000000080DFCB9F6896C7990300000008000000403FB79188FFFFFF40B0B29188FFFFFFA070578E85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000040000000F2D55BD0400000080DFCB9F2897C7991897C7992097C7991497C79982FFFFFF606EAA8C0497C79988FC1C95606EAA8C2097C79940B0B29188FFFFFF8897C7999897C7997898C799010000003097C799000000006497C79950923E952097C799000000001800000040B0B291403FB79188FFFFFF0000000082FFFFFF01000000606EAA8C0000000082FFFFFF80DFCB9F00000000740658959897C7998897C799804DD09A1850D09A80DFCB9F7898C79974065895D497C79908A235959897C799EC97C799070000004F000000CCC10E8D2C08528D
09-09 16:07:06.189  4458  4036 W google-breakpad: S 99C79780 000000002008528D40B0B29188FFFFFF80DFCB9F00000000A070578E85FFFFFF80DFCB9F00000000E897C799205F59954D08528D0898C7997898C799F897C79980DFCB9FEC97C79922000000804DD09A3C98C7993C123795ECC7579558CB579558DB6D95220000002C08528DACC4AE8C000000000C98C79922000000000000009099C799000000002498C79964DCF494C098C7999099C799C0C36E958898C79900000000010000007898C7996898C7992200000080DFCB9FCC99C799783B3A95506EAA8CF6FFFFFF8CDFCB9F0000000080DFCB9FA098C79902000000C098C799E0CCFD8C88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080DFCB9F01000000F099C799009AC79901000000506EAA8C070000000700000001000000309F2F8F0000000080DFCB9F000000000000000006000000E4C36E95E4C36E9506000000C0C36E9500000000FFFFFFFF00000000586EAA8C22000000389F2F8F0700000000000000010000001800C091
09-09 16:07:06.190  4458  4036 W google-breakpad: S 99C79900 5050A19181FFFFFF2C99C7993052279507000000309F2F8F80DFCB9F000000001000C0913899C7996C99C79938942795000000000000000000000000DCA4B894A099C7990100000000000000302D298FE01BC191309F2F8F00000000FFFFFFFF5050A19181FFFFFF089AC79980A5B894609AC7997C99C799C899C799000000000000000048A5B8944003000001000000FFFFFFFF81FFFFFF309F2F8F85FFFFFF1000C09185FFFFFF009AC7994049B69188FFFFFF90022E9200000000FFFFFFFFC050A19181FFFFFF089AC799388FD09900000000DC99C7998C99D099000000000000000090022E9242020000010000004049B69188FFFFFF00EAB29188FFFFFF309F2F8F85FFFFFF649AC799C050A19190022E9201050000309F2F8F85FFFFFF00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291F0D9C19185FFFFFF949AC799AC9AC79900000000889AC7998C99D099820100006086B691010000000000000082FFFFFF
09-09 16:07:06.190  4458  4036 W google-breakpad: S 99C79A80 309F2F8F85FFFFFF349BC799C018D991A4252D92010A0000309F2F8F85FFFFFF0000000082FFFFFF6086B69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007C09185FFFFFFF0D9C19185FFFFFF82FFFFFF001B7795F0FBC191BC8F2E8AA000000030BDB2910000000083FFFFFFB0902E8A0200000000000000609BC7998C99D09902020000A04CB69102000000A0C6B59188FFFFFF309F2F8F85FFFFFFA0EF168E88FFFFFFD49BC7998048ED8DCCD02E8A81060000F0D9C19185FFFFFF309F2F8F85FFFFFFA0C6B59188FFFFFFA04CB69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000B89BC7990000000083FFFFFF68000000C0DD2A8F389F2F8F0100000030000000C0DD2A8F00000000F89BC7998C99D09982010000E0F1198E010000000000000082FFFFFF309F2F8F85FFFFFF7C9CC7997041ED8D
09-09 16:07:06.190  4458  4036 W google-breakpad: S 99C79C00 04C92E8A81070000309F2F8F85FFFFFF0000000082FFFFFFE0F1198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF989CC799909CC799889CC799FC9CC79978000000C0DD2A8F0000000016EA388F58DB6D9580DFCB9F00000000A09CC7998C99D0998201000020F2198E010000000000000082FFFFFF309F2F8F85FFFFFF0C9DC79998D9E18DE4BE2E8A01060000309F2F8F85FFFFFF0000000082FFFFFF20F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5B391189DC799309DC7990400000060000000C0DD2A8FE058C08D81FFFFFF9C9DC799F84FD09900000000309DC7998C99D0998201000040F2198E010000000000000082FFFFFF309F2F8F85FFFFFF9C9DC79998D3E18DF0B52E8A01060000309F2F8F85FFFFFF0000000082FFFFFF40F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D02C298F00000000F8128D8F
09-09 16:07:06.190  4458  4036 W google-breakpad: S 99C79D80 60000000002D298F04000000B0902E8AAC9DC799C8AB099504000000C09DC7998C99D0998201000060F2198E010000000000000082FFFFFFD02C298F88FFFFFF3C9EC7999057C08DFCAC2E8A01070000D02C298F88FFFFFF0000000082FFFFFF60F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013C19185FFFFFF309F2F8F85FFFFFF00000000309EC7992C9EC79988FFFFFF70000000A02C298F207E548ED4881C95000000000000000004000000609EC7998C99D09982010000E0F2198E01000000E05B4B8F88FFFFFF1029298F88FFFFFFBC9EC7996070888D68A62E8A010500001029298F88FFFFFFE05B4B8F88FFFFFFE0F2198E88FFFFFFC0D3C19185FFFFFF207E548E01000000EC9EC799049FC79950000000F0D12A8F0200000070DE8490DC9EC79918AB099500000000F09EC7990CB52592820200006023CC8F030000000000000082FFFFFF1029298F88FFFFFF0000000081FFFFFF207E548E88FFFFFF8C9FC799D0AB8C8D0031E59101090000
09-09 16:07:06.190  4458  4036 W google-breakpad: S 99C79F00 207E548E88FFFFFF0000000081FFFFFF1029298F88FFFFFF0000000082FFFFFF6023CC8F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF00C9BE8E88FFFFFF0000000082FFFFFF0900000081FFFFFF207E548E88FFFFFF707E548E00000000BC9FC799C0D6B2919000000020C0B291B0902E8A0200000070985F8D81FFFFFF00000000B09FC7998C99D09982010000B002B39101000000207E548E88FFFFFF6023CC8F88FFFFFF34A0C799289F5F8D38A02E8A810700006023CC8F88FFFFFF207E548E88FFFFFFB002B39188FFFFFF707E548E88FFFFFFC0D6B29188FFFFFFC0D0B29188FFFFFF0000000082FFFFFF707E548E88FFFFFF0000000082FFFFFF58A0C799388FD099000000001CA0C79978000000F0D12A8F00000000EC962E8A42030000030000000000000060A0C7998C99D099020200008023CC8F0200000070869F8D88FFFFFFE0CCFD8C88FFFFFF207E548E88FFFFFFCCA0C79978925F8DB89B2E8A01060000207E548E88FFFFFFE0CCFD8C88FFFFFF
09-09 16:07:06.191  4458  4036 W google-breakpad: S 99C7A080 70869F8D88FFFFFF8023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFF98A0C799D0B0B2918035B49188FFFFFF60000000F0D12A8F8018C09190182D8A85FFFFFFCCA0C79900000000E036B49164232D8A000C0000C023CC8F02000000E036B49188FFFFFFE0CCFD8C88FFFFFF4077548E88FFFFFF8070578E85FFFFFFD07D548E88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF4CA1C799302A298F4077548E8035B491B03BAD8F8A000000E02B298F8070578E4077548E88FFFFFFD07D548E4077548E8035B4917070578E8018C091103CAD8F0900000040EF168ED0B0B291D0B0B2914077548E88FFFFFF090000004011C19109000000E036B491E0CCFD8CE028298F40EF168E88FFFFFF00000000BC9F688D60A1688D000400006036B49101000000E036B49188FFFFFFE0CCFD8C88FFFFFF0000000082FFFFFF982D7795E0CCFD8CB028298F8028298F0000000087FFFFFFA00FB3915028298F8028298FE0EE168E90C2009280020000A036B49102000000
09-09 16:07:06.191  4458  4036 W google-breakpad: S 99C7A200 0000000082FFFFFFA00FB39188FFFFFF5028298F88FFFFFFC07ECBB65028298FF027298F2028298F9CD1B89480020000E036B49100000000F027298F88FFFFFF000000000000000010A7B0908A0000000700000040B0B291A03BAD8FE036B49120C8CF9903020000403FB7910100000040B0B29188FFFFFFA03BAD8F85FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080DFCB9FC07ECBB628A4C7990100000081FFFFFF80A3C799ECA3C799646B0F95403FB791000000000000000050A3C79904A3C79938C7CF9958DB6D9580DFCB9F80E9E39174B4C7990000000000000000000000000100000054ABC79980DFCB9F0001C7990000000050D0B89400000000403FB791E0A7C7990200000001000000D4302B8D000000000100000081FFFFFF00A8C79900001000B8A7C799F6FFFFFF8CDFCB9F0100000080DFCB9F80A3C7990000000008000000
09-09 16:07:06.191  4458  4036 W google-breakpad: S 99C7A380 3C0082E000000000ACA3C799644B3395000080002000000030A6C799D844BB91000010000100000028A4C79980DFCB9F203E77950052BB9100000000486EAA8CECA3C7990F2D55BD0000000080DFCB9F28A4C799F0A3C799403FB7910052BB9100000000486EAA8C14A4C7997C0C2D950000000090CCFD8C24A4C799C07ECBB60100000080DFCB9FE8A7C79920A4C7999CA7C799740D2D9528A8C799000000E0E8A7C79901000000780B6D95010000000052BB9120A4C799000000000000000564A4C7999C4233950200000038000000C4302B8D7C41339511A4C7993800000028A8C79911A6C7993C000000000000E0C07ECBB630A6C799C8A4C799D844BB9190CCFD8C0000000094302B8D405F3395D8302B8DA4A4C79901000000B4A4C799B4A4C799FFFFFF0001000000C4A4C79908000000DC302B8DB0302B8D44E02E8A50E02E8A7027339528E02E8AF0FFFFFFFFFFFFFF0000000030A6C79944CFD47208B6D29F00302B8D00D018AA48A8C79908B6D29F306EAA8C00D018AA30A6C799
09-09 16:07:06.191  4458  4036 W google-breakpad: S 99C7A500 0C03CCB600B6D29F9435CBB608B6D29F306EAA8C5B62C9B604000000DCA5C799E849109060A5C79954A5C79998AF129544E02E8A54E02E8AF80E238DF80E238D64A5C79948A8C79901000000F80E238D80DFCB9F30A6C79901000000F80E238D80DFCB9F90CCFD8C90CCFD8C0000000084A5C7997C6AFF9460ADC79930A6C79994A5C79974120E9500000000C07ECBB61CB1C799ACE412950000238DC4AF58950D000000648D588D030000000000000000000000505213950000238D6CB25895A0372D8A30A6C799010000000000238DE8A5C799D844BB9190CCFD8CB8C96B9541B0B29184222D8A10000000280000001C0000002C00000000000000F80E238D0D000000648D588D03000000000000000D0000001C223395020000000100000030A6C79900000000000000000000000040A6C799000000000000000000000000000000000000000058A6C799000000000000000000000000000000000000000070A6C799000000000000000000000000000000000000000088A6C79900000000
09-09 16:07:06.192  4458  4036 W google-breakpad: S 99C7A680 000000000000000098A6C799000000000100000000000000A8A6C7990000000000000000000000000800000000000000C0A6C799000000000800000000000000D0A6C79900000000080000000000000008000000000000000800000000000000F0A6C79900000000000000000000000000A7C79900000000000000000500000010A7C7990000000000000000020000000200000000000000306EAA8C010000000100000000000000000000000100000040A7C799000000000000000000000000200000000000000058A7C79900000000200000000000000068A7C799000000002000000005000000010000000500000080A7C79902000000010000000F2D55BDC07ECBB6D8A7C79980DFCB9F88A8C799E8A7C799486EAA8C44A8C79934122D950100000000000000B8A7C79940B0B291E8A7C79901000000D0B4C799F6FFFFFF8CDFCB9F0000000080DFCB9FD8A7C7990300000008000000403FB79188FFFFFF40B0B29188FFFFFFA03BAD8F85FFFFFF00A8C799000000002000000000000000
09-09 16:07:06.192  4458  4036 W google-breakpad: S 99C7A800 10A8C7990000000020000000B0302B8D01342B8D00002B8D00296B950F2D55BD01342B8D80DFCB9F98A8C79988A8C79990A8C79984A8C79982FFFFFF406EAA8C74A8C79988FC1C95406EAA8C90A8C79940B0B29188FFFFFFF8A8C79908A9C799E8A9C79901000000A0A8C79900000000D4A8C79950923E9590A8C799080000001800000040B0B291403FB79188FFFFFF0000000082FFFFFF01000000406EAA8C0000000082FFFFFF80DFCB9F000000007406589508A9C799F8A8C799804DD09A1850D09A80DFCB9FE8A9C7997406589544A9C79908A2359508A9C7995CA9C799070000004F000000CCC10E8DDC07528D00000000D007528D40B0B29188FFFFFF80DFCB9F00000000A03BAD8F85FFFFFF80DFCB9F0000000058A9C799205F5995FD07528D78A9C799E8A9C79968A9C79980DFCB9F5CA9C79922000000804DD09AACA9C7993C123795ECC7579558CB579558DB6D9522000000DC07528D7CC4AE8C000000007CA9C799220000000000000000ABC7990000000094A9C79964DCF494
09-09 16:07:06.192  4458  4036 W google-breakpad: S 99C7A980 30AAC79900ABC799C0C36E95F8A9C7990000000001000000E8A9C799D8A9C7992200000080DFCB9F3CABC799783B3A95306EAA8CF6FFFFFF8CDFCB9F0000000080DFCB9F10AAC7990200000030AAC79990CCFD8C88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080DFCB9F0100000060ABC79970ABC79901000000306EAA8C07,0000000700000001000000403AAD8F0000000080DFCB9F000000000000000006000000E4C36E95E4C36E9506000000C0C36E9500000000FFFFFFFF00000000386EAA8C22000000483AAD8F0700000000000000010000001800C0915050A19181FFFFFF9CAAC7993052279507000000403AAD8F80DFCB9F000000001000C091A8AAC799DCAAC799389427958C13DC89A853D5B4F402CCB6DCA4B89410ABC79901000000A40D488DC027298FE01BC191403AAD8F00000000FFFFFFFF5050A19181FFFFFF78ABC79980A5B894D0ABC799ECAAC79938ABC799000000000000000048A5B8944003000001000000
09-09 16:07:06.192  4458  4036 W google-breakpad: S 99C7AB00 FFFFFFFF81FFFFFF403AAD8F85FFFFFF1000C09185FFFFFF78ABC7994049B69188FFFFFF90022E9200000000FFFFFFFFC050A19181FFFFFF78ABC799388FD099000000004CABC7998C99D099000000000000000090022E9242020000010000004049B69188FFFFFF00EAB29188FFFFFF403AAD8F85FFFFFFD4ABC799C050A19190022E9201050000403AAD8F85FFFFFF00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291F0D9C19185FFFFFF04ACC7991CACC79900000000F8ABC7998C99D099820100006086B691010000000000000082FFFFFF403AAD8F85FFFFFFA4ACC799C018D991A4252D92010A0000403AAD8F85FFFFFF0000000082FFFFFF6086B69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007C09185FFFFFFF0D9C19185FFFFFF82FFFFFF001B7795
09-09 16:07:06.192  4458  4036 W google-breakpad: S 99C7AC80 F0FBC191BC8F2E8AA000000030BDB2910000000083FFFFFFB0902E8A0200000000000000D0ACC7998C99D09902020000A04CB69102000000A0C6B59188FFFFFF403AAD8F85FFFFFFC0EE168E88FFFFFF44ADC7998048ED8DCCD02E8A81060000F0D9C19185FFFFFF403AAD8F85FFFFFFA0C6B59188FFFFFFA04CB69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000028ADC7990000000083FFFFFF68000000C0DD2A8F483AAD8F0100000030000000C0DD2A8F0000000068ADC7998C99D09982010000E0F1198E010000000000000082FFFFFF403AAD8F85FFFFFFECADC7997041ED8D04C92E8A81070000403AAD8F85FFFFFF0000000082FFFFFFE0F1198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF08AEC79900AEC799F8ADC7996CAEC79978000000C0DD2A8F0000000016EA388F58DB6D9580DFCB9F0000000010AEC7998C99D0998201000020F2198E01000000
09-09 16:07:06.193  4458  4036 W google-breakpad: S 99C7AE00 0000000082FFFFFF403AAD8F85FFFFFF7CAEC79998D9E18DE4BE2E8A01060000403AAD8F85FFFFFF0000000082FFFFFF20F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80D5B39188AEC799A0AEC7990400000060000000C0DD2A8FE058C08D81FFFFFF0CAFC799F84FD09900000000A0AEC7998C99D0998201000040F2198E010000000000000082FFFFFF403AAD8F85FFFFFF0CAFC79998D3E18DF0B52E8A01060000403AAD8F85FFFFFF0000000082FFFFFF40F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000003027298F00000000F8128D8F600000006027298F04000000B0902E8A1CAFC799C8AB09950400000030AFC7998C99D0998201000060F2198E010000000000000082FFFFFF3027298F88FFFFFFACAFC7999057C08DFCAC2E8A010700003027298F88FFFFFF0000000082FFFFFF60F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013C19185FFFFFF403AAD8F85FFFFFF
09-09 16:07:06.193  4458  4036 W google-breakpad: S 99C7AF80 00000000A0AFC7999CAFC79988FFFFFF700000000027298FA076548ED4881C95000000000000000004000000D0AFC7998C99D09982010000E0F2198E01000000E05B4B8F88FFFFFF7023298F88FFFFFF2CB0C7996070888D68A62E8A010500007023298F88FFFFFFE05B4B8F88FFFFFFE0F2198E88FFFFFFC0D3C19185FFFFFFA076548E010000005CB0C79974B0C79950000000F0D12A8F0200000070DE84904CB0C79918AB09950000000060B0C7990CB52592820200006023CC8F030000000000000082FFFFFF7023298F88FFFFFF0000000081FFFFFFA076548E88FFFFFFFCB0C799D0AB8C8D0031E59101090000A076548E88FFFFFF0000000081FFFFFF7023298F88FFFFFF0000000082FFFFFF6023CC8F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF90C8BE8E88FFFFFF0000000082FFFFFF0900000081FFFFFFA076548E88FFFFFFF076548E000000002CB1C799C0D6B2919000000020C0B291B0902E8A0200000070985F8D81FFFFFF0000000020B1C799
09-09 16:07:06.193  4458  4036 W google-breakpad: S 99C7B100 8C99D09982010000B002B39101000000A076548E88FFFFFF6023CC8F88FFFFFFA4B1C799289F5F8D38A02E8A810700006023CC8F88FFFFFFA076548E88FFFFFFB002B39188FFFFFFF076548E88FFFFFFC0D6B29188FFFFFFC0D0B29188FFFFFF0000000082FFFFFFF076548E88FFFFFF0000000082FFFFFFC8B1C799388FD099000000008CB1C79978000000F0D12A8F00000000EC962E8A420300000300000000000000D0B1C7998C99D099020200008023CC8F0200000070869F8D88FFFFFF90CCFD8C88FFFFFFA076548E88FFFFFF3CB2C79978925F8DB89B2E8A01060000A076548E88FFFFFF90CCFD8C88FFFFFF70869F8D88FFFFFF8023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFF08B2C799D0B0B2918035B49188FFFFFF60000000F0D12A8F8018C09190182D8A85FFFFFF3CB2C79900000000E036B49164232D8A000C0000C023CC8F02000000E036B49188FFFFFF90CCFD8C88FFFFFFB070548E88FFFFFF803BAD8F85FFFFFF5076548E88FFFFFF0900000081FFFFFF
09-09 16:07:06.193  4458  4036 W google-breakpad: S 99C7B280 0900000081FFFFFF0900000081FFFFFFBCB2C7999024298FB070548E8035B49110A7B0908A0000004026298F803BAD8FB070548E88FFFFFF5076548EB070548E8035B491703BAD8F8018C09170A7B0900900000000EE168ED0B0B291D0B0B291B070548E88FFFFFF090000004011C19109000000E036B49190CCFD8C4023298F00EE168E88FFFFFF00000000BC9F688D60A1688D000400006036B49101000000E036B49188FFFFFF90CCFD8C88FFFFFF0000000082FFFFFF982D779590CCFD8C1023298FE022298F0000000087FFFFFFA00FB391B022298FE022298FE0ED168E90C2009280020000A036B491020000000000000082FFFFFFA00FB39188FFFFFFB022298F88FFFFFF00000000B022298F5022298F8022298F9CD1B89480020000E036B491000000005022298F88FFFFFF88BDC79948000000CCB3C79998BBC7994800000040B0B29100A7B090E036B49120C8CF9903020000403FB7910100000040B0B29188FFFFFF00A7B09085FFFFFF00000000000000000000000000000000
09-09 16:07:06.194  4458  4036 W google-breakpad: S 99C7B400 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080DFCB9FC07ECBB698B5C7990100000081FFFFFFF0B4C7995CB5C799646B0F95403FB7910000000000000000C0B4C79974B4C79938C7CF9958DB6D9580DFCB9F80E9E391DCC5C79900000000000000000000000001000000C4BCC79980DFCB9F0001E38D0000000050D0B89400000000403FB79150B9C7990200000001000000888A5E8D000000000100000081FFFFFF00D018AA987C398D28B9C799F6FFFFFF8CDFCB9F0100000080DFCB9FF0B4C79900000000080000005039E38D3039E38DD88A5E8D9F010000C8805E8D3039E38DA039E38D2A04000048F1EB8C0100000098B5C79980DFCB9F203E77950052BB9100000000286EAA8C5CB5C7990F2D55BD0000000080DFCB9F98B5C79960B5C799403FB7910052BB9100000000286EAA8C84B5C7997C0C2D9500000000E098588D00000000C07ECBB60100000080DFCB9F58B9C79990B5C799
09-09 16:07:06.194  4458  4036 W google-breakpad: S 99C7B580 0CB9C799740D2D95521C838DFB1D838D58B9C79901000000780B6D95010000000052BB9190B5C79900000000001E838D0200000002000000010000000000000010B96C955C0000000600000000000000C8C4C799000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000014838D0000000000000000010000000200000000ED168E0053BB916574C49F00000000000000000F2D55BD
09-09 16:07:06.194  4458  4036 W google-breakpad: S 99C7B700 00000000C07ECBB60000000080DFCB9F18621F9528B7C799A4BAC799F80D2D95000000000000000048BBC79900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000D800AC8CE412AC8C0000000000800000E412AC8C9773C8B6B8B8C79988B8C799E412AC8CA453D5B4A853D5B4E412AC8C
09-09 16:07:06.194  4458  4036 W google-breakpad: S 99C7B880 00000000C375C8B66009D09101000000A40D488DFFFFFFFFAC0B8C8C01000000F80DE48F01000000BC078C90010000009810D091010000001008048D010000006C06388DFFFFFFFFE412AC8CFFFFFFFFA853D5B4FFFFFFFFFC0C808DFFFFFFFF5C0A448DFFFFFFFF7005348D0F2D55BDC07ECBB648B9C79980DFCB9FF8B9C79958B9C799286EAA8CB4B9C79934122D9500000000000000000000000040B0B29158B9C7990100000038C6C799F6FFFFFF8CDFCB9F0000000080DFCB9F48B9C7990300000008000000403FB79188FFFFFF40B0B29188FFFFFF00A7B09085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BD0000000080DFCB9F08BAC799F8B9C79900BAC799F4B9C79982FFFFFF206EAA8CE4B9C79988FC1C95206EAA8C00BAC79940B0B29188FFFFFF68BAC79978BAC79958BBC7990100000010BAC7990000000044BAC79950923E9500BAC799000000001800000040B0B291403FB79188FFFFFF
09-09 16:07:06.194  4458  4036 W google-breakpad: S 99C7BA00 0000000082FFFFFF01000000206EAA8C0000000082FFFFFF80DFCB9F000000007406589578BAC79968BAC799804DD09A1850D09A80DFCB9F58BBC79974065895B4BAC79908A2359578BAC799CCBAC799070000004F000000CCC10E8D8C07528D000000008007528D40B0B29188FFFFFF80DFCB9F0000000000A7B09085FFFFFF80DFCB9F00000000C8BAC799205F5995AD07528DE8BAC79958BBC799D8BAC79980DFCB9FCCBAC79922000000804DD09A1CBBC7993C123795ECC7579558CB579558DB6D95220000008C07528D4CC4AE8C40464B8DECBAC799220000000000000070BCC7990000000004BBC79964DCF494A0BBC79970BCC799C0C36E9568BBC799000000000100000058BBC79948BBC7992200000080DFCB9FACBCC799783B3A95106EAA8C000000003882AF8C000000000000000080BBC7999CBBC799A0BBC799B8BBC799000000000000000082FFFFFF00000000000100002200000000000000000000000000000000BBC79980DFCB9F01000000D0BCC799E0BCC7990106388D
09-09 16:07:06.195  4458  4036 W google-breakpad: S 99C7BB80 106EAA8C070000000700000001000000A0A5B0900000002080DFCB9F4CB5C799987C398D06000000E4C36E95E4C36E9506000000C0C36E9500000000FFFFFFFF00000000086EAA8C22000000A8A5B0900700000000000000010000001800C0915050A191010000000CBCC7993052279507000000A0A5B09080DFCB9F000000001000C09118BCC7994CBCC79938942795F098598D4899598DA099598DDCA4B89480BCC79901000000009B598D2022298FE01BC191A0A5B09000000000FFFFFFFF5050A19101000000E8BCC79980A5B89440BDC7995CBCC799A8BCC799000000000000000048A5B8944003000001000000FFFFFFFF81FFFFFFA0A5B09085FFFFFF1000C09185FFFFFF40A3598D4049B69188FFFFFF90022E9200000000FFFFFFFFC050A19101000000E8BCC799388FD09900000000BCBCC7998C99D099000000000000000090022E9242020000010000004049B69188FFFFFF00EAB29188FFFFFFA0A5B09085FFFFFF44BDC799C050A19190022E9201050000A0A5B09085FFFFFF
09-09 16:07:06.195  4458  4036 W google-breakpad: S 99C7BD00 00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291F0D9C19185FFFFFF74BDC7998CBDC7990000000068BDC7998C99D099820100006086B691010000000000000082FFFFFFA0A5B09085FFFFFF14BEC799C018D991A4252D92010A0000A0A5B09085FFFFFF0000000082FFFFFF6086B69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007C09185FFFFFFF0D9C19185FFFFFF82FFFFFF001B7795F0FBC191BC8F2E8AA000000030BDB2910000000083FFFFFFD020298F030200000000000040BEC7998C99D09902020000A04CB69102000000A0C6B59188FFFFFFA0A5B09085FFFFFFC0ED168E88FFFFFFB4BEC7998048ED8DCCD02E8A81060000F0D9C19185FFFFFFA0A5B09085FFFFFFA0C6B59188FFFFFFA04CB69188FFFFFF0000000082FFFFFF0000000082FFFFFF
09-09 16:07:06.195  4458  4036 W google-breakpad: S 99C7BE80 0000000082FFFFFFC103000098BEC7990000000083FFFFFF68000000C0DD2A8FA8A5B0900100000030000000C0DD2A8F00000000D8BEC7998C99D09982010000E0F1198E010000000000000082FFFFFFA0A5B09085FFFFFF5CBFC7997041ED8D04C92E8A81070000A0A5B09085FFFFFF0000000082FFFFFFE0F1198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF78BFC79970BFC79968BFC799DCBFC79978000000C0DD2A8F0000000016EA388F58DB6D9580DFCB9F0000000080BFC7998C99D0998201000020F2198E010000000000000082FFFFFFA0A5B09085FFFFFFECBFC79998D9E18DE4BE2E8A01060000A0A5B09085FFFFFF0000000082FFFFFF20F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000F8BFC79910C0C7990400000060000000C0DD2A8FE058C08D010000007CC0C799F84FD0990000000010C0C7998C99D0998201000040F2198E01000000
09-09 16:07:06.195  4458  4036 W google-breakpad: S 99C7C000 0000000082FFFFFFA0A5B09085FFFFFF7CC0C79998D3E18DF0B52E8A01060000A0A5B09085FFFFFF0000000082FFFFFF40F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000C021298F00000000F8128D8F60000000F021298F04000000D020298F8CC0C799C8AB099504000000A0C0C7998C99D0998201000060F2198E010000000000000082FFFFFFC021298F88FFFFFF1CC1C7999057C08DFCAC2E8A01070000C021298F88FFFFFF0000000082FFFFFF60F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013C19185FFFFFFA0A5B09085FFFFFF0000000010C1C7990CC1C79988FFFFFF700000009021298F1070548ED4881C9500000000000000000400000040C1C7998C99D09982010000E0F2198E01000000E05B4B8F88FFFFFF905DE88E88FFFFFF9CC1C7996070888D68A62E8A01050000905DE88E88FFFFFFE05B4B8F88FFFFFFE0F2198E88FFFFFFC0D3C19185FFFFFF1070548E01000000CCC1C799E4C1C799
,09-09 16:07:06.195  4458  4036 W google-breakpad: S 99C7C180 50000000F0D12A8F0302000070DE8490BCC1C79918AB099500000000D0C1C7990CB52592820200006023CC8F030000000000000082FFFFFF905DE88E88FFFFFF0000000081FFFFFF1070548E88FFFFFF6CC2C799D0AB8C8D0031E591010900001070548E88FFFFFF0000000081FFFFFF905DE88E88FFFFFF0000000082FFFFFF6023CC8F88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF20C8BE8E88FFFFFF0000000082FFFFFF0900000081FFFFFF1070548E88FFFFFF6070548E000000009CC2C799C0D6B2919000000020C0B291D020298F0302000070985F8D010000000000000090C2C7998C99D09982010000B002B391010000001070548E88FFFFFF6023CC8F88FFFFFF14C3C799289F5F8D38A02E8A810700006023CC8F88FFFFFF1070548E88FFFFFFB002B39188FFFFFF6070548E88FFFFFFC0D6B29188FFFFFFC0D0B29188FFFFFF0000000082FFFFFF6070548E88FFFFFF0000000082FFFFFF38C3C799388FD09900000000FCC2C79978000000F0D12A8F
09-09 16:07:06.196  4458  4036 W google-breakpad: S 99C7C300 00000000EC962E8A42030000030000000000000040C3C7998C99D099020200008023CC8F0200000070869F8D88FFFFFF40CCFD8C88FFFFFF1070548E88FFFFFFACC3C79978925F8DB89B2E8A010600001070548E88FFFFFF40CCFD8C88FFFFFF70869F8D88FFFFFF8023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFFCCB1D099F4C3C799F8C3C799E0A6B09060000000F0D12A8FE0C3C799E0A6B090D020298F0302000000000000D8C3C7998C99D09902020000C023CC8F02000000E036B49188FFFFFF40CCFD8C88FFFFFF10BABA8E88FFFFFF74C4C79988A6A990B4CAB5990109000010BABA8E88FFFFFF40CCFD8C88FFFFFFE036B49188FFFFFFC023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFFE0A6B09085FFFFFFB0BFBA8E88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF60ED168E88FFFFFFD020298F88FFFFFF403FB7910100000090000000605DE88E7CC4C7996CC4C799B02777950000000004000000C4C6C79960A1688D00040000
09-09 16:07:06.200  4458  4036 W google-breakpad: S 99C7C480 6036B49101000000E036B49188FFFFFF40CCFD8C88FFFFFF0000000082FFFFFF982D779540CCFD8C305DE88E005DE88E0000000087FFFFFFA00FB391D05CE88E005DE88E00ED168E90C2009280020000A036B491020000000000000082FFFFFFA00FB39188FFFFFFD05CE88E88FFFFFF28C5C799D05CE88E705CE88EA05CE88E9CD1B89480020000E036B49100000000705CE88E88FFFFFFA0B0E9908A00000007000000B0B0E99080DFCB9F40B0B291C0B32691E036B49120C8CF9903020000403FB7910100000040B0B29188FFFFFFC0B3269185FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080DFCB9FC07ECBB600C7C7990100000081FFFFFF58C6C799C4C6C799646B0F95403FB791000000000000000028C6C799DCC5C79938C7CF9958DB6D9580DFCB9F80E9E39144D7C799000000000000000000000000010000002CCEC79980DFCB9F
09-09 16:07:06.201  4458  4036 W google-breakpad: S 99C7C600 000100000000000050D0B89400000000403FB791B8CAC799020000000100000000000000000000000100000081FFFFFF000000000000000090CAC799F6FFFFFF8CDFCB9F0100000080DFCB9F58C6C79900000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000000C7C79980DFCB9F203E77950052BB9100000000086EAA8CC4C6C7990F2D55BD0000000080DFCB9F00C7C799C8C6C799403FB7910052BB9100000000086EAA8CECC6C7997C0C2D95000000000000000000000000C07ECBB60100000080DFCB9FC0CAC799F8C6C79974CAC799740D2D95521C838DFB1D838DC0CAC79901000000780B6D95010000000052BB91F8C6C79900000000001E838D0200000002000000010000000000000010B96C955C000000060000000000000030D6C7990000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.201  4458  4036 W google-breakpad: S 99C7C780 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000014838D0000000000000000010000000200000000EC168E0053BB916574C49F00000000000000000F2D55BD00000000C07ECBB60000000080DFCB9F18621F9590C8C7990CCCC799F80D2D950000000000000000B0CCC799000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.201  4458  4036 W google-breakpad: S 99C7C900 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BDC07ECBB6B0CAC79980DFCB9F60CBC799C0CAC799086EAA8C1CCBC79934122D950000000000000000
09-09 16:07:06.201  4458  4036 W google-breakpad: S 99C7CA80 0000000040B0B291C0CAC79901000000A0D7C799F6FFFFFF8CDFCB9F0000000080DFCB9FB0CAC7990300000008000000403FB79188FFFFFF40B0B29188FFFFFFC0B3269185FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BD0000000080DFCB9F70CBC79960CBC79968CBC7995CCBC79982FFFFFF006EAA8C4CCBC79988FC1C95006EAA8C68CBC79940B0B29188FFFFFFD0CBC799E0CBC799C0CCC7990100000078CBC79900000000ACCBC79950923E9568CBC799000000001800000040B0B291403FB79188FFFFFF0000000082FFFFFF01000000006EAA8C0000000082FFFFFF80DFCB9F0000000074065895E0CBC799D0CBC799804DD09A1850D09A80DFCB9FC0CCC799740658951CCCC79908A23595E0CBC79934CCC799070000004F000000CCC10E8D3C07528D000000003007528D40B0B29188FFFFFF80DFCB9F00000000C0B3269185FFFFFF80DFCB9F0000000030CCC799205F59955D07528D50CCC799
09-09 16:07:06.201  4458  4036 W google-breakpad: S 99C7CC00 C0CCC79940CCC79980DFCB9F34CCC79922000000804DD09A84CCC7993C123795ECC7579558CB579558DB6D95220000003C07528D1CC4AE8C0000000054CCC7992200000000000000D8CDC799000000006CCCC79964DCF49408CDC799D8CDC799C0C36E95D0CCC7990000000001000000C0CCC799B0CCC7992200000080DFCB9F14CEC799783B3A95F06DAA8C0000000080DFCB9FA0CCC79902000000E8CCC799F0CBFD8C08CDC7999057E88E88FFFFFF0000000082FFFFFF0000000000010000220000000000000000000000000000000000000080DFCB9F0100000038CEC79948CEC79901000000F06DAA8C07000000070000000100000060B226910000000080DFCB9F000000000000000006000000E4C36E95E4C36E9506000000C0C36E9500000000FFFFFFFF00000000F86DAA8C2200000068B226910700000000000000010000001800C0915050A1910100000074CDC799305227950700000060B2269180DFCB9F000000001000C09180CDC799B4CDC79938942795F402CCB6BB74C8B6
09-09 16:07:06.202  4458  4036 W google-breakpad: S 99C7CD80 6009D091DCA4B894E8CDC79901000000AC0B8C8C405CE88EE01BC19160B2269100000000FFFFFFFF5050A1910100000050CEC79980A5B894A8CEC799C4CDC79910CEC799000000000000000048A5B8944003000001000000FFFFFFFF81FFFFFF60B2269185FFFFFF1000C09185FFFFFFA453D5B44049B69188FFFFFF90022E9200000000FFFFFFFFC050A1910100000050CEC799388FD0990000000024CEC7998C99D099000000000000000090022E9242020000010000004049B69188FFFFFF00EAB29188FFFFFF60B2269185FFFFFFACCEC799C050A19190022E920105000060B2269185FFFFFF00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291F0D9C19185FFFFFFDCCEC799F4CEC79900000000D0CEC7998C99D099820100006086B691010000000000000082FFFFFF60B2269185FFFFFF7CCFC799C018D991A4252D92010A000060B2269185FFFFFF0000000082FFFFFF6086B69188FFFFFF0000000082FFFFFF
09-09 16:07:06.202  4458  4036 W google-breakpad: S 99C7CF00 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007C09185FFFFFFF0D9C19185FFFFFF82FFFFFF001B7795F0FBC191BC8F2E8AA000000030BDB2910000000083FFFFFFC05AE88E0302000000000000A8CFC7998C99D09902020000A04CB69102000000A0C6B59188FFFFFF60B2269185FFFFFFE0EC168E88FFFFFF1CD0C7998048ED8DCCD02E8A81060000F0D9C19185FFFFFF60B2269185FFFFFFA0C6B59188FFFFFFA04CB69188FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000000D0C7990000000083FFFFFF68000000C0DD2A8F68B226910100000030000000C0DD2A8F0000000040D0C7998C99D09982010000E0F1198E010000000000000082FFFFFF60B2269185FFFFFFC4D0C7997041ED8D04C92E8A8107000060B2269185FFFFFF0000000082FFFFFFE0F1198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
09-09 16:07:06.202  4458  4036 W google-breakpad: S 99C7D080 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE0D0C799D8D0C799D0D0C79944D1C79978000000C0DD2A8F0000000016EA388F58DB6D9580DFCB9F00000000E8D0C7998C99D0998201000020F2198E010000000000000082FFFFFF60B2269185FFFFFF54D1C79998D9E18DE4BE2E8A0106000060B2269185FFFFFF0000000082FFFFFF20F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000060D1C79978D1C7990400000060000000C0DD2A8FE058C08D01000000E4D1C799F84FD0990000000078D1C7998C99D0998201000040F2198E010000000000000082FFFFFF60B2269185FFFFFFE4D1C79998D3E18DF0B52E8A0106000060B2269185FFFFFF0000000082FFFFFF40F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E05BE88E00000000F8128D8F60000000105CE88E04000000C05AE88EF4D1C799C8AB09950400000008D2C7998C99D0998201000060F2198E010000000000000082FFFFFF
09-09 16:07:06.202  4458  4036 W google-breakpad: S 99C7D200 E05BE88E88FFFFFF84D2C7999057C08DFCAC2E8A01070000E05BE88E88FFFFFF0000000082FFFFFF60F2198E88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013C19185FFFFFF60B2269185FFFFFF0000000078D2C79974D2C79988FFFFFF70000000805BE88E70B9BA8ED4881C95000000000000000004000000A8D2C7998C99D09982010000E0F2198E01000000E05B4B8F88FFFFFFF057E88E88FFFFFF04D3C7996070888D68A62E8A01050000F057E88E88FFFFFFE05B4B8F88FFFFFFE0F2198E88FFFFFFC0D3C19185FFFFFF70B9BA8E0100000034D3C7994CD3C79950000000F0D12A8F0302000070DE849024D3C79918AB09950000000038D3C7990CB52592820200006023CC8F030000000000000082FFFFFFF057E88E88FFFFFF0000000081FFFFFF70B9BA8E88FFFFFFD4D3C799D0AB8C8D0031E5910109000070B9BA8E88FFFFFF0000000081FFFFFFF057E88E88FFFFFF0000000082FFFFFF6023CC8F88FFFFFF0900000084FFFFFF0000000082FFFFFF
09-09 16:07:06.203  4458  4036 W google-breakpad: S 99C7D380 0000000081FFFFFFB0C7BE8E88FFFFFF0000000082FFFFFF0900000081FFFFFF70B9BA8E88FFFFFFC0B9BA8E0000000004D4C799C0D6B2919000000020C0B291C05AE88E0302000070985F8D0100000000000000F8D3C7998C99D09982010000B002B3910100000070B9BA8E88FFFFFF6023CC8F88FFFFFF7CD4C799289F5F8D38A02E8A810700006023CC8F88FFFFFF70B9BA8E88FFFFFFB002B39188FFFFFFC0B9BA8E88FFFFFFC0D6B29188FFFFFFC0D0B29188FFFFFF0000000082FFFFFFC0B9BA8E88FFFFFF0000000082FFFFFFA0D4C799388FD0990000000064D4C79978000000F0D12A8F00000000EC962E8A420300000300000000000000A8D4C7998C99D099020200008023CC8F0200000070869F8D88FFFFFFF0CBFD8C88FFFFFF70B9BA8E88FFFFFF14D5C79978925F8DB89B2E8A0106000070B9BA8E88FFFFFFF0CBFD8C88FFFFFF70869F8D88FFFFFF8023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFFCCB1D0995CD5C79960D5C799A0B3269160000000F0D12A8F
09-09 16:07:06.203  4458  4036 W google-breakpad: S 99C7D500 48D5C799A0B32691C05AE88E030200000000000040D5C7998C99D09902020000C023CC8F02000000E036B49188FFFFFFF0CBFD8C88FFFFFF30B3BA8E88FFFFFFDCD5C79988A6A990B4CAB5990109000030B3BA8E88FFFFFFF0CBFD8C88FFFFFFE036B49188FFFFFFC023CC8F88FFFFFF0000000082FFFFFF0000000082FFFFFFA0B3269185FFFFFF20B9BA8E88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF20EC168E88FFFFFFC05AE88E88FFFFFF403FB7910100000090000000C057E88EE4D5C799D4D5C799B027779500000000040000002CD8C79960A1688D000400006036B49101000000E036B49188FFFFFFF0CBFD8C88FFFFFF0000000082FFFFFF982D7795F0CBFD8C9057E88E6057E88E0000000087FFFFFFA00FB3913057E88E6057E88E00EC168E90C2009280020000A036B491020000000000000082FFFFFFA00FB39188FFFFFF3057E88E88FFFFFF90D6C7993057E88ED056E88E0057E88E9CD1B89480020000E036B49100000000D056E88E88FFFFFF
09-09 16:07:06.203  4458  4036 W google-breakpad: S 99C7D680 60FE04908A0000000700000070FE049080DFCB9F40B0B29190B0E990E036B49120C8CF9903020000403FB7910100000040B0B29188FFFFFF90B0E99085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000080DFCB9FC07ECBB668D8C7990100000081FFFFFFC0D7C7992CD8C799646B0F95403FB791000000000000000090D7C79944D7C79938C7CF9958DB6D9580DFCB9F80E9E391ACE8C7990000000000000000000000000100000094DFC79980DFCB9F000100000000000050D0B89400000000403FB79120DCC799020000000100000000000000000000000100000081FFFFFF0000000000000000F8DBC799F6FFFFFF8CDFCB9F0100000080DFCB9FC0D7C79900000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000068D8C79980DFCB9F203E77950052BB9100000000E86DAA8C
09-09 16:07:06.203  4458  4036 W google-breakpad: S 99C7D800 2CD8C7990F2D55BD0000000080DFCB9F68D8C79930D8C799403FB7910052BB9100000000E86DAA8C54D8C7997C0C2D95000000000000000000000000C07ECBB60100000080DFCB9F28DCC79960D8C799DCDBC799740D2D95521C838DFB1D838D28DCC79901000000780B6D95010000000052BB9160D8C79900000000001E838D0200000002000000010000000000000010B96C955C000000060000000000000098E7C79900000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.204  4458  4036 W google-breakpad: S 99C7D980 0000000000000000000000000000000000000000000000000000000000000000000000000014838D0000000000000000010000000200000060EB168E0053BB916574C49F00000000000000000F2D55BD00000000C07ECBB60000000080DFCB9F18621F95F8D9C79974DDC799F80D2D95000000000000000018DEC7990000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.204  4458  4036 W google-breakpad: S 99C7DB00 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F2D55BDC07ECBB618DCC79980DFCB9FC8DCC79928DCC799E86DAA8C84DCC79934122D9500000000000000000000000040B0B29128DCC7990100000008E9C799F6FFFFFF8CDFCB9F0000000080DFCB9F18DCC7990300000008000000403FB79188FFFFFF40B0B29188FFFFFF90B0E99085FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000040000000F2D55BD0400000080DFCB9FD8DCC799C8DCC799D0DCC799C4DCC79982FFFFFFE06DAA8C
09-09 16:07:06.204  4458  4036 W google-breakpad: S 99C7DC80 B4DCC79988FC1C95E06DAA8CD0DCC79940B0B29188FFFFFF38DDC79948DDC79928DEC79901000000E0DCC7990000000014DDC79950923E95D0DCC799000000001800000040B0B291403FB79188FFFFFF0000000082FFFFFF01000000E06DAA8C0000000082FFFFFF80DFCB9F000000007406589548DDC79938DDC799804DD09A1850D09A80DFCB9F28DEC7997406589584DDC79908A2359548DDC7999CDDC799070000004F000000CCC10E8DEC06528D00000000E006528D40B0B29188FFFFFF80DFCB9F0000000090B0E99085FFFFFF80DFCB9F0000000098DDC799205F59950D07528DB8DDC79928DEC799A8DDC79980DFCB9F9CDDC79922000000804DD09AECDDC7993C123795ECC7579558CB579558DB6D9522000000EC06528DECC3AE8C00000000BCDDC799220000000000000040DFC79900000000D4DDC79964DCF49470DEC79940DFC799C0C36E9538DEC799000000000100000028DEC79918DEC7992200000080DFCB9F7CDFC799783B3A95D06DAA8CFFFFFFFF3015FC8EFFFFFFFF
09-09 16:07:06.204  4458  4036 W google-breakpad: S 99C7DE00 C006888E50DEC7998C13608E70DEC79968074C8EFFFFFFFF0000000082FFFFFF000000000001000022000000000000000000000000000000005AD5B480DFCB9F01000000A0DFC799B0DFC79901000000D06DAA8C070000000700000001000000203F9D900000000080DFCB9F000000000000000006000000E4C36E95E4C36E9506000000C0C36E9500000000FFFFFFFF00000000D86DAA8C22000000283F9D900700000000000000010000001800C0915050A19101000000DCDEC7993052279507000000203F9D9080DFCB9F000000001000C091E8DEC7991CDFC79938942795F402CCB6BB74C8B66009D091DCA4B89450DFC79901000000000CA48DA056E88EE01BC191203F9D9000000000FFFFFFFF5050A19101000000B8DFC79980A5B89410E0C7992CDFC79978DFC799000000000000000048A5B8944003000001000000FFFFFFFF81FFFFFF203F9D9085FFFFFF1000C09185FFFFFFA453D5B44049B69188FFFFFF90022E9200000000FFFFFFFFC050A19101000000B8DFC799388FD099
09-09 16:07:06.204  4458  4036 W google-breakpad: S 99C7DF80 000000008CDFC7998C99D099000000000000000090022E9242020000010000004049B69188FFFFFF00EAB29188FFFFFF203F9D9085FFFFFF14E0C799C050A19190022E9201050000203F9D9085FFFFFF00EAB29188FFFFFF4049B69188FFFFFF0000000082FFFFFF00000000E80CE18C40020000000000005000000030BDB291
09-09 16:07:06.204  4458  4036 W google-breakpad: C 060000400040BB99000000003C63C799B863C7991063C7996463C79980DFCB9F3C63C79940C41B9085FFFFFF804DD09A3463C799F862C7990063C799C8D01C95CCD01C9510000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-09 16:07:06.205  4458  4036 W google-breakpad: M B6F10000 00000000 00005000 E72F8FF84F6E260968CCE78B856F06B70 app_process32
09-09 16:07:06.205  4458  4036 W google-breakpad: M 94C85000 00000000 00A66000 886ECA16DD42F6E0428F775A7DA9BFB00 libjxcore.so
09-09 16:07:06.205  4458  4036 W google-breakpad: M A2526000 007F2000 01AE1000 488126E5C3908224A6BF664CC97A94320 libwebviewchromium.so
09-09 16:07:06.205  4458  4036 W google-breakpad: M A8926000 00000000 00006000 0D31362517BA6979AC917A35D240E1210 libwebviewchromium_loader.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A89CA000 00000000 00005000 590854A6A5B5D59683870D00EAE455310 libjnigraphics.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A89CF000 00000000 0000A000 4AE1FB560051D628B937E5D0F75C69F30 libcompiler_rt.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A89D9000 00000000 00011000 4CBE9A6CCCBDC8B3EF8B751BC123CEE50 libandroid.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A89EA000 00000000 0000C000 AFC34749768B41E8D431AF946E23577B0 libqservice.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A89F6000 00000000 0000B000 356C1D2029892384AFE121956A0BB4EA0 libqdutils.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A8A01000 00000000 00005000 95E7634C1A490462E66752EC8939C4530 libqdMetaData.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A8A06000 00000000 00008000 9997EA703403C3035DE00C7EE7880E430 libmemalloc.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A8A0E000 00000000 00008000 3FE99556F2945012B0CB1BE7C353A6540 gralloc.msm8084.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A8A16000 00000000 0000C000 A1BCE730F0644DAE1C5CBC146CD02BD90 eglSubDriverAndroid.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A8A22000 00000000 00027000 2A6DCFEF23E3A32055F90972FCABFED60 libGLESv1_CM_adreno.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A8A49000 00000000 0073D000 2003920CF0749EC2675D7EE282DE502B0 libllvm-glnext.so
09-09 16:07:06.206  4458  4036 W google-breakpad: M A9197000 00000000 004AD000 3082CAE2C0BC6E87686AEAA07100FEDE0 libGLESv2_adreno.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M A9646000 00000000 0003D000 44E63552D97113055F6017F152FAF0340 libgsl.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M A9683000 00000000 00007000 417C9A0548EF994318FDD8293BD2B4A90 libadreno_utils.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M A968C000 00000000 00013000 B4DF6A0A447291C436FE548566C498C00 libEGL_adreno.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB117000 00000000 0001B000 B0EFA02804790BBB6DE8B2B9095BE9CB0 libkeymaster1.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB132000 00000000 0000B000 D13E1014D51DECF5BF9D21E7C67666130 libkeymaster_messages.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB13D000 00000000 00017000 6658C7A49E3552941CE5496BFD2B34980 libsoftkeymasterdevice.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB154000 00000000 0000E000 25D7B988B89B18BC0429BB562FA2DE990 libkeystore_binder.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB162000 00000000 00006000 B33B16D8A7ED9B8FFB7AA215D6923C4B0 libkeystore-engine.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB168000 00000000 00018000 CEF05C42255586B6905B0AF681C33D8C0 libjavacrypto.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB1C0000 00000000 00010000 0C521B6A6E9E39A0E22193BB5D5525130 libstagefright_amrnb_common.so
09-09 16:07:06.207  4458  4036 W google-breakpad: M AB1D0000 00000000 0002C000 582DF60B6AA35307BD7198E3A18119AB0 libexif.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M AB1FC000 00000000 0000D000 7CD678568D893C8FE9A4676BCD58F2AD0 libjhead.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M AB20A000 00000000 00018000 ADA21AF62918F8A878B3FE4F2F0456580 libmtp.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M AB222000 00000000 00048000 0262207412DD5679BF20EB25407B7B440 libmedia_jni.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M AF051000 00000000 00005000 B37EB6398BB0DBE353FE8B1F1DEAB2EB0 memtrack.msm8084.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M B06C6000 00000000 00036000 E15D31AAB91199642EB180D3D4160C520 libjavacore.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M B3654000 00000000 00007000 79903F128710C73A4159E0E685663A550 libwebviewchromium_plat_support.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M B4825000 00000000 00459000 D1BC38C6D191DBFC4B3B8BE9676A2FBB0 libart.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M B4D8C000 00000000 00005000 68126D6F94C506C8BE6DAA402968ABD50 libsigchain.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M B4DB4000 00000000 00A5C000 0B64AEBAA12EA3FC8CB4E80A5310D9A20 libLLVM.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M B5819000 00000000 00038000 EB0128750F7A47E1274CC11D426A63840 libbcinfo.so
09-09 16:07:06.208  4458  4036 W google-breakpad: M B5851000 00000000 0005B000 8D9A857B04F62EBCFEC94FC226C49F600 libbcc.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B58AC000 00000000 0000E000 BD9845C69DC7ADC5D6D7E1756D34DD830 libcommon_time_client.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B58BB000 00000000 0001A000 9AC4BF2FD171753488B9C5DB621A9A240 libprotobuf-cpp-lite.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B58D5000 00000000 00009000 9B164CEF29D3AA5EAF47FA86862586FF0 libstagefright_avc_common.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B58DE000 00000000 00005000 4AA290A61993A8A5677655D665763B3D0 libstagefright_enc_common.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B58E3000 00000000 00007000 5146A8AEEE822B0CE87F523ABAE749F50 libpowermanager.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B58EA000 00000000 0001F000 EF15E47D9893659F6C584D4542F099490 libvorbisidec.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B5909000 00000000 00007000 9C90BE63E61A2127D39B214E6F43AF350 libstagefright_yuv.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B5911000 00000000 00032000 C3AC584E1FF634156E2797138D35375E0 libstagefright_omx.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B5943000 00000000 0003D000 B85FA71D8415B28DE38A933B1508D9F00 libopus.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B5980000 00000000 0000A000 5BEFFA75C748ED7D23421EF091D1F1300 libmediautils.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B598A000 00000000 0001A000 64DF194390054DFAFF82926D89B359340 libdrmframework.so
09-09 16:07:06.209  4458  4036 W google-breakpad: M B59A4000 00000000 00021000 A395A730CEF4C5A1BB47058DE0D9186E0 libRScpp.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B59C5000 00000000 00042000 70A461E7FEC54E6D7E1E5C66F936CE350 libRS.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5A07000 00000000 00009000 FDC63F080EB6155F934F885DEB37E94E0 libspeexresampler.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5A10000 00000000 0000B000 FFD2B97AE5B754AC2E9678225D23B75A0 libnbaio.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5A1B000 00000000 00014000 669F5236C39ADF5E46701FF6C9F768980 libpcre.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5A31000 00000000 00007000 21F0774A2FE026AA52F7480655D27ABE0 libwpa_client.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5A38000 00000000 00071000 C8703400FE46F435C2134FB0F3FDE9390 libGLES_trace.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5AA9000 00000000 00067000 1821F1842FA60DF842F94DF364C495A10 libft2.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5B10000 00000000 00027000 C5A689AFC30DE04B5E7E5ACBF12CA9330 libpng.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5B37000 00000000 00005000 E0AD90DEBEAFB376EBAA5415267856B40 libsync.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5B3C000 00000000 00007000 F5424CDA56569E38CF2903ECFAFF296E0 libstdc++.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5B43000 00000000 00012000 B4E430E8258C544A786360668D84BE8B0 libunwind.so
09-09 16:07:06.210  4458  4036 W google-breakpad: M B5B9B000 00000000 0000B000 96BB8488669F21FEDA8649403EB8BB0E0 libbase.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5BA6000 00000000 00007000 D32E249CC58B3A22906A78EDFDD545460 libeffects.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5BAE000 00000000 00006000 1964BC7CB1EF496E207C18FC55A57E6C0 libstagefright_http_support.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5BB4000 00000000 0001B000 4E010519E1AA1D9D10F586E0C0490F120 libstagefright_foundation.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5BCF000 00000000 0015B000 009817DD6F2FD8255E5AAE0FDE05646B0 libstagefright.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5D2A000 00000000 00070000 4054B4690025F8746C0DC28CC9D69D870 libhwui.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5D9A000 00000000 00005000 9CA9EF8816A2E0C106C15197423A91AE0 libradio_metadata.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5D9F000 00000000 00006000 F1863EB76C05E59645A8AA848D1624570 libnativebridge.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5DA5000 00000000 00006000 1D210F6A59079D7FD7F258724A88DEA70 libprocessgroup.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5DAB000 00000000 00011000 FDCAD8835C0C336BEB30CF765069FC3A0 libminikin.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5DBC000 00000000 0000E000 238BED0ADF305646BB994A7A676D0A1E0 libsoundtrigger.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5DCB000 00000000 0000E000 00FDCB77534A86A2594207ABA92E7FBF0 libradio.so
09-09 16:07:06.211  4458  4036 W google-breakpad: M B5DD9000 00000000 00006000 BBCF64A69A9F42E7BC0E0BD423E728790 libnetd_client.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B5DDF000 00000000 00010000 727E80AEB01F5239858F79470BB43E850 libimg_utils.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B5DEF000 00000000 00420000 2D9D72FD541F8A7DFBF9302532B5F3870 libpdfium.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B6210000 00000000 00009000 25B29975558839100CC6E366D29212350 libaudioutils.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B6219000 00000000 0001D000 DFED0D6F37875A07335517F4E69925120 libz.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B6237000 00000000 0004E000 66D92DD691765147492F9C21B6AD68960 libharfbuzz_ng.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B6285000 00000000 00007000 9008C23BFACF1EF1DDF142956BF976490 libusbhost.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B628C000 00000000 0003A000 2D00674AA1DD3C58C05B175DD18EE6050 libjpeg.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B62C7000 00000000 000AD000 A52E62FD0AC67AE14A01E7E4847F17620 libmedia.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B6374000 00000000 0017F000 14D5DC468D2218AA5F70C2F6FC6EBBF90 libicui18n.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B64F3000 00000000 00123000 0990D8BD31465D945F9282189239AB8F0 libicuuc.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B661A000 00000000 00026000 C4AA0ABF6C41A8583C0E373BD8CA4EE70 libssl.so
09-09 16:07:06.212  4458  4036 W google-breakpad: M B6640000 00000000 0009D000 A14F571CD9F3F8B6362ACC34BB5E42CA0 libcrypto.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B66DD000 00000000 00056000 23B95E0161A14BC00A49FE4C0126E1CF0 libsonivox.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6738000 00000000 00011000 87F28481D7D1980E2971DFAD611952AA0 libselinux.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6749000 00000000 00008000 4E213F2F80F006F539A0A0DBEC2228870 libhardware_legacy.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6752000 00000000 00005000 4025C8440BDADD37826842A415EF9BFF0 libhardware.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6757000 00000000 00006000 0CBDCDD7DFB535EB3876F8035637EAC00 libETC1.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B675D000 00000000 0000F000 A7B07D10AF426644931390FF2ABC2FEC0 libGLESv2.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B676C000 00000000 0000A000 1B33374FB686F15B59530546D8DB39640 libGLESv1_CM.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6776000 00000000 00068000 DAD11DC7527BFB7648299C3DE956986E0 libEGL.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B67E1000 00000000 00065000 E94A253EBAA34A7F995352FCEE8DD0D50 libsqlite.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6847000 00000000 0026E000 71785D4C7316B73D74AB9E39653907830 libskia.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6AB9000 00000000 0000A000 306A2E96AB94641A8076D9195DA933FF0 libcamera_metadata.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6AC3000 00000000 0002D000 7CA8B61C54BAAABF07F3C7847D490E9F0 libcamera_client.so
09-09 16:07:06.213  4458  4036 W google-breakpad: M B6AF0000 00000000 00040000 6C63D1A1ED4626296733EE132307BF6E0 libinputflinger.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6B30000 00000000 0001F000 112B3314840A32B638874B51553126190 libinput.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6B4F000 00000000 0005A000 D55348C7DD771E9409BFBF09AB5AAD720 libgui.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6BA9000 00000000 00010000 10F3AFD84F2FA6D8D59A78E2331D8AC50 libui.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6BB9000 00000000 00009000 8AAEFDEA9747BCF61A977E5DDA0D22620 libnetutils.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6BC2000 00000000 00009000 6C034766ACADC7459DB1EE108B8DDDC70 libnativehelper.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6BCB000 00000000 00017000 410352CE283FD8305E8A2FD783B3C8160 libexpat.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6BE2000 00000000 0002A000 41777DBC877E41A9712DDD4792610E7A0 libandroidfw.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6C0C000 00000000 00005000 EC03C38C8A2A3C11A25493EEEE8E58C20 libmemtrack.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6C11000 00000000 0000B000 6AC6874E2835174DF0B2E6A2BB3511ED0 libbacktrace.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6C1C000 00000000 00022000 771243F4B38A04911D7E2EFFC103E81F0 libm.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6C3E000 00000000 00079000 C45DDC3AA3778947F27583335C11C7260 libc.so
09-09 16:07:06.214  4458  4036 W google-breakpad: M B6CC1000 00000000 0008E000 4F01D021AD7772AE25722B88EF500DF60 libc++.so
09-09 16:07:06.215  4458  4036 W google-breakpad: M B6D50000 00000000 0002D000 C02C38CB58D679FECB52E59A954B4AAD0 libwilhelm.so
09-09 16:07:06.215  4458  4036 W google-breakpad: M B6D7D000 00000000 000DC000 ACD6E6927F2247CE8E5F68E6F5579F0E0 libandroid_runtime.so
09-09 16:07:06.215  4458  4036 W google-breakpad: M B6E5E000 00000000 0002E000 1E5AD4B0BC139C0D5814F52EEC059E2E0 libbinder.so
09-09 16:07:06.215  4458  4036 W google-breakpad: M B6E8C000 00000000 0000A000 F2FDFCED2E85559AC020655D564D0FFC0 liblog.so
09-09 16:07:06.215  4458  4036 W google-breakpad: M B6E96000, 00000000 0001B000 4E3DF0460B95A69E7A1D4ABE2D8C0A690 libutils.so
09-09 16:07:06.215  4458  4036 W google-breakpad: M B6EB1000 00000000 00011000 78F0BD9C3BF5DE7183A84BD26875408C0 libcutils.so
09-09 16:07:06.215  4458  4036 W google-breakpad: M B6EEE000 00000000 00020000 C98C597B4AE800CFB3F0589DF3EDED980 linker
09-09 16:07:06.215  4458  4036 W google-breakpad: -----END BREAKPAD MICRODUMP-----
09-09 16:07:06.253  3984  4036 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
09-09 16:07:06.253  3984  4036 W google-breakpad: Chrome build fingerprint:
09-09 16:07:06.253  3984  4036 W google-breakpad: 0.0.1
09-09 16:07:06.253  3984  4036 W google-breakpad: 19
09-09 16:07:06.253  3984  4036 W google-breakpad: 6ec9b36e-71c4-4d7b-882c-6b145c858100
09-09 16:07:06.254  3984  4036 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
09-09 16:07:06.254  3984  4036 E chromium: ### WebView Version 44.0.2403.117 (code 246011700)
--------- beginning of crash
09-09 16:07:06.255  3984  4036 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 4036 (Thread-370)
,09-09 16:07:06.368   374   374 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,09-09 16:07:06.369   374   374 F DEBUG   : Build fingerprint: 'google/shamu/shamu:6.0.1/MOB30M/2862625:user/release-keys'
,09-09 16:07:06.369   374   374 F DEBUG   : Revision: '0'
,09-09 16:07:06.369   374   374 F DEBUG   : ABI: 'arm'
,09-09 16:07:06.370   374   374 F DEBUG   : pid: 3984, tid: 4036, name: Thread-370  >>> com.test.thalitest <<<
,09-09 16:07:06.371   374   374 F DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,09-09 16:07:06.404   374   374 F DEBUG   :     r0 99bb4000  r1 00000000  r2 99c7633c  r3 99c763b8
,09-09 16:07:06.405   374   374 F DEBUG   :     r4 99c76310  r5 99c76364  r6 9fcbdf80  r7 99c7633c
,09-09 16:07:06.405   374   374 F DEBUG   :     r8 901bc440  r9 ffffff85  sl 9ad04d80  fp 99c76334
,09-09 16:07:06.405   374   374 F DEBUG   :     ip 99c762f8  sp 99c76300  lr 951cd0c8  pc 951cd0cc  cpsr 200f0010
09-09 16:07:06.410   374   374 F DEBUG   : 
09-09 16:07:06.410   374   374 F DEBUG   : backtrace:
09-09 16:07:06.410   374   374 F DEBUG   :     #00 pc 005480cc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
09-09 16:07:06.410   374   374 F DEBUG   :     #01 pc 0054856c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
09-09 16:07:06.410   374   374 F DEBUG   :     #02 pc 00762e84  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,09-09 16:07:06.689   874  1314 D ConnectivityService: handlePromptUnvalidated 102
,09-09 16:07:07.180   374   374 F DEBUG   : 
09-09 16:07:07.180   374   374 F DEBUG   : Tombstone written to: /data/tombstones/tombstone_04
,09-09 16:07:07.180   374   374 E DEBUG   : AM write failed: Broken pipe
,09-09 16:07:07.182   874   890 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,09-09 16:07:07.198   874  4459 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-09 16:07:07.201   278   278 E lowmemorykiller: Error writing /proc/3984/oom_score_adj; errno=22
,09-09 16:07:07.279   874  2044 D GraphicsStats: Buffer count: 2
09-09 16:07:07.280   874  2072 I WindowState: WIN DEATH: Window{d62ee7c u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 16:07:07.281   874  1313 D WifiService: Client connection lost with reason: 4
,09-09 16:07:07.317   874  1986 I ActivityManager: Process com.test.thalitest (pid 3984) has died
,09-09 16:07:07.315   390   390 I Zygote  : Process 3984 exited due to signal (11)
,09-09 16:07:07.349   874  1987 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3984 uid 10000
09-09 16:07:07.350  1896  1896 I Keyboard.Facilitator: onFinishInput()
,09-09 16:07:16.685  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:16.765  1504  4462 I VacuumService: Vacuum at: now=1473430036765 tag=VacuumService
,09-09 16:07:16.879  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:17.078  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:17.089  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:17.206  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 16:07:17.206  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 16:07:17.207  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:07:17.207  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:17.243  3712  3712 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 16:07:17.244  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 16:07:17.247  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 16:07:17.283  1504  4463 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 16:07:17.293  1504  4463 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 16:07:17.343  1504  4463 W Uploader:  no longer exists, so no auth token.
,09-09 16:07:18.634  1504  4463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-09 16:07:18.635  1504  4463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-09 16:07:18.635  1504  4463 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:07:18.635  1504  4463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:18.663  1504  4463 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 16:07:18.663  1504  4463 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 16:07:18.663  1504  4463 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 16:07:19.099  1504  4463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 16:07:19.099  1504  4463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 16:07:19.099  1504  4463 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:07:19.099  1504  4463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:19.138  1504  4463 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 16:07:19.138  1504  4463 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 16:07:19.138  1504  4463 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 16:07:19.930  1504  4463 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 16:07:19.930  1504  4463 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 16:07:19.930  1504  4463 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:07:19.930  1504  4463 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:19.958  1504  4463 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 16:07:19.958  1504  4463 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 16:07:19.958  1504  4463 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 16:07:28.955  4273  4477 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:07:28.994  4273  4478 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:07:29.005  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:29.007  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:29.025  1504  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:07:29.025  1504  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 16:07:29.025  1504  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:07:29.025  1504  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:29.045  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:29.046  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:29.079  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:07:29.079  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:07:29.080  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:07:29.080  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:29.093  4273  4478 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:07:29.094  4273  4477 E BooksSync: Soft error
09-09 16:07:29.094  4273  4477 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:07:29.094  4273  4477 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:07:29.094  4273  4477 E BooksSync: Sync error
09-09 16:07:29.094  4273  4477 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:07:29.094  4273  4477 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:07:29.094  4273  4477 I BooksSync: Finished books sync
,09-09 16:07:29.097   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 179468, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:07:29.102  3793  4476 V KeepSync: Connecting to GoogleApiClient
,09-09 16:07:29.103   874  2044 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:07:29.136  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:29.137  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:29.161  1504  3190 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:07:29.161  1504  3190 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:07:29.161  1504  3190 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:07:29.161  1504  3190 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:29.185  1714  4479 V BaseAuthAsyncOperation: access token request failed
,09-09 16:07:29.186  3793  4476 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:07:29.235  1504  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 16:07:29.235  1504  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:07:29.235  1504  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:07:29.235  1504  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:29.252  3793  4476 E KeepSync: IOException
09-09 16:07:29.252  3793  4476 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:07:29.252  3793  4476 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:07:29.252  3793  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:07:29.252  3793  4476 E KeepSync: 	... 10 more
09-09 16:07:29.252  3793  4476 W KeepSync: Sync result 2
,09-09 16:07:29.270   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 178782, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:07:37.577  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:37.593  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:37.598  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:37.685  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 16:07:37.685  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.,
,09-09 16:07:37.686  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:07:37.686  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:37.749  3712  3712 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 16:07:37.750  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 16:07:37.751  3712  3712 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 16:07:55.332   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219999, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:07:59.498  3793  4481 V KeepSync: Connecting to GoogleApiClient
,09-09 16:07:59.499   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:07:59.565  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:59.568  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:07:59.606  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:07:59.607  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:07:59.607  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:07:59.607  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:59.631  1714  4482 V BaseAuthAsyncOperation: access token request failed
,09-09 16:07:59.633  3793  4481 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:07:59.730  1504  3190 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 16:07:59.730  1504  3190 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:07:59.730  1504  3190 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:07:59.731  1504  3190 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:07:59.755  3793  4481 E KeepSync: IOException
09-09 16:07:59.755  3793  4481 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:07:59.755  3793  4481 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:07:59.755  3793  4481 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:07:59.755  3793  4481 E KeepSync: 	... 10 more
,09-09 16:07:59.755  3793  4481 W KeepSync: Sync result 2
,09-09 16:07:59.767   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 224053, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:08:07.391  1896  1961 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-09 16:08:07.392  1896  1961 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 16:08:07.439  1504  1504 I ConfigService: onCreate
,09-09 16:08:12.523  1504  1504 I ConfigService: onDestroy
,09-09 16:08:30.059  4273  4485 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:08:30.170  4273  4488 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:08:30.189  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:08:30.197  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:08:30.273  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:08:30.273  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:08:30.273  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:08:30.273  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:08:30.293  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 16:08:30.293  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:08:30.293  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:08:30.293  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:08:30.321  3753  4487 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:08:30.321  3753  4487 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:08:30.321  3753  4487 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	... 12 more
09-09 16:08:30.321  3753  4487 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at fal.a(PG:38)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:08:30.321  3753  4487 E HttpOperation: 	... 14 more
,09-09 16:08:30.399  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:08:30.400  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:08:30.400  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:08:30.400  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:08:30.418  1504  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:08:30.418  1504  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:08:30.418  1504  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:08:30.418  1504  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:08:30.425  4273  4488 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:08:30.428  4273  4485 E BooksSync: Soft error
09-09 16:08:30.428  4273  4485 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:08:30.428  4273  4485 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:08:30.428  4273  4485 E BooksSync: Sync error
09-09 16:08:30.428  4273  4485 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:08:30.428  4273  4485 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:08:30.428  4273  4485 I BooksSync: Finished books sync
,09-09 16:08:30.435   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 224836, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:08:30.439  3753  4487 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:08:30.439  3753  4487 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at hec.a(PG:42)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at hee.a(PG:102)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at czr.a(PG:65)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at kka.a(PG:108)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:08:30.439  3753  4487 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	... 15 more
09-09 16:08:30.439  3753  4487 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at fal.a(PG:38)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:08:30.439  3753  4487 E HttpOperation: 	... 17 more
,09-09 16:08:30.439  3753  4487 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:08:30.439  3753  4487 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	... 15 more
09-09 16:08:30.439  3753  4487 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:08:30.439  3753  4487 E ExperimentLoader: 	... 17 more
,09-09 16:08:30.572   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 249979, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:08:43.518   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:09:00.807  3793  4491 V KeepSync: Connecting to GoogleApiClient
09-09 16:09:00.807   874  2063 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:09:00.858  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:09:00.860  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:09:00.917  1504  3190 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:09:00.918  1504  3190 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:09:00.918  1504  3190 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 16:09:00.918  1504  3190 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:09:00.950  1714  4492 V BaseAuthAsyncOperation: access token request failed
,09-09 16:09:00.953  3793  4491 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:09:01.037  1504  1922 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 16:09:01.037  1504  1922 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:09:01.037  1504  1922 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:09:01.038  1504  1922 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:09:01.075  3793  4491 E KeepSync: IOException
09-09 16:09:01.075  3793  4491 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:09:01.075  3793  4491 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:09:01.075  3793  4491 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:09:01.075  3793  4491 E KeepSync: 	... 10 more
,09-09 16:09:01.075  3793  4491 W KeepSync: Sync result 2
,09-09 16:09:01.087   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 284667, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:09:18.745   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=303412, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:09:31.458  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:09:31.463  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:09:31.510  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 16:09:31.510  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:09:31.510  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:09:31.510  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:09:31.534  3753  4499 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:09:31.534  3753  4499 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:09:31.534  3753  4499 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	... 12 more
09-09 16:09:31.534  3753  4499 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at fal.a(PG:38)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:09:31.534  3753  4499 E HttpOperation: 	... 14 more
,09-09 16:09:31.608  1504  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:09:31.608  1504  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:09:31.608  1504  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:09:31.608  1504  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:09:31.624  3753  4499 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:09:31.624  3753  4499 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at hec.a(PG:42)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at hee.a(PG:102)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at czr.a(PG:65)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at kka.a(PG:108)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:09:31.624  3753  4499 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	... 15 more
09-09 16:09:31.624  3753  4499 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at fal.a(PG:38)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:09:31.624  3753  4499 E HttpOperation: 	... 17 more
,09-09 16:09:31.625  3753  4499 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:09:31.625  3753  4499 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: ,	at hec.a(PG:42)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	... 15 more
09-09 16:09:31.625  3753  4499 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:09:31.625  3753  4499 E ExperimentLoader: 	... 17 more
,09-09 16:09:31.794   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 286014, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:09:44.851   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329518, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:10:00.636  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:10:00.645  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:10:00.649  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:10:00.683  1504  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 16:10:00.683  1504  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 16:10:00.683  1504  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:10:00.683  1504  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:10:00.709  1504  3703 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 16:10:00.709  1504  3703 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 16:10:00.709  1504  3703 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 16:10:00.709  1504  3703 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 16:10:00.709  1504  3703 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 16:10:00.709  1504  3703 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 16:10:00.709  1504  3703 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 16:10:00.713  3712  3744 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 16:10:00.713  3712  3744 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 16:10:00.713  3712  3744 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 16:10:00.713  3712  3744 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 16:10:00.713  3712  3744 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 16:10:00.713  3712  3744 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 16:10:00.713  3712  3744 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 16:10:01.940  4273  4506 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:10:01.965  4273  4507 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:10:02.016  1504  3703 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:10:02.017  1504  3703 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:10:02.017  1504  3703 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:10:02.017  1504  3703 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:10:02.104  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:10:02.104  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:10:02.105  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:10:02.105  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:10:02.143  4273  4507 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:10:02.145  4273  4506 E BooksSync: Soft error
09-09 16:10:02.145  4273  4506 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:10:02.145  4273  4506 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:10:02.145  4273  4506 E BooksSync: Sync error
09-09 16:10:02.145  4273  4506 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:10:02.145  4273  4506 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:10:02.146  4273  4506 I BooksSync: Finished books sync
,09-09 16:10:02.158   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 317248, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:10:33.760  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:10:33.765  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:10:33.829  1504  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 16:10:33.829  1504  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 16:10:33.829  1504  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:10:33.830  1504  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:10:33.869  3753  4511 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:10:33.869  3753  4511 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:10:33.869  3753  4511 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	... 12 more
09-09 16:10:33.869  3753  4511 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at fal.a(PG:38)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:10:33.869  3753  4511 E HttpOperation: 	... 14 more
,09-09 16:10:33.958  1504  1922 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:10:33.958  1504  1922 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:10:33.958  1504  1922 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:10:33.958  1504  1922 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:10:34.004  3753  4511 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:10:34.004  3753  4511 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at hec.a(PG:42)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at hee.a(PG:102)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at czr.a(PG:65)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at kka.a(PG:108)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:10:34.004  3753  4511 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	... 15 more
09-09 16:10:34.004  3753  4511 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at fal.a(PG:38)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:10:34.004  3753  4511 E HttpOperation: 	... 17 more
,09-09 16:10:34.005  3753  4511 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:10:34.005  3753  4511 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at hec.a(PG:42)
,09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: ,	... 15 more
09-09 16:10:34.005  3753  4511 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:10:34.005  3753  4511 E ExperimentLoader: 	... 17 more
,09-09 16:10:34.202   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 378010, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:10:36.237   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:10:46.904   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=391571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:11:04.367  3793  4514 V KeepSync: Connecting to GoogleApiClient
,09-09 16:11:04.367   874  2031 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 16:11:04.427  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:11:04.430  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:11:04.464  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 16:11:04.464  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 16:11:04.464  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:11:04.464  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:11:04.488  1714  4515 V BaseAuthAsyncOperation: access token request failed
,09-09 16:11:04.489  3793  4514 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:11:04.555  1504  3190 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 16:11:04.556  1504  3190 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 16:11:04.556  1504  3190 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:11:04.556  1504  3190 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:11:04.582  3793  4514 E KeepSync: IOException
09-09 16:11:04.582  3793  4514 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:11:04.582  3793  4514 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:11:04.582  3793  4514 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:11:04.582  3793  4514 E KeepSync: 	... 10 more
09-09 16:11:04.583  3793  4514 W KeepSync: Sync result 2
,09-09 16:11:04.594   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 406219, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:11:22.159   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=426825, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:12:03.865   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468532, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:12:06.507  4273  4518 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:12:06.548  4273  4519 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:12:06.564  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:12:06.568  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:12:06.601  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:12:06.601  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 16:12:06.601  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:12:06.601  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:12:06.630  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:12:06.632  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:12:06.651  1504  3190 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 16:12:06.651  1504  3190 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.,
09-09 16:12:06.651  1504  3190 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:12:06.651  1504  3190 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:12:06.665  4273  4519 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:12:06.666  4273  4518 E BooksSync: Soft error
09-09 16:12:06.666  4273  4518 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:12:06.666  4273  4518 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:12:06.666  4273  4518 E BooksSync: Sync error
09-09 16:12:06.666  4273  4518 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:12:06.666  4273  4518 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:12:06.666  4273  4518 I BooksSync: Finished books sync
,09-09 16:12:06.680   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 471114, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:12:37.604  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:12:37.605  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:12:37.636  1504  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:12:37.636  1504  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 16:12:37.636  1504  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:12:37.636  1504  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:12:37.664  3753  4523 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:12:37.664  3753  4523 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:12:37.664  3753  4523 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	... 12 more
09-09 16:12:37.664  3753  4523 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at fal.a(PG:38)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:12:37.664  3753  4523 E HttpOperation: 	... 14 more
,09-09 16:12:37.739  1504  1922 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:12:37.739  1504  1922 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 16:12:37.739  1504  1922 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:12:37.739  1504  1922 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:12:37.751  3753  4523 E HttpOperation: [getmobileexperiments] Unexpected exception,
09-09 16:12:37.751  3753  4523 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at hec.a(PG:42)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at hee.a(PG:102)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at czr.a(PG:65)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at kka.a(PG:108)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:12:37.751  3753  4523 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	... 15 more
09-09 16:12:37.751  3753  4523 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at fal.a(PG:38)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:12:37.751  3753  4523 E HttpOperation: 	... 17 more
,09-09 16:12:37.752  3753  4523 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:12:37.752  3753  4523 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	... 15 more
09-09 16:12:37.752  3753  4523 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:12:37.752  3753  4523 E ExperimentLoader: 	... 17 more
,09-09 16:12:37.891   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 501965, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:12:39.065   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=503732, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:13:03.172   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=527839, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:13:38.372   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=563038, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:14:06.319   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590985, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:14:41.519   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=626185, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:15:05.580   874   874 I ActivityManager: Start proc 4534:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-09 16:15:05.703  4534  4534 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-09 16:15:05.739  4534  4534 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-09 16:15:05.739  4534  4534 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 16:15:05.739  4534  4534 I GAv4    :   adb logcat -s GAv4
,09-09 16:15:05.759  4534  4534 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:15:05.769  4534  4534 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:15:05.787  4534  4549 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:15:06.065   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=650732, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 16:15:41.252   874  4431 D NetlinkSocketObserver: NeighborEvent{elapsedMs=685918, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 16:24:33.460   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-09 16:29:52.406  4588  4588 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 16:29:52.411  4588  4588 D AndroidRuntime: CheckJNI is OFF
09-09 16:29:52.454  4588  4588 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 16:29:52.502  4588  4588 I Radio-JNI: register_android_hardware_Radio DONE
09-09 16:29:52.525  4588  4588 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 16:29:52.537   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 16:29:52.655   874   897 W PackageSettings: Skipping PackageSetting{a240b3 com.example.hello/10273} due to missing metadata
09-09 16:29:52.688   874   897 I art     : Starting a blocking GC Explicit
09-09 16:29:52.741   874   897 I art     : Explicit concurrent mark sweep GC freed 37770(2MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 744us total 51.209ms
09-09 16:29:52.773   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 16:29:52.781  4588  4588 I art     : System.exit called, status: 0
09-09 16:29:52.781  4588  4588 I AndroidRuntime: VM exiting with result code 0.
09-09 16:29:52.802   874   897 I ActivityManager: Start proc 4599:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-09 16:29:52.803   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-09 16:29:52.844  1866  2226 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 16:29:52.847  4378  4378 D BluetoothMapAppObserver: onReceive
09-09 16:29:52.847   874  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 16:29:52.847  4378  4378 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 16:29:52.855  3852  3852 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 16:29:52.868  1896  1896 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 16:29:52.874  1896  4612 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 16:29:52.895   874  1384 I ActivityManager: Start proc 4615:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 16:29:52.895  2022  2022 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-09 16:29:52.914  1896  4612 I Decoder : createOrResetDecoder
09-09 16:29:52.927   874   885 I ActivityManager: Killing 3905:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-09 16:29:52.946  4615  4615 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 16:29:52.952   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:29:52.981  4615  4629 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:29:52.981  4615  4629 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:29:52.999  4615  4629 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-09 16:29:53.003  4615  4629 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-09 16:29:53.003  4615  4629 E AndroidRuntime: Process: android.process.acore, PID: 4615
09-09 16:29:53.003  4615  4629 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:29:53.003  4615  4629 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:29:53.007  4615  4615 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 16:29:53.009  1504  1504 I ConfigService: onCreate
09-09 16:29:53.010  2039  2140 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 16:29:53.013   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 16:29:53.013   874  4631 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:29:53.013   874  4631 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:29:53.013   874  4631 E DropBoxManagerService: 	... 5 more
09-09 16:29:53.014   874   886 E PackageManager: Failed to write settings, restoring backup
09-09 16:29:53.014   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 16:29:53.014   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 16:29:53.014   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 16:29:53.014   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 16:29:53.014   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 16:29:53.014   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:29:53.014   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:29:53.014   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:29:53.022   874   887 I ActivityManager: Start proc 4633:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-09 16:29:53.023   874  1986 I ActivityManager: Killing 2110:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-09 16:29:53.023   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-09 16:29:53.023   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 16:29:53.023   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:29:53.023   874   887 E DropBoxManagerService: 	... 13 more
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 16:29:53.041  1504  4632 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 16:29:53.042  1504  4632 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:29:53.044  1504  4632 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 16:29:53.061   874  1313 D WifiService: Client connection lost with reason: 4
09-09 16:29:53.083   874  2072 I ActivityManager: Start proc 4645:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-09 16:29:53.084  2039  2140 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 16:29:53.084  2039  2140 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2039
09-09 16:29:53.084  2039  2140 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:29:53.084  2039  2140 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:29:53.084  4615  4629 I Process : Sending signal. PID: 4615 SIG: 9
09-09 16:29:53.092   874  2031 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 16:29:53.094   874  4655 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:29:53.094   874  4655 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:29:53.094   874  4655 E DropBoxManagerService: 	... 5 more
09-09 16:29:53.098  2039  2140 I Process : Sending signal. PID: 2039 SIG: 9
09-09 16:29:53.115  1896  4612 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 16:29:53.138  4633  4633 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-09 16:29:53.183  1896  4612 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 16:29:53.185  1896  4612 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 16:29:53.185  1896  4612 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 16:29:53.187  1896  4612 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 16:29:53.187  1896  4612 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 16:29:53.188  1896  4612 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 16:29:53.188  1896  4612 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 16:29:53.191  1896  4612 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 16:29:53.191  1896  4612 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 16:29:53.191  1896  4612 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 16:29:53.191  1896  4612 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 16:29:53.191  1896  4612 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 16:29:53.191  1896  4612 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-09 16:29:53.198  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 16:29:53.200  1504  1504 D AndroidRuntime: Shutting down VM
09-09 16:29:53.201  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
09-09 16:29:53.201  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
09-09 16:29:53.201  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 16:29:53.201  1504  1504 E AndroidRuntime: 	... 8 more
09-09 16:29:53.209  1504  1504 I Process : Sending signal. PID: 1504 SIG: 9
09-09 16:29:53.210   874  4664 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:29:53.210   874  4664 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:29:53.210   874  4664 E DropBoxManagerService: 	... 5 more
09-09 16:29:53.257   874  1300 W InputDispatcher: channel '9660c79 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-09 16:29:53.258   874  1300 E InputDispatcher: channel '9660c79 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!

```
