#### Test 81418577dce6d7c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 15:50:25.490  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:50:25.500  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 15:50:25.502  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 15:50:25.541  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 15:50:25.541  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 15:50:25.541  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:50:25.541  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 15:50:25.563  3467  3467 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 15:50:25.563  3467  3467 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 15:50:25.563  3467  3467 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-17 15:50:26.106  3751  3751 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 15:50:26.111  3751  3751 D AndroidRuntime: CheckJNI is OFF
08-17 15:50:26.156  3751  3751 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 15:50:26.207  3751  3751 I Radio-JNI: register_android_hardware_Radio DONE
08-17 15:50:26.229  3751  3751 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 15:50:26.234   872  1383 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 15:50:26.256  2012  2425 W SearchService: Abort, client detached.
08-17 15:50:26.264  2012  2012 I HotwordDetector: Closing mic
08-17 15:50:26.266  2012  2318 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@af9bbba
08-17 15:50:26.267  2012  2326 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 15:50:26.270  3751  3751 D AndroidRuntime: Shutting down VM
08-17 15:50:26.283   872  1699 I ActivityManager: Start proc 3760:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 15:50:26.315   376  2329 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 15:50:26.318   376  2329 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 15:50:26.326   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 15:50:26.329  2012  2323 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 15:50:26.330  2012  2325 I MicroRecognitionRnrImpl: Detection finished
08-17 15:50:26.366  3760  3760 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 15:50:26.389  3760  3760 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 15:50:26.397  3760  3760 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9450-9453)
08-17 15:50:26.397  3760  3760 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:50:26.411  3760  3760 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {55f7ce3}
08-17 15:50:26.411  3760  3760 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:50:26.412  3760  3760 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 15:50:26.420  3760  3760 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 15:50:26.421  3760  3760 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 15:50:26.437  3760  3760 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-17 15:50:26.448  3760  3760 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 15:50:26.448  3760  3760 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 15:50:26.448  3760  3760 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 15:50:26.448  3760  3760 I Adreno  : Build Date                       : 10/20/15
08-17 15:50:26.448  3760  3760 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 15:50:26.448  3760  3760 I Adreno  : Local Branch                     : M14
08-17 15:50:26.448  3760  3760 I Adreno  : Remote Branch                    : 
08-17 15:50:26.448  3760  3760 I Adreno  : Remote Branch                    : 
08-17 15:50:26.448  3760  3760 I Adreno  : Reconstruct Branch               : 
,08-17 15:50:26.512   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8dd7f5f:true
,08-17 15:50:26.547  3760  3760 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 15:50:26.561  3760  3760 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 15:50:26.621  3760  3799 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 15:50:26.633  3760  3786 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 15:50:26.696  3760  3799 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 15:50:26.760   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +491ms
,08-17 15:50:26.772  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-17 15:50:26.885  3760  3760 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3760
,08-17 15:50:27.043  3760  3760 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 15:50:27.110   872  3134 I ActivityManager: Killing 3179:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 15:50:27.149   872  3134 I ActivityManager: Killing 2960:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-17 15:50:27.276  3760  3802 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1715865296
,08-17 15:50:27.282  3760  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 15:50:27.282  3760  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 15:50:27.282  3760  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 15:50:27.282  3760  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 15:50:27.282  3760  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 15:50:27.282  3760  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f77f7 added. We now have 1 listener(s)
,08-17 15:50:27.286  3760  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-17 15:50:27.287  3760  3802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:50:27.287  3760  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:50:27.287  3760  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 15:50:27.292  3760  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd85d82 added. We now have 1 listener(s)
08-17 15:50:27.293  3760  3802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:27.302   872  1308 D WifiService: New client listening to asynchronous messages
,08-17 15:50:27.303  3760  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:50:27.303  3760  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 15:50:27.303  3760  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 15:50:27.303  3760  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 15:50:27.303  3760  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 15:50:27.306  3760  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:50:27.306  3760  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-17 15:50:27.311  3760  3802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:27.311  3760  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:27.312  3760  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 15:50:27.312  3760  3802 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:50:27.312  3760  3802 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 15:50:27.313  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:27.315  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:27.333  3760  3760 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 15:50:28.173  3760  3810 W jxcore-log: Initializing JXcore engine
08-17 15:50:28.173  3760  3810 W jxcore-log: JXcore engine is ready
,08-17 15:50:28.211  3810  3810 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-17 15:50:28.211  3810  3810 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10680]" dev="sockfs" ino=10680 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-17 15:50:28.211  3810  3810 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 15:50:28.211  3810  3810 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26015]" dev="sockfs" ino=26015 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 15:50:28.227  3760  3810 W jxcore-log: Starting JXcore engine
,08-17 15:50:28.342  3760  3810 W jxcore-log: Platform android
08-17 15:50:28.342  3760  3810 W jxcore-log: 
,08-17 15:50:28.343  3760  3810 W jxcore-log: Process ARCH arm
08-17 15:50:28.343  3760  3810 W jxcore-log: 
,08-17 15:50:28.645  3760  3810 I jxcore-log: JXcore Cordova bridge is ready!
08-17 15:50:28.645  3760  3810 I jxcore-log: 
,08-17 15:50:28.645  3760  3810 W jxcore-log: JXcore engine is started
,08-17 15:50:28.658  3760  3802 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 15:50:28.664  3760  3760 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 15:50:28.812   872  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-17 15:50:35.282  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:50:35.287  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:50:35.331  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 15:50:35.331  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 15:50:35.331  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:50:35.332  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:50:35.368  3506  3820 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 15:50:35.368  3506  3820 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at blb.a(PG:3937)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at czp.a(PG:18188)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:50:35.368  3506  3820 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	... 12 more
08-17 15:50:35.368  3506  3820 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at fal.a(PG:38)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:50:35.368  3506  3820 E HttpOperation: 	... 14 more
,08-17 15:50:35.434  1501  2037 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 15:50:35.434  1501  2037 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 15:50:35.434  1501  2037 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:50:35.435  1501  2037 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:50:35.450  3506  3820 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 15:50:35.450  3506  3820 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jdm.a(PG:82)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jcs.o(PG:406)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jcn.a(PG:1379)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jcs.i(PG:143)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at hec.a(PG:42)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at hee.a(PG:102)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at czr.a(PG:65)
,08-17 15:50:35.450  3506  3820 E HttpOperation: 	at kka.a(PG:108)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at czp.a(PG:19176)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at czp.a(PG:9081)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at czq.run(PG:1686)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:50:35.450  3506  3820 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jdj.a(PG:4091)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jdj.a(PG:1125)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jdm.a(PG:77)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	... 15 more
08-17 15:50:35.450  3506  3820 E HttpOperation: Caused by: faj: BadAuthentication
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at fal.a(PG:38)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	at jdj.a(PG:4089)
08-17 15:50:35.450  3506  3820 E HttpOperation: 	... 17 more
08-17 15:50:35.450  3506  3820 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 15:50:35.450  3506  3820 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at hec.a(PG:42)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at hee.a(PG:102)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at czr.a(PG:65)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at kka.a(PG:108)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	... 15 more
08-17 15:50:35.450  3506  3820 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at fal.a(PG:38)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 15:50:35.450  3506  3820 E ExperimentLoader: 	... 17 more
,08-17 15:50:35.582   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128123, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-17 15:50:38.882  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 15:50:38.882  3760  3810 I jxcore-log: 
,08-17 15:50:38.885  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 15:50:38.885  3760  3810 I jxcore-log: 
,08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:38.898  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:38.910  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:50:38.913  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 15:50:38.913  3760  3810 I jxcore-log: 
,08-17 15:50:38.915  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 15:50:38.915  3760  3810 I jxcore-log: 
,08-17 15:50:39.241  3760  3810 D ExecuteNativeTests: Running unit tests
,08-17 15:50:39.299  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:50:39.299  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 added. We now have 2 listener(s)
,08-17 15:50:39.301  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:50:39.301  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:50:39.301  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:50:39.301  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:50:39.301  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a added. We now have 2 listener(s)
08-17 15:50:39.301  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:39.302  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:50:39.306  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:39.319  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:39.325  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:50:39.326  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:50:39.328  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 15:50:39.328  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:50:39.328  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 15:50:39.330  3760  3810 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 15:50:39.330  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:50:39.331  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:50:39.331  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:50:39.331  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:50:39.331  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:50:39.332  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.332  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.332  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.332  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.332  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:50:39.332  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:50:39.333  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 removed from the list
08-17 15:50:39.333  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:50:39.333  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a removed from the list
,08-17 15:50:39.334  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.335  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.335  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.336  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.336  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.338  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.339  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:50:39.339  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.339  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.342  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:39.344  3760  3810 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 15:50:39.347  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.347  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.347  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.348  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.348  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.348  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.348  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.349  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.349  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.349  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.349  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.350  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.350  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:50:39.350  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.353  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.353  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.353  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.353  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
,08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:50:39.364  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:50:39.365  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:50:39.366  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:50:39.366  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-17 15:50:39.366  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:50:39.366  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:50:39.366  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:50:39.366  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:50:39.366  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.366  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.366  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.366  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:50:39.366  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.366  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.367  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.367  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.367  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.367  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.367  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.367  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.367  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.367  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.370  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.370  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.370  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:50:39.370  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.371  3760  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 15:50:39.372  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:39.382  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:39.386  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.386  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:50:39.386  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:50:39.387  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 15:50:39.387  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:50:39.387  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:50:39.387  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:50:39.390  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:39.397  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:50:39.397  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:50:39.399  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:39.403  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:50:39.405  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 15:50:39.405  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:50:39.408  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-17 15:50:39.411  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-17 15:50:39.411  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:50:39.412  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:50:39.412  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:50:39.413  3760  3810 D BluetoothAdapter: STATE_ON
,08-17 15:50:39.417  2688  2880 D BtGatt.GattService: registerClient() - UUID=c2966adf-c5e4-4559-945b-e0afb5ce8591
,08-17 15:50:39.418  2688  2740 D BtGatt.GattService: onClientRegistered() - UUID=c2966adf-c5e4-4559-945b-e0afb5ce8591, clientIf=5
,08-17 15:50:39.420  3760  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 15:50:39.423  2688  2701 D BtGatt.GattService: start scan with filters
,08-17 15:50:39.426  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:50:39.427  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:50:39.427  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:50:39.427  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 15:50:39.427  2688  2743 D BtGatt.ScanManager: handling starting scan
,08-17 15:50:39.430  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:50:39.430  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:50:39.430  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:50:39.431  2688  2743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:39.431  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:50:39.435  3760  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 15:50:39.438  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.438  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:50:39.438  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.438  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:50:39.438  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.438  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:50:39.439  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:50:39.439  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:50:39.439  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:50:39.439  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:50:39.439  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:50:39.439  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:50:39.440  3760  3810 D BluetoothAdapter: STATE_ON
,08-17 15:50:39.441  2688  2880 D BtGatt.GattService: stopScan() - queue size =1
08-17 15:50:39.442  2688  2701 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 15:50:39.442  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:50:39.442  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:50:39.442  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:50:39.442  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:50:39.442  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:50:39.451  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:50:39.451  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:50:39.451  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:50:39.452  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:50:39.452  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:50:39.453  2688  2740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 15:50:39.453  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:50:39.453  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.454  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.454  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:50:39.454  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
,08-17 15:50:39.454  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.454  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.454  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.454  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.454  2688  2743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 15:50:39.455  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.455  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.455  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:50:39.455  3760  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:50:39.457  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:39.465  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:39.466  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 15:50:39.466  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.467  2688  2743 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:50:39.468  2688  2743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 15:50:39.469  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:50:39.469  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:50:39.470  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:50:39.470  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 15:50:39.470  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:50:39.470  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:50:39.471  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:50:39.472  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.474  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.478  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:50:39.478  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:50:39.478  2688  2740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 15:50:39.478  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:50:39.481  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:50:39.482  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 15:50:39.482  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:50:39.485  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:50:39.485  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:50:39.486  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:50:39.486  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:50:39.486  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:50:39.487  3760  3810 D BluetoothAdapter: STATE_ON
,08-17 15:50:39.491  2688  2703 D BtGatt.GattService: registerClient() - UUID=4d429df1-d1f9-4afe-b6e6-d8ee779d0ee8
,08-17 15:50:39.492  2688  2740 D BtGatt.GattService: onClientRegistered() - UUID=4d429df1-d1f9-4afe-b6e6-d8ee779d0ee8, clientIf=5
08-17 15:50:39.493  3760  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 15:50:39.494  2688  2880 D BtGatt.GattService: start scan with filters
,08-17 15:50:39.497  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 15:50:39.497  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.497  2688  2743 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:50:39.498  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:50:39.499  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:50:39.500  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:50:39.501  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:50:39.502  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:50:39.502  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.502  2688  2743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:50:39.505  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:50:39.505  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:50:39.505  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:50:39.506  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 15:50:39.508  2688  2740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 15:50:39.508  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:50:39.509  2688  2743 D BtGatt.ScanManager: handling starting scan
08-17 15:50:39.510  3760  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 15:50:39.512  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.512  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:50:39.512  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.512  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:50:39.512  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.513  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:50:39.513  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:50:39.513  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:50:39.513  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 15:50:39.513  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:50:39.513  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:50:39.513  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 15:50:39.514  3760  3810 D BluetoothAdapter: STATE_ON
08-17 15:50:39.514  2688  2701 D BtGatt.GattService: stopScan() - queue size =1
,08-17 15:50:39.515  2688  2881 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 15:50:39.515  2688  2740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 15:50:39.516  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.516  2688  2743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 15:50:39.516  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:50:39.516  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:50:39.516  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:50:39.516  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:50:39.516  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 15:50:39.517  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:50:39.517  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:50:39.517  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 15:50:39.518  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:50:39.518  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:50:39.519  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.519  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.519  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:50:39.519  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:50:39.520  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.520  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:50:39.520  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.520  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.520  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.520  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.520  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.520  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.521  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.521  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 15:50:39.521  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.521  2688  2743 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:50:39.521  2688  2743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 15:50:39.521  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.521  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.521  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.522  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
,08-17 15:50:39.522  3760  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:50:39.524  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:39.529  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:39.531  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.531  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:50:39.532  2688  2740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 15:50:39.532  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:50:39.533  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:50:39.533  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 15:50:39.533  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:50:39.533  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:50:39.533  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:50:39.534  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.535  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:50:39.535  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:50:39.536  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.538  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:50:39.538  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.539  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:50:39.540  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 15:50:39.540  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:50:39.543  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:50:39.543  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:50:39.543  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:50:39.544  3760  3810 D BluetoothAdapter: STATE_ON
,08-17 15:50:39.545  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 15:50:39.545  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.545  2688  2743 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:50:39.546  2688  2881 D BtGatt.GattService: registerClient() - UUID=4475832b-571f-4541-98d5-c6c7747d6c3b
08-17 15:50:39.546  2688  2740 D BtGatt.GattService: onClientRegistered() - UUID=4475832b-571f-4541-98d5-c6c7747d6c3b, clientIf=5
08-17 15:50:39.546  3760  3772 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 15:50:39.546  2688  2880 D BtGatt.GattService: start scan with filters
,08-17 15:50:39.549  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:50:39.550  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:50:39.550  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:50:39.550  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:50:39.551  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:50:39.551  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.551  2688  2743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:50:39.552  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:50:39.553  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:50:39.553  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:50:39.554  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:50:39.556  2688  2740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 15:50:39.556  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.557  3760  3810 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:50:39.557  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.557  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 15:50:39.557  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.557  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:50:39.557  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.557  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:50:39.558  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:50:39.558  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:50:39.558  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:50:39.558  2688  2743 D BtGatt.ScanManager: handling starting scan
,08-17 15:50:39.558  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:50:39.561  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 15:50:39.561  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 15:50:39.563  3760  3810 D BluetoothAdapter: STATE_ON
08-17 15:50:39.563  2688  2880 D BtGatt.GattService: stopScan() - queue size =1
08-17 15:50:39.564  2688  2703 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 15:50:39.564  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:50:39.564  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:50:39.564  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:50:39.564  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:50:39.564  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 15:50:39.565  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:50:39.565  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:50:39.565  2688  2740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 15:50:39.565  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.565  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:50:39.566  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:50:39.566  2688  2743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 15:50:39.566  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:50:39.567  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.567  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.567  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:50:39.567  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.568  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:50:39.568  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.568  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.568  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.568  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.568  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:50:39.568  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.568  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.568  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.568  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.569  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.569  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.569  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.570  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.570  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.570  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.571  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.571  3760  3810 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 15:50:39.572  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.572  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:50:39.572  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.572  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.572  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.572  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.572  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.572  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.572  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.572  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.573  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.573  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.573  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.573  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 15:50:39.573  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.573  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.573  2688  2743 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:50:39.573  2688  2743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 15:50:39.574  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.574  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.574  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.574  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.575  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:50:39.575  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.575  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.575  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:50:39.575  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.575  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.575  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.576  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.576  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.576  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.576  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.576  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.576  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.576  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.576  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.577  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.577  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.578  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.578  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.579  3760  3810 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 15:50:39.579  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.579  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.579  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.579  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.579  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.580  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.580  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
,08-17 15:50:39.581  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.582  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.582  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.582  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.582  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.582  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.582  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.583  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.583  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.583  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.583  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
,08-17 15:50:39.583  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 15:50:39.584  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.584  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.584  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.584  2688  2740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 15:50:39.584  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.584  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.584  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:50:39.584  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.584  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.584  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.584  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.584  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.584  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.585  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.585  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.585  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.585  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.585  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.586  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:50:39.586  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.586  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:50:39.586  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:50:39.586  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:50:39.587  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:50:39.587  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:50:39.587  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:50:39.587  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:50:39.587  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.587  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.587  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.587  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.587  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.587  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.587  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.588  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.588  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.588  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.588  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.588  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:50:39.588  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.589  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.589  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.589  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.589  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.589  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:50:39.589  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.590  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:50:39.590  3760  3810 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:50:39.590  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 15:50:39.594  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 15:50:39.594  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 15:50:39.594  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:50:39.594  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:50:39.594  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:50:39.594  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:50:39.594  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:50:39.595  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:50:39.596  2688  2740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:50:39.596  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:50:39.596  2688  2743 D BtGatt.ScanManager: stopping BLe Batch
08-17 15:50:39.596  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:50:39.597  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-17 15:50:39.597  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:50:39.597  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:50:39.597  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 15:50:39.597  3760  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:50:39.597  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 15:50:39.597  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:50:39.597  3760  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:50:39.597  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 15:50:39.598  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:50:39.598  3760  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:50:39.598  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-17 15:50:39.601  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-17 15:50:39.602  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-17 15:50:39.602  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
08-17 15:50:39.602  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 15:50:39.603  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 15:50:39.603  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 15:50:39.603  2688  2740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:50:39.603  3760  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 15:50:39.603  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:50:39.603  2688  2743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 15:50:39.603  3760  3810 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 15:50:39.604  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.604  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.604  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.604  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.604  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.604  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.604  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-17 15:50:39.608  2688  2740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 15:50:39.608  2688  2740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:50:39.611  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
,08-17 15:50:39.611  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.611  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.611  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.611  3760  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 390)
08-17 15:50:39.611  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.611  3760  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 390
08-17 15:50:39.611  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.611  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.611  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.611  3760  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 390)
08-17 15:50:39.612  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.612  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.612  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.612  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.613  3760  3810 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-17 15:50:39.613  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.613  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.613  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.614  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.614  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:50:39.614  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.614  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.614  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.614  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.614  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.614  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.614  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.614  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.614  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.615  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.615  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.615  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.615  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.616  3760  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 15:50:39.616  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.616  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.616  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:50:39.616  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.616  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.616  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.617  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.617  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.617  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.617  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.617  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.617  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.617  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.617  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.618  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.618  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.618  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.618  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
,08-17 15:50:39.619  3760  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 15:50:39.619  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 15:50:39.619  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:50:39.619  3760  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 15:50:39.619  3760  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:50:39.619  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 15:50:39.619  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:50:39.619  3760  3810 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 15:50:39.619  3760  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:50:39.619  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:50:39.619  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:50:39.619  3760  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 15:50:39.620  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:50:39.620  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.620  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.620  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.620  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.620  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.620  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.620  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.620  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.620  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.620  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.620  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.620  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.621  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.622  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.622  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.622  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.622  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.623  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.623  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.623  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.623  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.623  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.623  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
,08-17 15:50:39.623  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.623  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.623  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.623  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.623  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.623  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.624  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.624  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.624  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.624  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.624  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:50:39.624  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.624  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.624  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.624  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.624  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.624  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.624  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.624  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.625  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.625  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.625  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.625  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.626  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.626  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.626  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:50:39.626  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.627  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 15:50:39.627  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:50:39.628  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 15:50:39.628  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 15:50:39.628  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 15:50:39.629  3760  3760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 15:50:39.629  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 15:50:39.629  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 15:50:39.629  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.629  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 15:50:39.629  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 15:50:39.629  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 15:50:39.630  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.630  3760  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 15:50:39.630  3760  3760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 15:50:39.630  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.630  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.630  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:50:39.630  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:50:39.630  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:50:39.630  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.630  3760  3827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:50:39.630  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.631  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:50:39.632  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.632  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:50:39.632  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:50:39.632  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.632  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.632  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.632  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.632  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.633  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:50:39.633  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.633  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.633  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.633  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.633  3760  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 15:50:39.633  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.633  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.633  3760  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 15:50:39.633  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.633  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.633  3760  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 15:50:39.633  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.633  3760  3760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 15:50:39.634  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.634  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.634  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.634  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
,08-17 15:50:39.635  3760  3810 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 15:50:39.636  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-17 15:50:39.636  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:50:39.636  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 15:50:39.636  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.636  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.636  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.636  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.636  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.636  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.637  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.637  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:50:39.637  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.637  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.637  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.637  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.637  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.637  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.638  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.638  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:50:39.638  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.638  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.641  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.641  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.641  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:50:39.642  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:50:39.642  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.642  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.642  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.642  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.642  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.642  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.642  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.642  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.642  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.642  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.643  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.643  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.643  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.643  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.644  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:50:39.644  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:50:39.644  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:50:39.644  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:50:39.644  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.644  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.644  3760  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a31b6a5 not in the list
08-17 15:50:39.644  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.644  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.644  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:50:39.645  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.645  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:50:39.645  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:50:39.645  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:39.645  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:50:39.645  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:50:39.646  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:50:39.646  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56f3a7a not in the list
08-17 15:50:39.646  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 15:50:39.646  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:50:39.647  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 15:50:39.647  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-17 15:50:39.647  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 15:50:39.647  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 15:50:39.648  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:50:39.649  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 15:50:39.649  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 15:50:39.649  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:50:39.649  3760  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 15:50:39.649  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:50:39.649  3760  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-17 15:50:39.649  3760  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 15:50:39.650  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 15:50:39.650  3760  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 15:50:39.650  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 15:50:39.651  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 15:50:39.651  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 15:50:39.651  3760  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-17 15:50:39.652  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:50:39.652  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@330f4cc added. We now have 2 listener(s)
08-17 15:50:39.652  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:39.653  3760  3810 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 15:50:39.653   872   883 D WifiService: setWifiEnabled: true pid=3760, uid=10000
08-17 15:50:39.653   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 15:50:39.654  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:50:39.654  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8369315 added. We now have 3 listener(s)
08-17 15:50:39.654  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:39.658  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:50:39.658  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74b362a added. We now have 4 listener(s)
08-17 15:50:39.658  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:39.659  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:50:39.659  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4030c1b added. We now have 5 listener(s)
08-17 15:50:39.660  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:39.661   872  1700 D WifiService: setWifiEnabled: false pid=3760, uid=10000
08-17 15:50:39.661   872  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:50:39.666  2688  2736 D BluetoothAdapterState: Current state: ON, message: 23
08-17 15:50:39.666  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:50:39.666  2688  2736 D BluetoothAdapterProperties: Setting state to 13
,08-17 15:50:39.666  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 15:50:39.667  2688  2736 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 15:50:39.668  2688  2736 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:50:39.669  2688  2740 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:50:39.669  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:39.670  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:39.670  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 15:50:39.672  2688  2688 D BluetoothMapService: onReceive
08-17 15:50:39.672  2688  2688 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:50:39.672  2688  2688 D BluetoothMapService: STATE_TURNING_OFF
08-17 15:50:39.672  2688  2688 D BluetoothMapService: MAP Service closeService in
08-17 15:50:39.673  2688  2688 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 15:50:39.673  2688  2688 D ObexServerSockets0: shutdown(block = true)
08-17 15:50:39.673  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 15:50:39.674  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 15:50:39.674  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:39.674  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.675  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:50:39.675  2688  2883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 15:50:39.675  2688  2870 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 15:50:39.675  2688  2882 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 15:50:39.676  2688  2688 I BtOppRfcommListener: stopping Accept Thread
08-17 15:50:39.677  2688  3387 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:50:39.677  2688  3387 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 15:50:39.679  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:50:39.682  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.684  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.686   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 15:50:39.686   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 15:50:39.687   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 15:50:39.687   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:50:39.689  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:39.689  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:50:39.689  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:39.689  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:39.691  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.692   872  1875 D DhcpClient: Clearing IP address
08-17 15:50:39.692   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:50:39.693  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.695  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.696   372   870 D CommandListener: Setting iface cfg
08-17 15:50:39.700  1501  2471 V NativeCrypto: Read error: ssl=0x9a653800: I/O error during system call, Connection timed out
,08-17 15:50:39.701   872  1878 D DhcpClient: Receive thread stopped
,08-17 15:50:39.702  1501  2471 V NativeCrypto: SSL shutdown failed: ssl=0x9a653800: I/O error during system call, Broken pipe
08-17 15:50:39.704   872   885 I ActivityManager: Start proc 3830:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-17 15:50:39.705  2688  2688 D HeadsetService: Received stop request...Stopping profile...
08-17 15:50:39.705   872  1383 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-17 15:50:39.706   872  1870 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-17 15:50:39.706   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:39.706   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:39.707   872   872 D BluetoothHeadset: Proxy object disconnected
,08-17 15:50:39.707  1351  2034 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:39.707  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-17 15:50:39.708  1922  1933 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:39.709  2688  2688 D A2dpService: Received stop request...Stopping profile...
08-17 15:50:39.710  2688  2875 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:50:39.711  1351  1351 D BluetoothA2dp: Proxy object disconnected
08-17 15:50:39.711   872   872 D BluetoothA2dp: Proxy object disconnected
08-17 15:50:39.713  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:39.713  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:39.713  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:39.713  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:39.715  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:50:39.715   872  1870 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-17 15:50:39.715  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:50:39.715   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-17 15:50:39.715  2688  2740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 15:50:39.716  2688  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:39.716  2688  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:39.716  2688  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:39.716   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:50:39.716  2688  2688 D HidService: Received stop request...Stopping profile...
08-17 15:50:39.716  2688  2688 D HidService: Stopping Bluetooth HidService
08-17 15:50:39.716  2688  2740 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 15:50:39.716   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 15:50:39.717   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-17 15:50:39.717   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-17 15:50:39.718   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:50:39.722   407   407 E Parcel  : Reading a NULL string not supported here.
08-17 15:50:39.722  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-17 15:50:39.722  1351  1351 D HidProfile: Bluetooth service disconnected
08-17 15:50:39.723   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 15:50:39.723  2688  2688 D HealthService: Received stop request...Stopping profile...
08-17 15:50:39.724   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:50:39.725  2688  2688 D PanService: Received stop request...Stopping profile...
08-17 15:50:39.726  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 15:50:39.726  1351  1351 D PanProfile: Bluetooth service disconnected
08-17 15:50:39.726  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:39.726  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:39.726  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:39.726  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:39.727  2688  2688 D BluetoothMapService: Received stop request...Stopping profile...
08-17 15:50:39.727  2688  2688 D BluetoothMapService: stop()
,08-17 15:50:39.729   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 15:50:39.729   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 15:50:39.733  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:39.733  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:39.732  2688  2688 D BluetoothMapAppObserver: deinitObservers()
08-17 15:50:39.733  2688  2688 D BluetoothMapAppObserver: removeReceiver()
08-17 15:50:39.733  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:39.733  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:50:39.735  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:39.735  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:39.735  1351  1351 D BluetoothMap: Proxy object disconnected
08-17 15:50:39.735  1351  1351 D MapProfile: Bluetooth service disconnected
08-17 15:50:39.736  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:39.736  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:39.737  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:39.737  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:39.737  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:39.737  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:39.737   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 15:50:39.737  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:50:39.737  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:50:39.737  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:39.737  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:39.737  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:39.738  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:39.738  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:50:39.738  2688  2740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 15:50:39.738  2688  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:39.738  2688  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:39.738  2688  2864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 15:50:39.738  2688  2864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:50:39.738  2688  2864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:50:39.738  2688  2864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:50:39.738  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:50:39.738  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:39.738  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:39.739  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:39.739  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:39.739  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:50:39.739  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 15:50:39.738  2688  2740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 15:50:39.739  2688  2740 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 15:50:39.740  2688  2688 D BluetoothMapService: MAP Service closeService in
08-17 15:50:39.740  2688  2688 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:39.740  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:39.740  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:39.740  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:39.740  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 15:50:39.740  2688  2736 D BluetoothAdapterProperties: Setting state to 15
08-17 15:50:39.740  2688  2688 D BluetoothMapService: cleanup()
08-17 15:50:39.740  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-17 15:50:39.740  2688  2688 D BluetoothMapService: MAP Service closeService in
08-17 15:50:39.741  2688  2736 I BluetoothAdapterState: Entering BleOnState
08-17 15:50:39.742  1988  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:50:39.742   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:50:39.743  1922  1933 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:39.743   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:39.743   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:39.743  1351  1364 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:50:39.744  1351  1363 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:39.744  1351  2034 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 15:50:39.745  1351  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:50:39.745   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:39.745  1351  1363 D BluetoothMap: onBluetoothStateChange: up=false
08-17 15:50:39.745  1351  2034 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:50:39.747  2688  2736 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 15:50:39.747  2688  2736 D BluetoothAdapterProperties: Setting state to 16
,08-17 15:50:39.747  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 15:50:39.748  2688  2736 D BluetoothAdapterProperties: onBleDisable
08-17 15:50:39.748  2688  2736 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:50:39.748  2688  2737 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 15:50:39.749  2688  2864 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 15:50:39.749  2688  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:39.750  2688  2740 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:50:39.750  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.752  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.753  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.753  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.765   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 15:50:39.780  3830  3830 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-17 15:50:39.785   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 15:50:39.786   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-17 15:50:39.786   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:50:39.788   872   889 D Tethering: MasterInitialState.processMessage what=3
08-17 15:50:39.792   872   881 I art     : Background partial concurrent mark sweep GC freed 47021(2MB) AllocSpace objects, 10(192KB) LOS objects, 33% free, 29MB/43MB, paused 1.741ms total 111.897ms
08-17 15:50:39.792  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.793  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:39.795  3378  3378 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@3274415 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 15:50:39.816  3830  3830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:50:39.820  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:50:39.823   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc1f07a:true
,08-17 15:50:39.833   872   883 I ActivityManager: Start proc 3851:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 15:50:39.837   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-17 15:50:39.838   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 15:50:39.863  3851  3851 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 15:50:39.865  3830  3830 D LocalBluetoothProfileManager: Adding local MAP profile
,08-17 15:50:39.866  3830  3830 D BluetoothMap: Create BluetoothMap proxy object
,08-17 15:50:39.875  3830  3830 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 15:50:39.890  3830  3830 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:50:39.894   872  1700 I ActivityManager: Killing 2264:com.google.android.talk/u0a61 (adj 15): empty #17
,08-17 15:50:39.950  2688  2740 I bt_hci  : shut_down
,08-17 15:50:39.951  2688  2744 D bt_hwcfg: hw_epilog_process
,08-17 15:50:39.952  2688  2744 I bt_vendor: low_power_mode_cb
,08-17 15:50:39.974  2688  2744 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-17 15:50:39.974  2688  2744 I bt_vendor: epilog_cb
,08-17 15:50:39.974  2688  2744 I bt_hci  : epilog_finished_callback
08-17 15:50:39.981  2688  2740 I bt_hci_h4: hal_close
,08-17 15:50:39.981  2688  2740 I bt_userial_vendor: device fd = 51 close
,08-17 15:50:40.072  3851  3851 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 15:50:40.072  3851  3851 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:50:40.072  3851  3851 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:50:40.072  3851  3851 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:50:40.072  3851  3851 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:50:40.072  3851  3851 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:50:40.072  3851  3851 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.072  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:50:40.073  3851  3851 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:50:40.073  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 15:50:40.115   872   882 I ActivityManager: Start proc 3882:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-17 15:50:40.116   872   882 I ActivityManager: Killing 3518:com.google.process.gapps/u0a99 (adj 15): empty #17
08-17 15:50:40.132  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:50:40.159  2688  2737 D bt_stack_manager: event_shut_down_stack finished.
,08-17 15:50:40.160  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 15:50:40.163  2688  2688 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:50:40.163  2688  2736 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 15:50:40.164  2688  2688 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 15:50:40.164  2688  2688 D BtGatt.GattService: stop()
08-17 15:50:40.164  2688  2688 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 15:50:40.165  2688  2688 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:40.165  2688  2688 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:40.166  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:40.166  2688  2688 V BluetoothAdapterState: isBleTurningOff()=true
08-17 15:50:40.166  2688  2736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 15:50:40.166  2688  2736 D BluetoothAdapterProperties: Setting state to 10
08-17 15:50:40.166  2688  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 15:50:40.166  2688  2736 I BluetoothAdapterState: Entering OffState
,08-17 15:50:40.168   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 15:50:40.172  3882  3882 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-17 15:50:40.175  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-17 15:50:40.175  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 15:50:40.175  2688  2688 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:50:40.176  2688  2737 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 15:50:40.177  2688  2737 D bt_stack_manager: event_clean_up_stack finished.
,08-17 15:50:40.194  2688  2688 I art     : System.exit called, status: 0
08-17 15:50:40.194  2688  2688 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 15:50:40.228   872  1699 I ActivityManager: Process com.android.bluetooth (pid 2688) has died
,08-17 15:50:40.461  3882  3902 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-17 15:50:40.461  3882  3902 I Babel_SMS: MmsConfig.loadMmsSettings
08-17 15:50:40.462  3882  3902 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-17 15:50:40.463  3882  3902 I Babel_SMS: MmsConfig.loadFromDatabase
,08-17 15:50:40.510  3882  3902 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-17 15:50:40.510  3882  3902 I Babel_SMS: MmsConfig.loadFromResources
,08-17 15:50:40.511  3882  3902 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-17 15:50:40.511  3882  3902 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-17 15:50:40.514  3851  3879 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 15:50:40.533  3882  3882 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:50:40.535  3882  3882 I Babel_Crash: startup - clean
,08-17 15:50:40.591  3882  3882 I Babel_telephony: TeleModule.launchCompleted
,08-17 15:50:40.618   872  1974 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-17 15:50:40.634  3882  3882 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-17 15:50:40.642  3882  3882 W Babel   : BAM#gBA: invalid account id: -1
,08-17 15:50:40.643  3882  3882 W Babel   : BAM#gBA: invalid account id: -1
,08-17 15:50:40.643  3882  3882 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
08-17 15:50:40.645  3882  3907 I Babel   : deleted: false for 0
08-17 15:50:40.654   872  1957 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-17 15:50:40.677   872   882 I ActivityManager: Start proc 3909:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-17 15:50:40.748   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7c6432:true
,08-17 15:50:40.752  3882  3882 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:50:40.834  3909  3909 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 15:50:40.856  3882  3882 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 15:50:40.864  3882  3882 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:50:40.866  3882  3882 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:50:40.875  3882  3882 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:50:40.884  3882  3882 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:50:40.900  3882  3882 I vclib   : onServiceConnected
,08-17 15:50:40.929  3909  3909 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 15:50:40.975   872  1383 I ActivityManager: Killing 3378:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 15:50:41.039  3830  3830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:50:41.072   872  1974 I ActivityManager: Start proc 3934:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-17 15:50:41.077  3830  3830 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:50:41.213  3934  3934 D AdapterServiceConfig: Adding HeadsetService
,08-17 15:50:41.213  3934  3934 D AdapterServiceConfig: Adding A2dpService
08-17 15:50:41.214  3934  3934 D AdapterServiceConfig: Adding HidService
08-17 15:50:41.214  3934  3934 D AdapterServiceConfig: Adding HealthService
08-17 15:50:41.215  3934  3934 D AdapterServiceConfig: Adding PanService
08-17 15:50:41.215  3934  3934 D AdapterServiceConfig: Adding GattService
08-17 15:50:41.215  3934  3934 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 15:50:41.221   872  1383 I ActivityManager: Killing 2763:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 15:50:41.286  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:50:41.322  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 15:50:41.329  1715  1715 D SystemUpdateService: onCreate
,08-17 15:50:41.333  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 15:50:41.341  1715  3946 I SystemUpdateService: active receiver: enabled
,08-17 15:50:41.352  1715  3946 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 15:50:41.355  1715  3946 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 15:50:41.356  1715  3946 I SystemUpdateService: now status is 0 (complete)
,08-17 15:50:41.356  1715  3946 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 15:50:41.357  1715  3946 I SystemUpdateService: file has been verified
08-17 15:50:41.357  1715  3946 I SystemUpdateService: OTA package size = 12249756
08-17 15:50:41.357  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 15:50:41.362  1715  3946 I SystemUpdateService: showing system update notification
,08-17 15:50:41.364  1715  2437 I iu.UploadsManager: num queued entries: 0
,08-17 15:50:41.366  1715  2437 I iu.UploadsManager: num updated entries: 0
,08-17 15:50:41.370  1715  2437 I iu.SyncManager: NEXT; no task
,08-17 15:50:41.388  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 15:50:41.391  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:50:41.391  1715  1715 D SystemUpdateService: onDestroy
,08-17 15:50:41.414   872  1700 I ActivityManager: Start proc 3948:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 15:50:41.478  3948  3948 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 15:50:41.483  3948  3948 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:50:41.493  3948  3948 D SprintDMHelper: simOperator: 
08-17 15:50:41.493  3948  3948 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:50:41.531   872  1974 I ActivityManager: Start proc 3960:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 15:50:41.534   872  1974 I ActivityManager: Killing 3450:android.process.acore/u0a5 (adj 15): empty #17
,08-17 15:50:41.766   872  1942 I ActivityManager: Start proc 3975:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 15:50:41.773  3882  3974 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 15:50:41.791   872  1957 I ActivityManager: Killing 3613:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 15:50:41.908  3975  3975 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 15:50:41.995  3975  3975 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 15:50:41.995  3975  3975 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 15:50:41.995  3975  3975 I GAv4    :   adb logcat -s GAv4
,08-17 15:50:42.014  3975  3975 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:50:42.021  3975  3975 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:50:42.054  3975  3992 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 15:50:42.177  3975  3975 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 15:50:42.217  3975  3975 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 15:50:42.229  3975  3975 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5281-5285)
,08-17 15:50:42.229  3975  3975 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 15:50:42.242  3975  3975 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1484ce7}
,08-17 15:50:42.242  3975  3975 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:50:42.242  3975  3975 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 15:50:42.250  3975  3975 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 15:50:42.252  3975  3975 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 15:50:42.273  3975  3975 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 15:50:42.288  3975  3975 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 15:50:42.288  3975  3975 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 15:50:42.288  3975  3975 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 15:50:42.288  3975  3975 I Adreno  : Build Date                       : 10/20/15
08-17 15:50:42.288  3975  3975 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 15:50:42.288  3975  3975 I Adreno  : Local Branch                     : M14
08-17 15:50:42.288  3975  3975 I Adreno  : Remote Branch                    : 
08-17 15:50:42.288  3975  3975 I Adreno  : Remote Branch                    : 
08-17 15:50:42.288  3975  3975 I Adreno  : Reconstruct Branch               : 
,08-17 15:50:42.335  3975  4021 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 15:50:42.352  3975  3975 I NSApplication: Starting up...
,08-17 15:50:42.398   872   882 I ActivityManager: Start proc 4026:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 15:50:42.399   872   882 I ActivityManager: Killing 3630:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 15:50:42.521  4026  4026 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 15:50:42.677   872  1700 D WifiService: setWifiEnabled: true pid=3760, uid=10000
,08-17 15:50:42.677   872  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:50:42.681   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-17 15:50:42.689  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:42.690  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:42.690  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:42.690  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:42.693  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:42.693  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:42.694  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:42.694  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:42.715   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-17 15:50:42.716   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-17 15:50:42.717   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-17 15:50:42.718   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 15:50:42.718   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 15:50:42.718   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 15:50:42.718   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 15:50:42.735   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.25 rxSuccessRate=10.75 delta 1000 -> 994
,08-17 15:50:42.735   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-17 15:50:42.737   372   870 D CommandListener: Setting iface cfg
08-17 15:50:42.738   872  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-17 15:50:42.739   872  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 15:50:42.743   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 15:50:42.743   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:50:42.746   872  1974 I ActivityManager: Killing 2180:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 15:50:42.754   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 15:50:42.807   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
08-17 15:50:42.807   872  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 15:50:42.810   872  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 15:50:42.825  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 15:50:43.242  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:50:43.285  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:50:43.285  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 15:50:43.290   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:50:43.304   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 15:50:43.304   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:50:43.305   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 15:50:43.322   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:50:43.333   372   870 D CommandListener: Setting iface cfg
08-17 15:50:43.333   872  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 15:50:43.349   872  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 15:50:43.352   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 15:50:43.367   872  4049 D DhcpClient: Receive thread started
,08-17 15:50:43.451   872  1306 E native  : do suspend false
,08-17 15:50:43.472   872  1875 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 15:50:43.486   872  4049 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-17 15:50:43.487   872  1875 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-17 15:50:43.492   872  1875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 15:50:43.504   872  4049 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 15:50:43.506   872  1875 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 15:50:43.512   372   870 D CommandListener: Setting iface cfg
,08-17 15:50:43.523   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 15:50:43.528   872  1875 D DhcpClient: Scheduling renewal in 86399s
,08-17 15:50:43.546   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 15:50:43.550   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
08-17 15:50:43.550   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 15:50:43.551   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 15:50:43.555   872  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 15:50:43.576   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 15:50:43.609   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 15:50:43.609   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-17 15:50:43.610   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-17 15:50:43.611   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 15:50:43.612   872  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 15:50:43.629   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 15:50:43.636   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 15:50:43.636   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-17 15:50:43.636   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 15:50:43.637   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:50:43.637   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-17 15:50:43.637   872  1309 D ConnectivityService:    accepting network in place of null
,08-17 15:50:43.638   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 15:50:43.649   872  4048 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136705, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 15:50:43.681   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:50:43.717   872  4047 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:4001:813::200e
,08-17 15:50:43.747   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:50:43.753   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 15:50:43.753   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:50:43.756   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 15:50:43.758   872   889 D Tethering: MasterInitialState.processMessage what=3
08-17 15:50:43.768  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:43.768  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:43.769  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:43.769  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:43.774  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:50:43.775  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:50:43.775  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:43.775  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:50:43.788  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 15:50:43.792  1715  1715 D SystemUpdateService: onCreate
,08-17 15:50:43.795  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 15:50:43.798  1715  4060 I SystemUpdateService: active receiver: enabled
,08-17 15:50:43.802  1715  4060 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 15:50:43.803   872  4047 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:50:43 GMT], X-Android-Received-Millis=[1471441843802], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471441843771]}
,08-17 15:50:43.805   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 15:50:43.805  1715  4060 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-17 15:50:43.805  1715  4060 I SystemUpdateService: now status is 0 (complete)
08-17 15:50:43.805   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-17 15:50:43.806  1715  4060 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 15:50:43.806   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 15:50:43.806  1715  4060 I SystemUpdateService: file has been verified
08-17 15:50:43.806  1715  4060 I SystemUpdateService: OTA package size = 12249756
,08-17 15:50:43.807   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:50:43.817  1715  4060 I SystemUpdateService: showing system update notification
,08-17 15:50:43.823  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 15:50:43.825  1715  2437 I iu.UploadsManager: num queued entries: 0
,08-17 15:50:43.826  1715  2437 I iu.UploadsManager: num updated entries: 0
,08-17 15:50:43.826  1715  2437 I iu.SyncManager: NEXT; no task
,08-17 15:50:43.832  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 15:50:43.833  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:50:43.836  3948  3948 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:50:43.838  1715  1715 D SystemUpdateService: onDestroy
08-17 15:50:43.839  1715  4065 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-17 15:50:43.839  1715  4065 W BaseAppContext: Using Auth Proxy for data requests.
08-17 15:50:43.840  1715  4065 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 15:50:43.844  3948  3948 D SprintDMHelper: simOperator: 
,08-17 15:50:43.844  3948  3948 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:50:43.847  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:50:43.849  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:50:43.875  1501  2037 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 15:50:43.875  1501  2037 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 15:50:43.875  1501  2037 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:50:43.875  1501  2037 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:50:43.895  1715  4065 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-17 15:50:43.973  3882  4067 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 15:50:44.754   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 15:50:45.681   872  3134 D WifiService: setWifiEnabled: false pid=3760, uid=10000
,08-17 15:50:45.681   872  3134 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:50:45.698  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 15:50:45.700   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 15:50:45.700   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 15:50:45.701   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:50:45.701   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:50:45.713   872  1875 D DhcpClient: Clearing IP address
,08-17 15:50:45.713   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:50:45.718  1501  4071 V NativeCrypto: Read error: ssl=0x9a653800: I/O error during system call, Connection timed out
,08-17 15:50:45.720  1501  4071 V NativeCrypto: SSL shutdown failed: ssl=0x9a653800: I/O error during system call, Broken pipe
,08-17 15:50:45.722   372   870 D CommandListener: Setting iface cfg
,08-17 15:50:45.723   872  1942 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-17 15:50:45.723   872  4047 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-17 15:50:45.725   872  4047 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-17 15:50:45.726   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-17 15:50:45.726   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 15:50:45.727   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:50:45.735   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 15:50:45.735   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-17 15:50:45.739   407   407 E Parcel  : Reading a NULL string not supported here.
,08-17 15:50:45.740   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-17 15:50:45.740   872  4049 D DhcpClient: Receive thread stopped
08-17 15:50:45.740   872  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-17 15:50:45.741   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 15:50:45.774   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:50:45.779  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:50:45.796  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 15:50:45.796  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 15:50:45.796  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 15:50:45.796  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:50:45.811   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:50:45.812   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:50:45.812   872  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 15:50:45.813   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:50:45.815  3467  3467 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 15:50:45.815  3467  3467 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 15:50:45.816  3467  3467 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-17 15:50:45.816   872   889 D Tethering: MasterInitialState.processMessage what=3
08-17 15:50:45.822  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:45.823  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:50:45.823  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:45.823  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:45.824  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:45.824  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:50:45.824  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:45.824  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:45.829  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 15:50:45.833  1715  1715 D SystemUpdateService: onCreate
,08-17 15:50:45.834   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 15:50:45.835  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:45.835  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:45.835  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:45.836  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:50:45.836  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:45.836  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:50:45.836  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:45.836  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:50:45.838   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 15:50:45.841  1988  2295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:50:45.847  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 15:50:45.864  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 15:50:45.866  1715  2437 I iu.UploadsManager: num queued entries: 0
08-17 15:50:45.866  1715  2437 I iu.UploadsManager: num updated entries: 0
,08-17 15:50:45.881  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 15:50:45.882  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:50:45.884  3948  3948 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:50:45.886  1715  4082 I SystemUpdateService: active receiver: enabled
08-17 15:50:45.887  3948  3948 D SprintDMHelper: simOperator: 
08-17 15:50:45.887  3948  3948 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:50:45.910   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-17 15:50:45.910   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 15:50:45.910  1715  2437 I iu.SyncManager: NEXT; no task
,08-17 15:50:45.924  3882  4086 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 15:50:45.927  1715  4082 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 15:50:45.935  1715  4082 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 15:50:45.935  1715  4082 I SystemUpdateService: now status is 0 (complete)
08-17 15:50:45.935  1715  4082 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 15:50:45.935  1715  4082 I SystemUpdateService: file has been verified
08-17 15:50:45.936  1715  4082 I SystemUpdateService: OTA package size = 12249756
,08-17 15:50:45.939  1715  4082 I SystemUpdateService: showing system update notification
,08-17 15:50:45.946  1715  1715 D SystemUpdateService: onDestroy
,08-17 15:50:45.948   872  1383 I ActivityManager: Killing 3652:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-17 15:50:48.725  3934  3934 D BluetoothAdapterState: make() - Creating AdapterState
08-17 15:50:48.725   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@87bb8e4:true
,08-17 15:50:48.731  3934  3934 I bt_bluedroid: init
,08-17 15:50:48.731  3934  4091 I BluetoothAdapterState: Entering OffState
,08-17 15:50:48.734  3934  4092 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 15:50:48.735  3934  4092 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:50:48.735  3934  4092 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 15:50:48.735  3934  4092 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 15:50:48.743  3934  3934 I bt_bluedroid: get_profile_interface socket
,08-17 15:50:48.745  3934  3934 I bt_bluedroid: get_profile_interface sdp
,08-17 15:50:48.749  3934  3945 I bt_bluedroid: config_hci_snoop_log
08-17 15:50:48.751   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 15:50:48.755  3934  4095 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:50:48.758  3934  4091 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 15:50:48.759  3934  4095 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:50:48.759  3934  4091 D BluetoothAdapterProperties: Setting state to 14
08-17 15:50:48.760  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-17 15:50:48.761  3934  4091 D BluetoothBondStateMachine: make
,08-17 15:50:48.765  3934  4096 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 15:50:48.769  3934  4091 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:50:48.771  3934  3934 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 15:50:48.774  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:48.775  3934  3934 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:50:48.775  3934  3934 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:50:48.775  3934  3934 D BtGatt.GattService: start()
,08-17 15:50:48.775  3934  3934 I bt_bluedroid: get_profile_interface gatt
,08-17 15:50:48.777  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
08-17 15:50:48.777  3934  3934 D BtGatt.AdvertiseManager: advertise manager created
,08-17 15:50:48.788  3934  3934 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:48.788  3934  3934 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:48.788  3934  3934 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 15:50:48.788  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:48.788  3934  4091 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 15:50:48.789  3934  4091 I bt_bluedroid: enable
08-17 15:50:48.789  3934  4092 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 15:50:48.789  3934  4092 I bt_hci  : start_up
,08-17 15:50:48.800  3934  4092 I bt_vendor: alloc value 0xb39b9189
08-17 15:50:48.800  3934  4092 I bt_vendor: init
08-17 15:50:48.800  3934  4092 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 15:50:48.800  3934  4092 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 15:50:48.908  3934  4092 D bt_hci  : start_up starting async portion
08-17 15:50:48.908  3934  4099 I bt_hci  : event_finish_startup
08-17 15:50:48.909  3934  4099 I bt_hci_h4: hal_open
08-17 15:50:48.909  3934  4099 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 15:50:48.915  3934  4099 I bt_userial_vendor: device fd = 51 open
,08-17 15:50:48.950  3934  4099 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 15:50:48.982  3934  4099 D bt_hwcfg: Chipset BCM4354A2
,08-17 15:50:48.982  3934  4099 D bt_hwcfg: Target name = [BCM4354A2]
08-17 15:50:48.983  3934  4099 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 15:50:49.642  3934  4099 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 15:50:49.644  3934  4099 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 15:50:49.644  3934  4099 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 15:50:49.761  3934  4099 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 15:50:49.762  3934  4099 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 15:50:49.791  3934  4099 I bt_hwcfg: vendor lib fwcfg completed
,08-17 15:50:49.792  3934  4099 I bt_vendor: firmware callback
08-17 15:50:49.792  3934  4099 I bt_hci  : firmware_config_callback
,08-17 15:50:49.803  3934  4101 I bt_btu  : btu_task pending for preload complete event
,08-17 15:50:49.803  3934  4101 I bt_btu_task: Bluetooth chip preload is complete
,08-17 15:50:49.803  3934  4101 I bt_btu  : btu_task received preload complete event
,08-17 15:50:49.815  3934  4101 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 15:50:49.816  3934  4101 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 15:50:49.816  3934  4101 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 15:50:49.816  3934  4101 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 15:50:49.817  3934  4101 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 15:50:49.817  3934  4101 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:50:49.817  3934  4101 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:50:49.818  3934  4101 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:50:49.818  3934  4101 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:50:49.819  3934  4101 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:50:49.819  3934  4101 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:50:49.819  3934  4101 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:50:49.820  3934  4101 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:50:49.820  3934  4101 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:50:49.821  3934  4101 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 15:50:49.953  3934  4101 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-17 15:50:49.953  3934  4101 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-17 15:50:49.965  3934  4095 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 15:50:49.969  3934  4095 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 15:50:49.970  3934  4095 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:50:49.978  3934  4095 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:50:49.980  3934  4095 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:50:49.980  3934  4095 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 15:50:49.981  3934  4095 D bt_hci  : do_postload posting postload work item
08-17 15:50:49.981  3934  4099 I bt_hci  : event_postload
,08-17 15:50:49.981  3934  4099 I bt_vendor: sco_config_cb
,08-17 15:50:49.981  3934  4099 I bt_hci  : sco_config_callback postload finished.
,08-17 15:50:49.984  3934  4095 D bt_bte_conf: Device ID record 1 : primary
08-17 15:50:49.984  3934  4095 D bt_bte_conf:   vendorId            = 000f
,08-17 15:50:49.984  3934  4095 D bt_bte_conf:   vendorIdSource      = 0001
08-17 15:50:49.984  3934  4095 D bt_bte_conf:   product             = 1200
,08-17 15:50:49.985  3934  4095 D bt_bte_conf:   version             = 1436
,08-17 15:50:49.985  3934  4095 D bt_bte_conf:   clientExecutableURL = 
,08-17 15:50:49.985  3934  4095 D bt_bte_conf:   serviceDescription  = 
,08-17 15:50:49.985  3934  4095 D bt_bte_conf:   documentationURL    = 
,08-17 15:50:49.985  3934  4095 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 15:50:49.986  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:49.986  3934  4092 D bt_stack_manager: event_start_up_stack finished
08-17 15:50:49.987  3934  4099 I bt_vendor: low_power_mode_cb
,08-17 15:50:49.987  3934  4091 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-17 15:50:49.988  3934  4091 D BluetoothAdapterProperties: Setting state to 15
08-17 15:50:49.988  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 15:50:49.989  3934  4091 I BluetoothAdapterState: Entering BleOnState
08-17 15:50:49.990  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:49.994  3934  4091 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 15:50:49.994  3934  4091 D BluetoothAdapterProperties: Setting state to 11
08-17 15:50:49.994  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-17 15:50:50.000  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:50.003  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:50.009  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
08-17 15:50:50.010  3934  3934 D HeadsetService: Received start request. Starting profile...
08-17 15:50:50.013  3934  3934 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:50:50.013  3934  3934 D HeadsetStateMachine: make
,08-17 15:50:50.023  3934  4091 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:50:50.024  3934  3934 D HeadsetStateMachine: max_hf_connections = 1
08-17 15:50:50.024  3934  3934 I bt_bluedroid: get_profile_interface handsfree
08-17 15:50:50.024  3934  4095 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-17 15:50:50.025  3934  4095 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 15:50:50.031  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
08-17 15:50:50.031  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:50:50.031  3934  3934 D A2dpService: Received start request. Starting profile...
,08-17 15:50:50.032  3934  3934 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 15:50:50.033  3934  3934 I bt_bluedroid: get_profile_interface avrcp
,08-17 15:50:50.039  3934  3934 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 15:50:50.040  3934  3934 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:50:50.040  3934  3934 D A2dpStateMachine: make
,08-17 15:50:50.043  3934  3934 I bt_bluedroid: get_profile_interface a2dp
,08-17 15:50:50.043  3934  4095 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 15:50:50.048  3934  4110 D A2dpStateMachine: Enter Disconnected: -2
,08-17 15:50:50.048  3934  3934 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 15:50:50.049  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:50.051  3830  3830 D BluetoothInputDevice: Proxy object connected
,08-17 15:50:50.051  3934  3934 D HidService: Received start request. Starting profile...
08-17 15:50:50.052  3934  3934 I bt_bluedroid: get_profile_interface hidhost
08-17 15:50:50.052  3830  3830 D HidProfile: Bluetooth service connected
,08-17 15:50:50.052  3934  3934 D HidService: setHidService(): set to: null
,08-17 15:50:50.052  3934  4095 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-17 15:50:50.052  3934  4095 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 15:50:50.053  3934  3934 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 15:50:50.054  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:50.055  3934  3934 D HealthService: Received start request. Starting profile...
,08-17 15:50:50.057  3934  3934 I bt_bluedroid: get_profile_interface health
,08-17 15:50:50.058  3934  3934 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 15:50:50.059  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:50.060  3830  3830 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 15:50:50.060  3934  3934 D PanService: Received start request. Starting profile...
08-17 15:50:50.061  3934  3934 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:50:50.061  3934  3934 I bt_bluedroid: get_profile_interface pan
,08-17 15:50:50.061  3934  4095 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 15:50:50.061  3830  3830 D PanProfile: Bluetooth service connected
,08-17 15:50:50.067  3934  3934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:50.069  3830  3830 D BluetoothMap: Proxy object connected
,08-17 15:50:50.069  3830  3830 D MapProfile: Bluetooth service connected
,08-17 15:50:50.069  3934  3934 D BluetoothMapService: Received start request. Starting profile...
08-17 15:50:50.069  3934  3934 D BluetoothMapService: start()
08-17 15:50:50.069  3830  3830 D BluetoothMap: getConnectedDevices()
,08-17 15:50:50.071  3830  3830 D BluetoothMap: Bluetooth is Not enabled
,08-17 15:50:50.073  3934  3934 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 15:50:50.074  3934  3934 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 15:50:50.074  3934  3934 D BluetoothMapAppObserver: createReceiver()
,08-17 15:50:50.075  3934  3934 D BluetoothMapAppObserver: initObservers()
08-17 15:50:50.076  3934  3934 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 15:50:50.086  3934  3934 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:50.086  3934  4107 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 15:50:50.086  3934  3934 V BluetoothAdapterState: isTurningOn()=true
08-17 15:50:50.086  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:50.086  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:50.088  3934  3934 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isTurningOn()=true
08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isTurningOn()=true
08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:50:50.089  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isTurningOn()=true
08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isTurningOn()=true
08-17 15:50:50.090  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:50.091  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:50.091  3934  4091 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 15:50:50.091  3934  4091 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:50:50.091  3934  4091 D BluetoothAdapterProperties: State =  11
,08-17 15:50:50.092  3934  4095 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:50:50.092  3934  4095 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:50:50.092  3934  4091 D BluetoothAdapterProperties: Setting state to 12
,08-17 15:50:50.093  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 15:50:50.093   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:50:50.093  3934  4091 I BluetoothAdapterState: Entering OnState
08-17 15:50:50.098  1922  1933 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:50:50.099   872   872 D BluetoothA2dp: Proxy object connected
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:50.100  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:50.100  3830  3841 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:50:50.103  3830  3843 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:50:50.103  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:50:50.103  3830  3841 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:50:50.104   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:50.104   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:50.104  1351  2034 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 15:50:50.106  3934  3934 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 15:50:50.107  1351  1351 D BluetoothInputDevice: Proxy object connected
08-17 15:50:50.107  1351  1351 D HidProfile: Bluetooth service connected
08-17 15:50:50.107  3934  3934 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 15:50:50.108  1351  1363 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:50.108  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:50.108  3830  3843 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:50:50.109  1351  1364 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:50:50.111  3934  3934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:50:50.111  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:50.112  1351  2034 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:50:50.114  3934  3934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:50:50.115  1351  1351 D BluetoothA2dp: Proxy object connected
08-17 15:50:50.116  3934  3934 D ObexServerSockets: Succeed to create listening sockets 
08-17 15:50:50.116  3934  3934 D ObexServerSockets0: startAccept()
08-17 15:50:50.116  3934  3934 D ObexServerSockets0: prepareForNewConnect()
,08-17 15:50:50.117   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:50.118  1351  1364 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:50:50.119  3934  3934 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 15:50:50.119  3934  3934 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 15:50:50.120  3934  4116 D ObexServerSockets0: Accepting socket connection...
08-17 15:50:50.120  3934  4117 D ObexServerSockets0: Accepting socket connection...
08-17 15:50:50.122  1351  1351 D BluetoothMap: Proxy object connected
08-17 15:50:50.122  1351  1351 D MapProfile: Bluetooth service connected
08-17 15:50:50.122  1351  1351 D BluetoothMap: getConnectedDevices()
,08-17 15:50:50.123  1351  2034 D BluetoothPan: onBluetoothStateChange on: true
,08-17 15:50:50.126  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 15:50:50.126  1351  1351 D PanProfile: Bluetooth service connected
,08-17 15:50:50.130   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 15:50:50.131  3934  3934 D BluetoothMapService: onReceive
,08-17 15:50:50.131  3934  3934 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:50:50.131  3934  3934 D BluetoothMapService: STATE_ON
08-17 15:50:50.132  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:50.134  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:50.135  3830  3830 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-17 15:50:50.139  3830  3830 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 15:50:50.145  3830  3830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:50:50.151  3830  3830 D BluetoothA2dp: Proxy object connected
,08-17 15:50:50.152  3934  3934 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 15:50:50.153  3934  3934 D ObexServerSockets0: prepareForNewConnect()
,08-17 15:50:50.158  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:50:50.162  3830  3830 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:50:50.174  3830  3830 D BluetoothPbap: Proxy object connected
,08-17 15:50:50.174  3830  3830 D PbapServerProfile: Bluetooth service connected
08-17 15:50:50.175  1351  1351 D BluetoothPbap: Proxy object connected
,08-17 15:50:50.175  1351  1351 D PbapServerProfile: Bluetooth service connected
,08-17 15:50:50.182  3934  4122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:50:50.204   872   872 D BluetoothHeadset: Proxy object connected
,08-17 15:50:50.204   872   889 D BluetoothHeadset: Proxy object connected
08-17 15:50:50.204   872   872 D BluetoothHeadset: Proxy object connected
08-17 15:50:50.204   872   889 D BluetoothHeadset: Proxy object connected
08-17 15:50:50.204   872   872 D BluetoothHeadset: Proxy object connected
,08-17 15:50:50.204  1351  1364 D BluetoothHeadset: Proxy object connected
08-17 15:50:50.204  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-17 15:50:50.205  1922  2056 D BluetoothHeadset: Proxy object connected
,08-17 15:50:50.208  3934  4126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:50:50.208  1351  2034 D BluetoothHeadset: Proxy object connected
,08-17 15:50:50.209  1351  1351 D HeadsetProfile: Bluetooth service connected
08-17 15:50:50.210  3934  4126 I BtOppRfcommListener: Accept thread started.
,08-17 15:50:50.218   872   889 D BluetoothHeadset: Proxy object connected
,08-17 15:50:50.242  3830  3841 D BluetoothHeadset: Proxy object connected
,08-17 15:50:50.244  3830  3830 D HeadsetProfile: Bluetooth service connected
,08-17 15:50:51.641   872  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-17 15:50:51.695  3934  4091 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 15:50:51.696  3934  4091 D BluetoothAdapterProperties: Setting state to 13
08-17 15:50:51.696  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 15:50:51.698  3934  4091 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 15:50:51.710  3934  3934 D BluetoothMapService: onReceive
,08-17 15:50:51.710  3934  3934 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:50:51.711  3934  3934 D BluetoothMapService: STATE_TURNING_OFF
,08-17 15:50:51.711  3934  3934 D BluetoothMapService: MAP Service closeService in
,08-17 15:50:51.712  3934  4091 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:50:51.712  3934  3934 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 15:50:51.712  3934  3934 D ObexServerSockets0: shutdown(block = true)
08-17 15:50:51.713  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 15:50:51.714  3934  4095 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:51.714  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:51.714  3934  4091 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 15:50:51.714  3934  4116 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 15:50:51.715  3934  3934 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 15:50:51.716  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:51.716  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:50:51.716  3934  4117 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 15:50:51.718  3934  4104 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 15:50:51.719  3934  3934 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 15:50:51.720  3934  3934 I BtOppRfcommListener: stopping Accept Thread
08-17 15:50:51.721  3934  4126 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 15:50:51.722  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:51.722  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:50:51.723  3934  4126 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 15:50:51.724  3760  3760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:50:51.725  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:51.727  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:51.728  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:51.730  3934  3934 D HeadsetService: Received stop request...Stopping profile...
08-17 15:50:51.732  3830  3830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 15:50:51.732   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:51.732   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:51.732   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:51.733  3934  3934 D A2dpService: Received stop request...Stopping profile...
,08-17 15:50:51.733  1351  1363 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:51.733  1351  1351 D HeadsetProfile: Bluetooth service disconnected
08-17 15:50:51.733  3934  4110 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:50:51.735  3830  3843 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:51.736  1922  2082 D BluetoothHeadset: Proxy object disconnected
08-17 15:50:51.737   872   872 D BluetoothA2dp: Proxy object disconnected
08-17 15:50:51.738  1351  1351 D BluetoothA2dp: Proxy object disconnected
08-17 15:50:51.739  3934  3934 D HidService: Received stop request...Stopping profile...
,08-17 15:50:51.739  3934  3934 D HidService: Stopping Bluetooth HidService
08-17 15:50:51.740  1351  1351 D BluetoothInputDevice: Proxy object disconnected
08-17 15:50:51.740  1351  1351 D HidProfile: Bluetooth service disconnected
08-17 15:50:51.740  3934  3934 D HealthService: Received stop request...Stopping profile...
,08-17 15:50:51.742  3934  3934 D PanService: Received stop request...Stopping profile...
08-17 15:50:51.743  1351  1351 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 15:50:51.743  1351  1351 D PanProfile: Bluetooth service disconnected
,08-17 15:50:51.745  3934  3934 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 15:50:51.745  3934  3934 D BluetoothMapService: stop()
,08-17 15:50:51.746  3934  3934 D BluetoothMapAppObserver: deinitObservers()
,08-17 15:50:51.746  3934  3934 D BluetoothMapAppObserver: removeReceiver()
08-17 15:50:51.746  3830  3830 D DockEventReceiver: finishStartingService: stopping service
08-17 15:50:51.747  1351  1351 D BluetoothMap: Proxy object disconnected
08-17 15:50:51.747  1351  1351 D MapProfile: Bluetooth service disconnected
08-17 15:50:51.748  3934  3934 V BluetoothAdapterState: isTurningOff()=true
,08-17 15:50:51.748  3934  3934 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:51.748  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:51.748  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:51.750  3934  3934 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 15:50:51.750  3934  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:51.750  3934  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:51.750  3934  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:51.750  3934  4095 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 15:50:51.751  3934  4095 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-17 15:50:51.751  3934  3934 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 15:50:51.751  3934  3934 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:51.751  3934  3934 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:51.748  3830  3830 D HeadsetProfile: Bluetooth service disconnected
08-17 15:50:51.751  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:51.751  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:51.752  3934  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 15:50:51.752  3934  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 15:50:51.753  3934  4101 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:50:51.752  3830  3830 D BluetoothA2dp: Proxy object disconnected
08-17 15:50:51.753  3934  4101 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:50:51.753  3934  4101 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:50:51.753  3934  4101 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-17 15:50:51.753  3934  4095 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 15:50:51.753  3830  3830 D BluetoothInputDevice: Proxy object disconnected
,08-17 15:50:51.753  3830  3830 D HidProfile: Bluetooth service disconnected
,08-17 15:50:51.754  3830  3830 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 15:50:51.755  3830  3830 D PanProfile: Bluetooth service disconnected
,08-17 15:50:51.755  3934  3934 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:51.755  3934  3934 V BluetoothAdapterState: isTurningOn()=false
,08-17 15:50:51.755  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:51.755  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:51.755  3934  3934 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:50:51.755  3934  3934 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:50:51.756  3934  3934 V BluetoothAdapterState: isTurningOff()=true
,08-17 15:50:51.756  3934  3934 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:51.756  3934  4095 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 15:50:51.756  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:51.756  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:51.756  3934  3934 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-17 15:50:51.756  3830  3830 D BluetoothMap: Proxy object disconnected
,08-17 15:50:51.756  3830  3830 D MapProfile: Bluetooth service disconnected
08-17 15:50:51.756  3934  4095 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 15:50:51.756  3934  3934 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:50:51.757  3934  3934 V BluetoothAdapterState: isTurningOff()=true
08-17 15:50:51.757  3934  3934 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:51.757  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:51.757  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:51.757  3934  3934 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:50:51.758  3934  3934 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 15:50:51.758  3934  3934 D BluetoothMapService: MAP Service closeService in
08-17 15:50:51.759  3934  3934 V BluetoothAdapterState: isTurningOff()=true
,08-17 15:50:51.759  3934  3934 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:51.759  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:51.759  3934  3934 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:51.759  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:50:51.759  3934  4091 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-17 15:50:51.760  3934  4091 D BluetoothAdapterProperties: Setting state to 15
08-17 15:50:51.760  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 15:50:51.760  3934  4091 I BluetoothAdapterState: Entering BleOnState
08-17 15:50:51.760   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:50:51.760  3934  3934 D BluetoothMapService: cleanup()
08-17 15:50:51.760  3934  3934 D BluetoothMapService: MAP Service closeService in
08-17 15:50:51.760  1922  1933 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:51.761  3830  3841 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 15:50:51.765  1351  1351 D BluetoothPbap: Proxy object disconnected
08-17 15:50:51.765  1351  1351 D PbapServerProfile: Bluetooth service disconnected
08-17 15:50:51.765  3830  3843 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 15:50:51.768  3830  3841 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:50:51.769  3830  3843 D BluetoothPan: onBluetoothStateChange on: false
,08-17 15:50:51.769   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:51.769  3830  3841 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:51.769   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:51.769  1351  1363 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:50:51.770  1351  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 15:50:51.770  3830  3843 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:50:51.773  1351  2034 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 15:50:51.773  1351  1363 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 15:50:51.774   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:50:51.774  1351  1364 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 15:50:51.775  1351  2034 D BluetoothPan: onBluetoothStateChange on: false
,08-17 15:50:51.775  3934  4091 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-17 15:50:51.775  3934  4091 D BluetoothAdapterProperties: Setting state to 16
,08-17 15:50:51.775  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-17 15:50:51.776  3934  4091 D BluetoothAdapterProperties: onBleDisable
08-17 15:50:51.776  3934  4091 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:50:51.776  3934  4092 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-17 15:50:51.779  3934  4101 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 15:50:51.779  3934  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 15:50:51.779  3934  4095 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:50:51.780  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:51.781  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:51.782  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:51.783  3830  3830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 15:50:51.783  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:51.788  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:50:51.791  3830  3830 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:50:51.979  3934  4095 I bt_hci  : shut_down
,08-17 15:50:51.989  3934  4099 I bt_vendor: low_power_mode_cb
,08-17 15:50:51.992  3934  4099 D bt_hwcfg: hw_epilog_process
,08-17 15:50:52.009  3934  4099 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 15:50:52.009  3934  4099 I bt_vendor: epilog_cb
08-17 15:50:52.010  3934  4099 I bt_hci  : epilog_finished_callback
,08-17 15:50:52.015  3934  4095 I bt_hci_h4: hal_close
,08-17 15:50:52.017  3934  4095 I bt_userial_vendor: device fd = 51 close
,08-17 15:50:52.134  3934  4092 D bt_stack_manager: event_shut_down_stack finished.
,08-17 15:50:52.135  3934  4091 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 15:50:52.140  3934  4091 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-17 15:50:52.141  3934  3934 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:50:52.142  3934  3934 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 15:50:52.142  3934  3934 D BtGatt.GattService: stop()
08-17 15:50:52.143  3934  3934 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 15:50:52.148  3934  3934 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:52.148  3934  3934 V BluetoothAdapterState: isTurningOn()=false
,08-17 15:50:52.148  3934  3934 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:52.149  3934  3934 V BluetoothAdapterState: isBleTurningOff()=true
,08-17 15:50:52.149  3934  4091 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 15:50:52.150  3934  4091 D BluetoothAdapterProperties: Setting state to 10
08-17 15:50:52.151  3934  4091 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 15:50:52.153  3934  4091 I BluetoothAdapterState: Entering OffState
08-17 15:50:52.154   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 15:50:52.180  3934  3934 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 15:50:52.180  3934  3934 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 15:50:52.180  3934  4092 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 15:50:52.186  3934  4092 D bt_stack_manager: event_clean_up_stack finished.
,08-17 15:50:52.187  3934  3934 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 15:50:52.193  3934  3934 I art     : System.exit called, status: 0
,08-17 15:50:52.194  3934  3934 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 15:50:52.270   872  1699 I ActivityManager: Process com.android.bluetooth (pid 3934) has died
,08-17 15:50:54.692  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:50:54.693  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:50:57.150   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 15:50:57.162  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-17 15:50:57.174   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 15:50:57.174   872   892 I Adreno  : Build Date                       : 10/20/15
08-17 15:50:57.174   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 15:50:57.174   872   892 I Adreno  : Local Branch                     : M14
08-17 15:50:57.174   872   892 I Adreno  : Remote Branch                    : 
08-17 15:50:57.174   872   892 I Adreno  : Remote Branch                    : 
08-17 15:50:57.174   872   892 I Adreno  : Reconstruct Branch               : 
,08-17 15:50:57.211   282   895 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (303 us)
,08-17 15:50:57.701  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:50:57.701  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7a4b91 added. We now have 6 listener(s)
,08-17 15:50:57.703  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:57.708  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:50:57.709  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33e8af6 added. We now have 7 listener(s)
08-17 15:50:57.709  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:50:57.711  3760  3810 I System.out: IsBluetoothEnabled
,08-17 15:50:57.723  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:57.764   872   889 I ActivityManager: Start proc 4141:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 15:50:57.856  3760  3760 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 15:50:57.856  3760  3760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 15:50:57.899  3760  3760 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6a3a6d1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3c4ef7, 16908290=android.view.AbsSavedState$1@3c4ef7}, android:focusedViewId=100}]}]
,08-17 15:50:57.899  3760  3760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 15:50:57.899  3760  3760 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 15:50:57.899  3760  3760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-17 15:50:57.900   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 15:50:57.906   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 15:50:57.908  4141  4141 D AdapterServiceConfig: Adding HeadsetService
,08-17 15:50:57.908  4141  4141 D AdapterServiceConfig: Adding A2dpService
08-17 15:50:57.909  4141  4141 D AdapterServiceConfig: Adding HidService
08-17 15:50:57.909  4141  4141 D AdapterServiceConfig: Adding HealthService
,08-17 15:50:57.909  4141  4141 D AdapterServiceConfig: Adding PanService
,08-17 15:50:57.910   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-17 15:50:57.910   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-17 15:50:57.911   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 15:50:57.916  4141  4141 D AdapterServiceConfig: Adding GattService
08-17 15:50:57.916  4141  4141 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 15:50:57.936   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@886e9a4:true
,08-17 15:50:57.937  4141  4141 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 15:50:57.939  4141  4141 I bt_bluedroid: init
08-17 15:50:57.940  4141  4154 I BluetoothAdapterState: Entering OffState
,08-17 15:50:57.941  4141  4155 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 15:50:57.941  4141  4155 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:50:57.941  4141  4155 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 15:50:57.941  4141  4155 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 15:50:57.942  4141  4141 I bt_bluedroid: get_profile_interface socket
,08-17 15:50:57.944  4141  4141 I bt_bluedroid: get_profile_interface sdp
08-17 15:50:57.944  4141  4158 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:50:57.945  4141  4158 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:50:57.946  4141  4151 I bt_bluedroid: config_hci_snoop_log
,08-17 15:50:57.947   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 15:50:57.950  4141  4154 D BluetoothAdapterState: Current state: OFF, message: 0
08-17 15:50:57.951  4141  4154 D BluetoothAdapterProperties: Setting state to 14
08-17 15:50:57.951  4141  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-17 15:50:57.953  4141  4154 D BluetoothBondStateMachine: make
,08-17 15:50:57.954  4141  4159 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 15:50:57.958  4141  4154 I BluetoothAdapterState: Entering PendingCommandState
08-17 15:50:57.958  4141  4141 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 15:50:57.960  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
08-17 15:50:57.961  4141  4141 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 15:50:57.961  4141  4141 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:50:57.961  4141  4141 D BtGatt.GattService: start()
08-17 15:50:57.961  4141  4141 I bt_bluedroid: get_profile_interface gatt
08-17 15:50:57.962  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
08-17 15:50:57.962  4141  4141 D BtGatt.AdvertiseManager: advertise manager created
,08-17 15:50:57.967  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:57.968  4141  4141 V BluetoothAdapterState: isTurningOn()=false
08-17 15:50:57.968  4141  4141 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 15:50:57.968  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:57.968  4141  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 15:50:57.969  4141  4154 I bt_bluedroid: enable
08-17 15:50:57.969  4141  4155 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 15:50:57.969  4141  4155 I bt_hci  : start_up
,08-17 15:50:57.974  4141  4155 I bt_vendor: alloc value 0xb3a1c189
,08-17 15:50:57.974  4141  4155 I bt_vendor: init
08-17 15:50:57.974  4141  4155 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 15:50:57.974  4141  4155 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 15:50:58.083  4141  4155 D bt_hci  : start_up starting async portion
,08-17 15:50:58.084  4141  4162 I bt_hci  : event_finish_startup
,08-17 15:50:58.085  4141  4162 I bt_hci_h4: hal_open
08-17 15:50:58.086  4141  4162 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 15:50:58.095  4141  4162 I bt_userial_vendor: device fd = 51 open
,08-17 15:50:58.125  4141  4162 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 15:50:58.150   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 15:50:58.155   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 15:50:58.156  4141  4162 D bt_hwcfg: Chipset BCM4354A2
08-17 15:50:58.157  4141  4162 D bt_hwcfg: Target name = [BCM4354A2]
08-17 15:50:58.157  4141  4162 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
08-17 15:50:58.156   872  1332 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,08-17 15:50:58.162   872   892 I DreamManagerService: Entering dreamland.
,08-17 15:50:58.163   872   892 I PowerManagerService: Dozing...
,08-17 15:50:58.164   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 15:50:58.216   376  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 15:50:58.216   376  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 15:50:58.221   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:50:58.225   872  1306 E native  : do suspend false
,08-17 15:50:58.244  1910  4165 D NfcService: Discovery configuration equal, not updating.
,08-17 15:50:58.265   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 15:50:58.270   872  1306 E native  : do suspend true
,08-17 15:50:58.354   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 15:50:58.355   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 15:50:58.803  4141  4162 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-17 15:50:58.804  4141  4162 D bt_hwcfg: Settlement delay -- 100 ms
08-17 15:50:58.805  4141  4162 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 15:50:58.921  4141  4162 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-17 15:50:58.922  4141  4162 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 15:50:58.952  4141  4162 I bt_hwcfg: vendor lib fwcfg completed
,08-17 15:50:58.952  4141  4162 I bt_vendor: firmware callback
08-17 15:50:58.953  4141  4162 I bt_hci  : firmware_config_callback
,08-17 15:50:58.965  4141  4169 I bt_btu  : btu_task pending for preload complete event
,08-17 15:50:58.966  4141  4169 I bt_btu_task: Bluetooth chip preload is complete
08-17 15:50:58.966  4141  4169 I bt_btu  : btu_task received preload complete event
,08-17 15:50:58.978  4141  4169 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 15:50:58.978  4141  4169 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 15:50:58.978  4141  4169 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 15:50:58.979  4141  4169 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 15:50:58.979  4141  4169 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 15:50:58.979  4141  4169 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:50:58.979  4141  4169 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:50:58.980  4141  4169 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:50:58.981  4141  4169 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:50:58.981  4141  4169 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:50:58.981  4141  4169 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:50:58.981  4141  4169 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:50:58.982  4141  4169 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:50:58.982  4141  4169 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:50:58.982  4141  4169 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 15:50:59.119  4141  4169 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d,
08-17 15:50:59.119  4141  4169 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
,08-17 15:50:59.146  4141  4158 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-17 15:50:59.151  4141  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 15:50:59.151  4141  4158 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 15:50:59.155  4141  4158 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 15:50:59.158  4141  4158 D BluetoothAdapterProperties: Scan Mode:20
,08-17 15:50:59.158  4141  4158 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 15:50:59.159  4141  4158 D bt_hci  : do_postload posting postload work item
,08-17 15:50:59.160  4141  4162 I bt_hci  : event_postload
,08-17 15:50:59.160  4141  4162 I bt_vendor: sco_config_cb
,08-17 15:50:59.161  4141  4162 I bt_hci  : sco_config_callback postload finished.
,08-17 15:50:59.164  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:50:59.164  4141  4158 D bt_bte_conf: Device ID record 1 : primary
,08-17 15:50:59.164  4141  4158 D bt_bte_conf:   vendorId            = 000f
08-17 15:50:59.165  4141  4158 D bt_bte_conf:   vendorIdSource      = 0001
08-17 15:50:59.165  4141  4158 D bt_bte_conf:   product             = 1200
,08-17 15:50:59.165  4141  4158 D bt_bte_conf:   version             = 1436
08-17 15:50:59.165  4141  4158 D bt_bte_conf:   clientExecutableURL = 
,08-17 15:50:59.166  4141  4158 D bt_bte_conf:   serviceDescription  = 
08-17 15:50:59.166  4141  4158 D bt_bte_conf:   documentationURL    = 
08-17 15:50:59.166  4141  4158 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 15:50:59.167  4141  4155 D bt_stack_manager: event_start_up_stack finished
08-17 15:50:59.168  4141  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 15:50:59.169  4141  4154 D BluetoothAdapterProperties: Setting state to 15
,08-17 15:50:59.169  4141  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 15:50:59.170  4141  4154 I BluetoothAdapterState: Entering BleOnState
,08-17 15:50:59.173  4141  4162 I bt_vendor: low_power_mode_cb
,08-17 15:50:59.176  4141  4154 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 15:50:59.176  4141  4154 D BluetoothAdapterProperties: Setting state to 11
08-17 15:50:59.177  4141  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 15:50:59.185  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:59.186  4141  4141 D HeadsetService: Received start request. Starting profile...
08-17 15:50:59.190  4141  4141 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:50:59.191  4141  4141 D HeadsetStateMachine: make
08-17 15:50:59.192  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:59.205  4141  4141 D HeadsetStateMachine: max_hf_connections = 1
,08-17 15:50:59.205  4141  4141 I bt_bluedroid: get_profile_interface handsfree
08-17 15:50:59.205  4141  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 15:50:59.205  4141  4158 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 15:50:59.209  4141  4154 I BluetoothAdapterState: Entering PendingCommandState
,08-17 15:50:59.211  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:59.213  4141  4141 D A2dpService: Received start request. Starting profile...
,08-17 15:50:59.214  4141  4141 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 15:50:59.214  4141  4141 I bt_bluedroid: get_profile_interface avrcp
,08-17 15:50:59.221  4141  4141 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 15:50:59.221  4141  4141 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:50:59.221  4141  4141 D A2dpStateMachine: make
,08-17 15:50:59.223  4141  4141 I bt_bluedroid: get_profile_interface a2dp
,08-17 15:50:59.223  4141  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 15:50:59.228  4141  4178 D A2dpStateMachine: Enter Disconnected: -2
,08-17 15:50:59.230  4141  4141 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 15:50:59.231  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:59.232  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:50:59.232  4141  4141 D HidService: Received start request. Starting profile...
,08-17 15:50:59.233  4141  4141 I bt_bluedroid: get_profile_interface hidhost,
08-17 15:50:59.233  4141  4158 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
08-17 15:50:59.233  4141  4141 D HidService: setHidService(): set to: null
,08-17 15:50:59.233  4141  4158 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 15:50:59.235  4141  4141 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 15:50:59.235  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:59.236  4141  4141 D HealthService: Received start request. Starting profile...,
08-17 15:50:59.238  4141  4141 I bt_bluedroid: get_profile_interface health
,08-17 15:50:59.239  4141  4141 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 15:50:59.239  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:59.240  4141  4141 D PanService: Received start request. Starting profile...
,08-17 15:50:59.240  4141  4141 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:50:59.240  4141  4141 I bt_bluedroid: get_profile_interface pan
,08-17 15:50:59.241  4141  4158 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 15:50:59.246  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
,08-17 15:50:59.247  4141  4141 D BluetoothMapService: Received start request. Starting profile...
,08-17 15:50:59.247  4141  4141 D BluetoothMapService: start()
,08-17 15:50:59.250  4141  4141 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 15:50:59.251  4141  4141 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 15:50:59.252  4141  4141 D BluetoothMapAppObserver: createReceiver()
,08-17 15:50:59.253  4141  4141 D BluetoothMapAppObserver: initObservers()
,08-17 15:50:59.253  4141  4141 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 15:50:59.262  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:59.262  4141  4141 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:50:59.262  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:59.263  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:59.265  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,08-17 15:50:59.265  4141  4141 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:50:59.265  4141  4175 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 15:50:59.265  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:59.265  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:59.266  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:59.266  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-17 15:50:59.266  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 15:50:59.266  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isTurningOn()=true
,08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-17 15:50:59.267  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-17 15:50:59.268  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-17 15:50:59.268  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 15:50:59.268  4141  4154 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 15:50:59.268  4141  4154 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:50:59.268  4141  4154 D BluetoothAdapterProperties: State =  11
08-17 15:50:59.271  4141  4158 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:50:59.271  4141  4158 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:50:59.271  4141  4154 D BluetoothAdapterProperties: Setting state to 12
08-17 15:50:59.271  4141  4154 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 15:50:59.272   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:50:59.273  1922  2082 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:59.273  4141  4154 I BluetoothAdapterState: Entering OnState
,08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:59.275  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:50:59.275  3830  3843 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 15:50:59.276   872   872 D BluetoothA2dp: Proxy object connected
08-17 15:50:59.277  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:59.278  3830  3841 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:50:59.280  3830  4133 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:50:59.282  4141  4141 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 15:50:59.282  3830  4133 D BluetoothPan: onBluetoothStateChange on: true
,08-17 15:50:59.282  4141  4141 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 15:50:59.283   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:59.283  3830  3841 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:59.284   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:59.284  1351  1363 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:50:59.284  4141  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:50:59.286  1351  4153 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:50:59.286  3830  3830 D BluetoothMap: Proxy object connected
08-17 15:50:59.286  3830  3830 D MapProfile: Bluetooth service connected
,08-17 15:50:59.287  4141  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:50:59.286  3830  3830 D BluetoothMap: getConnectedDevices()
,08-17 15:50:59.287  3830  3843 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:50:59.288  4141  4141 D ObexServerSockets: Succeed to create listening sockets 
08-17 15:50:59.288  4141  4141 D ObexServerSockets0: startAccept()
08-17 15:50:59.288  4141  4141 D ObexServerSockets0: prepareForNewConnect()
,08-17 15:50:59.289  1351  2034 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 15:50:59.290  4141  4141 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 15:50:59.290  4141  4141 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-17 15:50:59.291  4141  4185 D ObexServerSockets0: Accepting socket connection...
08-17 15:50:59.292  4141  4186 D ObexServerSockets0: Accepting socket connection...
,08-17 15:50:59.293  1351  1351 D BluetoothInputDevice: Proxy object connected
08-17 15:50:59.293  1351  1351 D HidProfile: Bluetooth service connected
08-17 15:50:59.293  1351  1363 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:50:59.295   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:50:59.295  1351  1351 D BluetoothA2dp: Proxy object connected
08-17 15:50:59.295  3830  3830 D BluetoothA2dp: Proxy object connected
08-17 15:50:59.295  1351  2034 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 15:50:59.297  1351  1351 D BluetoothMap: Proxy object connected
08-17 15:50:59.297  3830  3830 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:50:59.297  1351  1351 D MapProfile: Bluetooth service connected
08-17 15:50:59.297  3830  3830 D PanProfile: Bluetooth service connected
08-17 15:50:59.297  1351  1351 D BluetoothMap: getConnectedDevices()
,08-17 15:50:59.297  3830  3830 D BluetoothInputDevice: Proxy object connected
08-17 15:50:59.297  1351  4153 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:50:59.297  3830  3830 D HidProfile: Bluetooth service connected
,08-17 15:50:59.298  1351  1351 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:50:59.298  1351  1351 D PanProfile: Bluetooth service connected
08-17 15:50:59.299   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 15:50:59.301  4141  4141 D BluetoothMapService: onReceive
08-17 15:50:59.301  4141  4141 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:50:59.301  4141  4141 D BluetoothMapService: STATE_ON
08-17 15:50:59.301  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:59.306  3830  3830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 15:50:59.314  3830  3830 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:50:59.314  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:50:59.323  3830  3830 D BluetoothPbap: Proxy object connected
,08-17 15:50:59.323  3830  3830 D PbapServerProfile: Bluetooth service connected
,08-17 15:50:59.325  1351  1351 D BluetoothPbap: Proxy object connected
,08-17 15:50:59.325  1351  1351 D PbapServerProfile: Bluetooth service connected
,08-17 15:50:59.328  4141  4141 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 15:50:59.328  4141  4141 D ObexServerSockets0: prepareForNewConnect()
,08-17 15:50:59.332  4141  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:50:59.351  4141  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:50:59.353  4141  4194 I BtOppRfcommListener: Accept thread started.
,08-17 15:50:59.375   872   872 D BluetoothHeadset: Proxy object connected
,08-17 15:50:59.375   872   872 D BluetoothHeadset: Proxy object connected
,08-17 15:50:59.375   872   872 D BluetoothHeadset: Proxy object connected
08-17 15:50:59.375  1351  1363 D BluetoothHeadset: Proxy object connected
08-17 15:50:59.375  1351  1351 D HeadsetProfile: Bluetooth service connected
08-17 15:50:59.376  3830  3841 D BluetoothHeadset: Proxy object connected
08-17 15:50:59.376  3830  3830 D HeadsetProfile: Bluetooth service connected
08-17 15:50:59.377  1922  1933 D BluetoothHeadset: Proxy object connected
,08-17 15:50:59.384   872   889 D BluetoothHeadset: Proxy object connected
08-17 15:50:59.384  3830  3843 D BluetoothHeadset: Proxy object connected
,08-17 15:50:59.385   872   889 D BluetoothHeadset: Proxy object connected
08-17 15:50:59.385  3830  3830 D HeadsetProfile: Bluetooth service connected
,08-17 15:50:59.387  1351  2034 D BluetoothHeadset: Proxy object connected
08-17 15:50:59.387  1351  1351 D HeadsetProfile: Bluetooth service connected
,08-17 15:50:59.394   872   889 D BluetoothHeadset: Proxy object connected
,08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:59.746  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:50:59.753  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:59.756  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:50:59.756  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c71164 added. We now have 8 listener(s)
08-17 15:50:59.757  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:50:59.762   872  1977 D WifiService: setWifiEnabled: false pid=3760, uid=10000
,08-17 15:50:59.762   872  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:50:59.775  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:50:59.776   872  1699 D WifiService: setWifiEnabled: true pid=3760, uid=10000
,08-17 15:50:59.776   872  1699 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:50:59.791   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:50:59.812  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:50:59.820  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:50:59.821   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-17 15:50:59.822   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 15:50:59.823   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-17 15:50:59.824   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 15:50:59.824   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 15:50:59.824   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 15:50:59.824   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 15:50:59.838   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 15:50:59.838   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.05 delta 1000 -> 1000
08-17 15:50:59.839   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 15:50:59.840   372   870 D CommandListener: Setting iface cfg
,08-17 15:50:59.849   872  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-17 15:50:59.849   872  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 15:50:59.850   872  1306 E native  : do suspend true
,08-17 15:50:59.859   872  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 15:50:59.864   872  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 15:50:59.865   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 15:50:59.865   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:50:59.872   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 15:50:59.921   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 15:50:59.941  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 15:51:00.384  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:51:00.436  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 15:51:00.436  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 15:51:00.439   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 15:51:00.445   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 15:51:00.445   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:51:00.446   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 15:51:00.465   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 15:51:00.476   372   870 D CommandListener: Setting iface cfg
,08-17 15:51:00.477   872  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 15:51:00.486   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 15:51:00.500   872  4202 D DhcpClient: Receive thread started
,08-17 15:51:00.587   872  1306 E native  : do suspend false
,08-17 15:51:00.609   872  1875 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 15:51:00.622   872  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-17 15:51:00.623   872  1875 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-17 15:51:00.627   872  1875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 15:51:00.639   872  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 15:51:00.641   872  1875 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 15:51:00.646   372   870 D CommandListener: Setting iface cfg
,08-17 15:51:00.657   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 15:51:00.658   872  1875 D DhcpClient: Scheduling renewal in 86399s
,08-17 15:51:00.661   872  1306 E native  : do suspend true,
,08-17 15:51:00.677   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 15:51:00.678   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 15:51:00.679   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 15:51:00.680   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 15:51:00.681   872  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 15:51:00.740   872  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 15:51:00.740   872  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 15:51:00.744   872  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 15:51:00.746   872  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 15:51:00.750   872  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 15:51:00.774   872  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 15:51:00.786   872  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 15:51:00.787   872  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-17 15:51:00.787   872  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-17 15:51:00.788   872  1309 D ConnectivityService:    accepting network in place of null
,08-17 15:51:00.788   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-17 15:51:00.789   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 15:51:00.790   872  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:00.796  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:51:00.798  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:51:00.802  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 15:51:00.803  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 15:51:00.805  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6a3a6d1 Bundle[{}]
,08-17 15:51:00.805   872  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153861, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 15:51:00.806  3760  3810 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 15:51:00.806  3760  3810 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 15:51:00.807  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 15:51:00.807  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 15:51:00.808  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 15:51:00.808  3760  3810 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 15:51:00.813  3760  3810 I System.out: Running OutgoingSocketThread
08-17 15:51:00.814  3760  4207 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
,08-17 15:51:00.815  3760  4207 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41717
08-17 15:51:00.815  3760  4207 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 15:51:00.830   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:51:00.861   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 15:51:00.866   872  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-17 15:51:00.866   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:51:00.870   872  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-17 15:51:00.874   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:00.893  3760  3760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:51:00.896  3760  3760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:51:00.904  1715  1715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 15:51:00.907  1715  1715 D SystemUpdateService: onCreate
,08-17 15:51:00.911  1715  1715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 15:51:00.922  1715  4212 I SystemUpdateService: active receiver: enabled
,08-17 15:51:00.928  1715  4212 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 15:51:00.931  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 15:51:00.937  1715  2437 I iu.UploadsManager: num queued entries: 0
,08-17 15:51:00.937  1715  2437 I iu.UploadsManager: num updated entries: 0
,08-17 15:51:00.938  1715  2437 I iu.SyncManager: NEXT; no task
,08-17 15:51:00.995  1715  4212 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 15:51:00.995  1715  4212 I SystemUpdateService: now status is 0 (complete)
08-17 15:51:00.996  1715  4212 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 15:51:00.996  1715  4212 I SystemUpdateService: file has been verified
,08-17 15:51:01.004  1715  4212 I SystemUpdateService: OTA package size = 12249756
,08-17 15:51:01.007  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 15:51:01.009  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 15:51:01.013  1715  4215 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 15:51:01.013  1715  4215 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 15:51:01.016  1715  4215 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 15:51:01.024  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:51:01.025  3948  3948 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:51:01.026  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 15:51:01.037  3948  3948 D SprintDMHelper: simOperator: 
,08-17 15:51:01.037  3948  3948 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 15:51:01.055  1715  4212 I SystemUpdateService: showing system update notification
,08-17 15:51:01.080  1501  2951 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-17 15:51:01.080  1501  2951 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 15:51:01.080  1501  2951 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 15:51:01.080  1501  2951 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 15:51:01.096  1715  1715 D SystemUpdateService: onDestroy
,08-17 15:51:01.100  1715  4215 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-17 15:51:01.172  3882  4217 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 15:51:01.206   872  1383 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,08-17 15:51:01.224   872   883 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,08-17 15:51:01.228   872  1700 D ConnectivityService: reportNetworkConnectivity(102, true) by 10011
,08-17 15:51:01.578   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:813::200e
,08-17 15:51:01.650   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:51:01 GMT], X-Android-Received-Millis=[1471441861647], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471441861622]}
08-17 15:51:01.656   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10011
08-17 15:51:01.656   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 15:51:01.657   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 15:51:01.658   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 15:51:01.658   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:813::200e
08-17 15:51:01.667   872  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:51:01.688   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:51:01 GMT], X-Android-Received-Millis=[1471441861686], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471441861661]}
,08-17 15:51:01.691   872  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 15:51:01.691   872  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-17 15:51:01.816  3760  3810 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,08-17 15:51:01.817  3760  3810 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,08-17 15:51:01.826  3760  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,08-17 15:51:01.828  3760  3810 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 15:51:01.829  3760  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,08-17 15:51:01.835  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:51:01.835  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a670fcd added. We now have 2 listener(s)
,08-17 15:51:01.837  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:51:01.837  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:01.837  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:01.838  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:01.838  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a406082 added. We now have 9 listener(s)
08-17 15:51:01.838  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:01.838  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:51:01.842  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:01.849  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:51:01.852  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:51:01.852  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:01.852  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:51:01.852  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@895dfd0 added. We now have 3 listener(s)
,08-17 15:51:01.854  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:51:01.854  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:51:01.854  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:01.855  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:01.855  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce1dbc9 added. We now have 10 listener(s)
,08-17 15:51:01.855  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:51:01.855  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:01.855  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:01.855  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:01.855  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:51:01.855  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:01.855  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:01.855  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:51:01.855  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a670fcd removed from the list
,08-17 15:51:01.856  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:01.856  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a406082 removed from the list
08-17 15:51:01.857  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:01.857  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:01.857  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:01.858  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:01.858  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:01.866   872  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 15:51:01.868  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:51:01.868  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:51:01.868  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:01.868  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a406082 not in the list
08-17 15:51:01.868  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:51:01.868  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:01.870  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:01.871  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:01.871  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:51:01.872  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:01.872  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce1dbc9 removed from the list
08-17 15:51:01.872  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:01.872  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:01.872  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:01.873  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:51:01.873  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@895dfd0 removed from the list
08-17 15:51:01.875  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:51:01.875  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39802ce added. We now have 2 listener(s)
08-17 15:51:01.878  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:51:01.878  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:01.879  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:01.879  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:01.879  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e825ef added. We now have 9 listener(s)
08-17 15:51:01.879  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:01.879  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:51:01.882  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:01.887  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:01.889  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:01.890  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:01.890  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:51:01.890  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2236b85 added. We now have 3 listener(s)
08-17 15:51:01.892  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:51:01.892  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:01.892  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:01.892  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:01.892  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:01.892  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b57dda added. We now have 10 listener(s)
08-17 15:51:01.892  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:01.893  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:51:01.893  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:51:01.893  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:51:01.893  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:01.893  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:51:01.895  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:01.896  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:51:01.896  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:51:01.900  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:51:01.900  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 15:51:01.900  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:51:01.904  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 15:51:01.904  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:51:01.904  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:51:01.904  3760  3810 D BluetoothAdapter: STATE_ON
08-17 15:51:01.908  4141  4151 D BtGatt.GattService: registerClient() - UUID=595c15ec-dcc2-462a-9ce2-9f77b4a7ec48
08-17 15:51:01.908  4141  4158 D BtGatt.GattService: onClientRegistered() - UUID=595c15ec-dcc2-462a-9ce2-9f77b4a7ec48, clientIf=5
08-17 15:51:01.909  3760  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 15:51:01.910  4141  4184 D BtGatt.GattService: start scan with filters
08-17 15:51:01.914  4141  4161 D BtGatt.ScanManager: handling starting scan
08-17 15:51:01.914  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:51:01.915  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 15:51:01.915  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:51:01.915  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 15:51:01.916  4141  4161 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b84ba55
08-17 15:51:01.920  4141  4158 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 15:51:01.920  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:01.921  4141  4161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 15:51:01.923  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:51:01.924  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:51:01.925  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 15:51:01.928  4141  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 15:51:01.928  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:01.929  4141  4161 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:51:01.929  4141  4161 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 15:51:01.930  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 15:51:01.935  3760  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 15:51:01.935  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:01.935  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 15:51:01.936  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:01.936  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:51:01.936  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:51:01.936  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:51:01.936  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:51:01.936  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:51:01.937  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:51:01.937  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 15:51:01.938  3760  3810 D BluetoothAdapter: STATE_ON
08-17 15:51:01.938  4141  4184 D BtGatt.GattService: stopScan() - queue size =1
08-17 15:51:01.939  4141  4152 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 15:51:01.939  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:51:01.940  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:51:01.940  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:51:01.940  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:51:01.940  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 15:51:01.942  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:51:01.942  4141  4158 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 15:51:01.942  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:01.942  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:51:01.942  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:51:01.942  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:51:01.943  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:01.945  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:51:01.945  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:51:01.945  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:51:01.948  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:01.948  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:01.949  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:01.949  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:01.949  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:01.949  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:01.949  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:51:01.949  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39802ce removed from the list
08-17 15:51:01.949  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:01.949  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e825ef removed from the list
08-17 15:51:01.949  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:01.949  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:01.950  4141  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:51:01.950  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:01.950  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:01.950  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:01.951  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:51:01.951  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:01.951  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:01.951  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e825ef not in the list
08-17 15:51:01.951  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:51:01.951  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:01.952  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:01.952  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:01.953  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:51:01.953  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b57dda removed from the list
,08-17 15:51:01.953  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:01.953  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:51:01.953  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:01.953  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:51:01.953  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2236b85 removed from the list
08-17 15:51:01.954  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:51:01.954  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfd9da6 added. We now have 2 listener(s)
08-17 15:51:01.956  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-17 15:51:01.956  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:01.956  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:51:01.956  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:51:01.956  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@568e3e7 added. We now have 9 listener(s)
08-17 15:51:01.956  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:51:01.957  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:51:01.960  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:51:01.960  4141  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 15:51:01.960  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:51:01.961  4141  4161 D BtGatt.ScanManager: stopping BLe Batch
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:01.965  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:51:01.968  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:01.968  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:51:01.968  4141  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:51:01.968  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:01.968  4141  4161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 15:51:01.970  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:51:01.970  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:01.970  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b28863d added. We now have 3 listener(s)
08-17 15:51:01.973  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:01.974  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:51:01.974  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:01.974  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:01.974  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:01.974  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@955ee32 added. We now have 10 listener(s)
08-17 15:51:01.974  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:01.974  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:51:01.975  4141  4158 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 15:51:01.975  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:01.975  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:51:01.975  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:51:01.975  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:51:01.975  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:51:01.975  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 15:51:01.978  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 15:51:01.978  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:51:01.982  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:51:01.983  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 15:51:01.983  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:51:01.986  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 15:51:01.986  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:51:01.986  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 15:51:01.987  3760  3810 D BluetoothAdapter: STATE_ON
,08-17 15:51:01.989  4141  4176 D BtGatt.GattService: registerClient() - UUID=293f365d-e323-4db4-9fde-1eb19f69b0a1
,08-17 15:51:01.990  4141  4158 D BtGatt.GattService: onClientRegistered() - UUID=293f365d-e323-4db4-9fde-1eb19f69b0a1, clientIf=5
,08-17 15:51:01.990  3760  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 15:51:01.990  4141  4184 D BtGatt.GattService: start scan with filters
,08-17 15:51:01.993  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:51:01.993  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:51:01.993  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:51:01.993  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 15:51:01.993  4141  4161 D BtGatt.ScanManager: handling starting scan
,08-17 15:51:01.996  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:51:01.996  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:51:01.996  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:51:01.998  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:51:01.999  4141  4158 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 15:51:01.999  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:51:01.999  4141  4161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 15:51:02.002  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 15:51:02.002  3760  3810 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 15:51:02.002  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:02.002  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:51:02.002  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:51:02.003  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:51:02.003  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.003  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 15:51:02.003  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:51:02.003  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfd9da6 removed from the list
08-17 15:51:02.003  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:51:02.003  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@568e3e7 removed from the list
08-17 15:51:02.003  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:51:02.003  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:51:02.004  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:51:02.004  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 15:51:02.004  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.004  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:51:02.005  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:02.005  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:02.005  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:51:02.006  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@568e3e7 not in the list
08-17 15:51:02.006  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:51:02.006  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-17 15:51:02.006  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:51:02.006  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 15:51:02.006  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 15:51:02.008  3760  3810 D BluetoothAdapter: STATE_ON
08-17 15:51:02.008  4141  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 15:51:02.008  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:51:02.008  4141  4151 D BtGatt.GattService: stopScan() - queue size =1
08-17 15:51:02.009  4141  4152 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 15:51:02.009  4141  4161 D BtGatt.ScanManager: Starting BLE batch scan
08-17 15:51:02.009  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 15:51:02.009  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:51:02.010  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 15:51:02.010  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 15:51:02.010  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 15:51:02.010  4141  4161 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 15:51:02.011  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 15:51:02.012  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:51:02.012  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 15:51:02.012  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:51:02.012  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:02.013  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:02.013  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:51:02.013  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:51:02.013  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@955ee32 removed from the list
,08-17 15:51:02.013  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:02.013  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:51:02.013  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.013  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:02.013  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:51:02.014  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:51:02.014  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b28863d removed from the list
08-17 15:51:02.014  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:51:02.014  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:51:02.015  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@770bb7e added. We now have 2 listener(s)
,08-17 15:51:02.016  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:51:02.016  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:02.016  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:02.016  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:02.017  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59468df added. We now have 9 listener(s)
08-17 15:51:02.017  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:51:02.017  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:51:02.020  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:02.025  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:51:02.027  4141  4158 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 15:51:02.027  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:51:02.027  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:02.027  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:51:02.027  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:51:02.027  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fef3ff5 added. We now have 3 listener(s)
,08-17 15:51:02.029  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:02.030  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:51:02.030  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:02.031  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-17 15:51:02.031  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:51:02.031  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad9118a added. We now have 10 listener(s)
08-17 15:51:02.031  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:51:02.031  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 15:51:02.031  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:51:02.031  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 15:51:02.031  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:51:02.031  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:51:02.033  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:02.035  3760  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 15:51:02.036  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:51:02.038  4141  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:51:02.038  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-17 15:51:02.040  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:51:02.040  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 15:51:02.041  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:51:02.044  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 15:51:02.044  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 15:51:02.044  3760  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 15:51:02.045  3760  3810 D BluetoothAdapter: STATE_ON
,08-17 15:51:02.048  4141  4151 D BtGatt.GattService: registerClient() - UUID=ab03b841-f007-40f2-9ba8-1af7e136e568
,08-17 15:51:02.048  4141  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 15:51:02.048  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:51:02.049  4141  4158 D BtGatt.GattService: onClientRegistered() - UUID=ab03b841-f007-40f2-9ba8-1af7e136e568, clientIf=5
,08-17 15:51:02.049  3760  3772 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 15:51:02.049  4141  4161 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:51:02.049  4141  4176 D BtGatt.GattService: start scan with filters
,08-17 15:51:02.054  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 15:51:02.054  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 15:51:02.054  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 15:51:02.054  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 15:51:02.055  4141  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:51:02.055  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:51:02.056  4141  4161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:51:02.057  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 15:51:02.058  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 15:51:02.058  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 15:51:02.060  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 15:51:02.062  4141  4158 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 15:51:02.063  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:51:02.066  4141  4161 D BtGatt.ScanManager: handling starting scan
,08-17 15:51:02.067  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:51:02.067  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 15:51:02.067  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:51:02.067  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:02.067  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.067  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 15:51:02.067  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:51:02.068  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@770bb7e removed from the list
,08-17 15:51:02.068  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:02.068  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59468df removed from the list
08-17 15:51:02.068  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:51:02.068  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:02.069  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.069  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 15:51:02.069  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.069  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:51:02.070  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:02.070  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 15:51:02.070  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:02.070  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59468df not in the list
08-17 15:51:02.070  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-17 15:51:02.070  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:51:02.071  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:51:02.071  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-17 15:51:02.071  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 15:51:02.071  3760  3810 D BluetoothAdapter: STATE_ON
08-17 15:51:02.072  4141  4152 D BtGatt.GattService: stopScan() - queue size =1,
08-17 15:51:02.073  4141  4151 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 15:51:02.073  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 15:51:02.073  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 15:51:02.073  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 15:51:02.073  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 15:51:02.073  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 15:51:02.074  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:51:02.075  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 15:51:02.075  3760  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:51:02.075  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:51:02.075  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:02.076  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 15:51:02.077  3760  3760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:51:02.077  3760  3760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:51:02.077  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:02.077  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:51:02.077  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:51:02.077  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad9118a removed from the list
08-17 15:51:02.077  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:02.077  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.077  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:02.078  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:51:02.078  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fef3ff5 removed from the list
,08-17 15:51:02.078  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:51:02.079  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bebc56 added. We now have 2 listener(s)
,08-17 15:51:02.081  4141  4158 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 15:51:02.081  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:02.081  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 15:51:02.081  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 15:51:02.081  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:51:02.081  4141  4161 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 15:51:02.081  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:02.081  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94d7 added. We now have 9 listener(s)
08-17 15:51:02.081  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:51:02.082  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 15:51:02.084  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:51:02.088  3760  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:51:02.090  3760  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:51:02.091  3760  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:51:02.091  4141  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 15:51:02.092  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:02.091  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 15:51:02.092  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52c78ad added. We now have 3 listener(s)
08-17 15:51:02.092  4141  4161 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 15:51:02.092  4141  4161 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 15:51:02.093  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:51:02.093  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 15:51:02.093  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:51:02.094  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 15:51:02.094  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:51:02.094  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38247e2 added. We now have 10 listener(s)
,08-17 15:51:02.094  3760  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:51:02.094  3760  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 15:51:02.094  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:02.094  3760  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:51:02.094  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:02.094  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.094  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:51:02.095  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:51:02.095  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bebc56 removed from the list
,08-17 15:51:02.095  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:02.095  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94d7 removed from the list
08-17 15:51:02.096  3760  3760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:51:02.096  3760  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:51:02.096  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:02.096  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:51:02.096  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:02.097  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:51:02.097  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:51:02.097  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:51:02.097  3760  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61c94d7 not in the list
,08-17 15:51:02.097  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:51:02.097  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:51:02.098  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:51:02.098  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:51:02.098  3760  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:51:02.099  3760  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38247e2 removed from the list
,08-17 15:51:02.099  3760  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:51:02.099  3760  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 15:51:02.099  3760  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:51:02.099  3760  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 15:51:02.099  3760  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52c78ad removed from the list
08-17 15:51:02.100  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 15:51:02.100  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 15:51:02.100  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 15:51:02.100  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:51:02.100  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 15:51:02.100  3760  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:51:02.106  3760  4224 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
08-17 15:51:02.106  3760  4224 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
,08-17 15:51:02.106  3760  4224 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 15:51:02.108  3760  4225 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
08-17 15:51:02.109  3760  4225 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
08-17 15:51:02.109  3760  4225 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 15:51:02.110  3760  3810 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-17 15:51:02.111  3760  3810 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 15:51:02.111  3760  3810 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-17 15:51:02.111  3760  3810 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 15:51:02.111  3760  3810 D com.test.thalitest.ThaliTestRunner: Total duration: 22813 ms
,08-17 15:51:02.113  3760  3810 I jxcore-log: Total number of executed tests:  80
08-17 15:51:02.113  3760  3810 I jxcore-log: 
08-17 15:51:02.113  3760  3810 I jxcore-log: Number of passed tests:  80
08-17 15:51:02.113  3760  3810 I jxcore-log: 
08-17 15:51:02.113  3760  3810 I jxcore-log: Number of failed tests:  0
08-17 15:51:02.113  3760  3810 I jxcore-log: 
,08-17 15:51:02.114  3760  3810 I jxcore-log: Number of ignored tests:  0
08-17 15:51:02.114  3760  3810 I jxcore-log: 
,08-17 15:51:02.114  3760  3810 I jxcore-log: Total duration:  22813
08-17 15:51:02.114  3760  3810 I jxcore-log: 
08-17 15:51:02.116  3760  3810 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 15:51:02.116  3760  3810 I jxcore-log: 
,08-17 15:51:02.116  4141  4158 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 15:51:02.117  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:02.119  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.119  3760  3810 I jxcore-log: 
08-17 15:51:02.122  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.122  3760  3810 I jxcore-log: 
08-17 15:51:02.124  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.124  3760  3810 I jxcore-log: 
08-17 15:51:02.125  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.125  3760  3810 I jxcore-log: 
08-17 15:51:02.126  4141  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 15:51:02.126  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:02.126  3760  3760 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 15:51:02.127  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.127  3760  3810 I jxcore-log: 
08-17 15:51:02.129  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.129  3760  3810 I jxcore-log: 
08-17 15:51:02.132  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.132  3760  3810 I jxcore-log: 
,08-17 15:51:02.134  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.134  3760  3810 I jxcore-log: 
,08-17 15:51:02.135  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.135  3760  3810 I jxcore-log: 
,08-17 15:51:02.136  4141  4158 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 15:51:02.136  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:02.136  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:51:02.136  3760  3810 I jxcore-log: 
08-17 15:51:02.136  4141  4161 D BtGatt.ScanManager: stopping BLe Batch
,08-17 15:51:02.137  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:51:02.137  3760  3810 I jxcore-log: 
,08-17 15:51:02.138  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:51:02.138  3760  3810 I jxcore-log: 
08-17 15:51:02.139  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.139  3760  3810 I jxcore-log: 
08-17 15:51:02.140  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.140  3760  3810 I jxcore-log: 
,08-17 15:51:02.141  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:51:02.141  3760  3810 I jxcore-log: 
,08-17 15:51:02.141  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:51:02.141  3760  3810 I jxcore-log: 
08-17 15:51:02.142  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.142  3760  3810 I jxcore-log: 
,08-17 15:51:02.143  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.143  3760  3810 I jxcore-log: 
08-17 15:51:02.144  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.144  3760  3810 I jxcore-log: 
08-17 15:51:02.144  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-17 15:51:02.144  3760  3810 I jxcore-log: 
08-17 15:51:02.145  4141  4158 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 15:51:02.145  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 15:51:02.145  4141  4161 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 15:51:02.145  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.145  3760  3810 I jxcore-log: 
,08-17 15:51:02.146  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.146  3760  3810 I jxcore-log: 
08-17 15:51:02.147  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.147  3760  3810 I jxcore-log: 
,08-17 15:51:02.148  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:51:02.148  3760  3810 I jxcore-log: 
08-17 15:51:02.148  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:51:02.148  3760  3810 I jxcore-log: 
,08-17 15:51:02.149  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.149  3760  3810 I jxcore-log: 
08-17 15:51:02.150  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.150  3760  3810 I jxcore-log: 
,08-17 15:51:02.150  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.150  3760  3810 I jxcore-log: 
,08-17 15:51:02.151  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.151  3760  3810 I jxcore-log: 
08-17 15:51:02.152  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.152  3760  3810 I jxcore-log: 
08-17 15:51:02.152  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.152  3760  3810 I jxcore-log: 
08-17 15:51:02.153  4141  4158 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 15:51:02.153  4141  4158 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 15:51:02.154  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:51:02.154  3760  3810 I jxcore-log: 
,08-17 15:51:02.446  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:51:02.449  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:51:02.449  3760  3810 I jxcore-log: 
,08-17 15:51:02.514  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:51:02.517  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:51:02.517  3760  3810 I jxcore-log: 
,08-17 15:51:02.577  3760  3760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 15:51:02.580  3760  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:51:02.580  3760  3810 I jxcore-log: 
,08-17 15:51:02.636  1988  2626 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 15:51:02.776  4226  4226 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 15:51:02.781  4226  4226 D AndroidRuntime: CheckJNI is OFF
,08-17 15:51:02.832  4226  4226 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 15:51:02.884  4226  4226 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 15:51:02.911  4226  4226 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 15:51:02.934   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 15:51:02.935   872   885 I ActivityManager: Killing 3760:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 15:51:03.045   872  1515 I WindowState: WIN DEATH: Window{80afe4f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 15:51:03.045   872  1959 D GraphicsStats: Buffer count: 2
08-17 15:51:03.045   872  1308 D WifiService: Client connection lost with reason: 4
,08-17 15:51:03.068   872   896 W PackageSettings: Skipping PackageSetting{298fc2e com.example.hello/10273} due to missing metadata
,08-17 15:51:03.104   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-17 15:51:03.104   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-17 15:51:03.105   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-17 15:51:03.105   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 15:51:03.105   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.105   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.105   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 15:51:03.105   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-17 15:51:03.105   872   885 I ActivityManager:   Force finishing activity ActivityRecord{f4275e4 u0 com.test.thalitest/.MainActivity t2}
,08-17 15:51:03.106   872   896 I art     : Starting a blocking GC Explicit
,08-17 15:51:03.115   872  1974 W ActivityManager: Spurious death for ProcessRecord{c54b651 0:com.test.thalitest/u0a0}, curProc for 3760: null
,08-17 15:51:03.150   872   896 I art     : Explicit concurrent mark sweep GC freed 13991(968KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 698us total 42.747ms
,08-17 15:51:03.198   872   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 15:51:03.202  4226  4226 I art     : System.exit called, status: 0
,08-17 15:51:03.202  4226  4226 I AndroidRuntime: VM exiting with result code 0.
,08-17 15:51:03.205   872   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 15:51:03.220   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 15:51:03.225  4141  4141 D BluetoothMapAppObserver: onReceive
,08-17 15:51:03.225  4141  4141 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-17 15:51:03.227  1988  2263 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 15:51:03.230  3599  3599 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 15:51:03.232   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 15:51:03.234  1856  1856 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-17 15:51:03.256  1856  4239 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 15:51:03.267  1922  1922 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 15:51:03.271   872  3134 I ActivityManager: Start proc 4242:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 15:51:03.285  1856  4239 I Decoder : createOrResetDecoder
,08-17 15:51:03.314  1501  1501 I ConfigService: onCreate
,08-17 15:51:03.320   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 15:51:03.324  4242  4242 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 15:51:03.329  1856  4239 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 15:51:03.338   872  1515 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3760 uid 10000
,08-17 15:51:03.340  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-17 15:51:03.356  1856  4239 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 15:51:03.359  1856  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-17 15:51:03.359  1856  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 15:51:03.362   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-17 15:51:03.362   872   884 E PackageManager: Failed to write settings, restoring backup
08-17 15:51:03.362   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 15:51:03.362   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 15:51:03.362   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 15:51:03.362   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 15:51:03.362   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 15:51:03.362   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.362   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.362   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:51:03.365   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-17 15:51:03.365   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 15:51:03.365   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.365   872   885 E DropBoxManagerService: 	... 13 more
,08-17 15:51:03.367  1856  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-17 15:51:03.367  1856  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-17 15:51:03.369  1856  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-17 15:51:03.369  1856  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-17 15:51:03.371  1856  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-17 15:51:03.372  1856  4239 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-17 15:51:03.372  1856  4239 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-17 15:51:03.373  1856  4239 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 15:51:03.373  1856  4239 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-17 15:51:03.373  1856  4239 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 15:51:03.384  1935  2028 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 15:51:03.395  4242  4257 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.395  4242  4257 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.396  4242  4257 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 15:51:03.396   872   882 I ActivityManager: Start proc 4259:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-17 15:51:03.397  1935  2028 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 15:51:03.397  1935  2028 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1935
08-17 15:51:03.397  1935  2028 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 15,:51:03.397  1935  2028 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.397  1935  2028 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 15:51:03.399   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 15:51:03.400  4242  4242 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 15:51:03.400   872  4267 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.400   872  4267 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.400   872  4267 E DropBoxManagerService: 	... 5 more
08-17 15:51:03.404  1935  2028 I Process : Sending signal. PID: 1935 SIG: 9
,08-17 15:51:03.424   872  1515 I ActivityManager: Start proc 4274:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-17 15:51:03.432  4242  4273 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-17 15:51:03.455  4274  4274 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-17 15:51:03.487  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-17 15:51:03.488  1501  1501 D AndroidRuntime: Shutting down VM
08-17 15:51:03.488  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:51:03.488  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
08-17 15:51:03.488  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 15:51:03.488  1501  1501 E AndroidRuntime: 	... 8 more
,08-17 15:51:03.493   872  4290 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.493   872  4290 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.493   872  4290 E DropBoxManagerService: 	... 5 more
,08-17 15:51:03.495  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
,08-17 15:51:03.502   872  1515 D GraphicsStats: Buffer count: 1
,08-17 15:51:03.502   872  1959 I WindowState: WIN DEATH: Window{22a55c5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-17 15:51:03.512   872  1699 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1935) has died,
,08-17 15:51:03.513   872  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-17 15:51:03.515   872  1699 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 15:51:03.535   872   885 I ActivityManager: Start proc 4293:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 15:51:03.541   872  1308 D WifiService: Client connection lost with reason: 4
,08-17 15:51:03.546  1715  4291 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@7da5a93
,08-17 15:51:03.546   872  1699 I ActivityManager: Process com.google.process.gapps (pid 1501) has died
,08-17 15:51:03.547   872  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-17 15:51:03.547   872  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-17 15:51:03.547   872  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
08-17 15:51:03.547   872  1699 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
,08-17 15:51:03.558  1715  1715 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-17 15:51:03.566   872  1959 I ActivityManager: Start proc 4305:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.580  4293  4293 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.581  4293  4293 D AndroidRuntime: Shutting down VM
08-17 15:51:03.588  4293  4293 E And,roidRuntime: FATAL EXCEPTION: main
08-17 15:51:03.588  4293  4293 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4293
08-17 15:51:03.588  4293  4293 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.5,88  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.588  4293  4293 E AndroidRuntime: 	... 10 more
08-17 15:51:03.590   872  1942 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 15:51:03.591  4293  4293 I Process : Sending signal. PID: 4293 SIG: 9
08-17 15:51:03.592  4305  4305 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-17 15:51:03.595   872  4318 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.595   872  4318 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.595   872  4318 E DropBoxManagerService: 	... 5 more
08-17 15:51:03.599  4305  4305 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.601  4305  4305 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.601  4305  4305 D AndroidRuntime: Shutting down VM
08-17 15:51:03.601  4305  4305 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:51:03.601  4305  4305 E AndroidRuntime: Process: com.google.process.gapps, PID: 4305
08-17 15:51:03.601  4305  4305 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.601  4305  4305 E AndroidRuntime: 	... 10 more
08-17 15:51:03.604  4305  4305 I Process : Sending signal. PID: 4305 SIG: 9
08-17 15:51:03.604   872  4320 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.604   872  4320 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.604   872  4320 E DropBoxManagerService: 	... 5 more
08-17 15:51:03.610   872  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
08-17 15:51:03.623  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-17 15:51:03.623  1715  1715 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-17 15:51:03.624   872  1957 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4293) has died
,08-17 15:51:03.625   872  1957 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-17 15:51:03.630  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-17 15:51:03.630  1715  1715 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-17 15:51:03.638  1715  4321 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-17 15:51:03.640  4242  4257 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.645  4242  4273 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-17 15:51:03.646  4242  4273 E AndroidRuntime: Process: android.process.acore, PID: 4242
08-17 15:51:03.646  4242  4273 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.646  4242  4273 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 15:51:03.649  4242  4257 I Process : Sending signal. PID: 4242 SIG: 9
08-17 15:51:03.650   872   885 I ActivityManager: Start proc 4324:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 15:51:03.652   872   883 I ActivityManager: Process com.google.process.gapps (pid 4305) has died
08-17 15:51:03.652   872   883 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a84f047 u0 com.google.android.gms/.gcm.GcmService}
08-17 15:51:03.652   872   883 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{8ce737f u0 com.google.android.gms/.config.ConfigService}
08-17 15:51:03.653   872   883 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{59eb13c u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-17 15:51:03.653   872   883 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{1e9e28a u0 com.google.android.gms/.auth.GetToken}
08-17 15:51:03.654   872  4329 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.654   872  4329 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.654   872  4329 E DropBoxManagerService: 	... 5 more
08-17 15:51:03.656  1715  4321 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-17 15:51:03.656  1715  4321 E AndroidRuntime: Process: com.google.android.gms, PID: 1715
08-17 15:51:03.656  1715  4321 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 15:51:03.656  1715  4321 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-17 15:51:03.665   872   883 I ActivityManager: Start proc 4336:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,08-17 15:51:03.670  1715  4321 I Process : Sending signal. PID: 1715 SIG: 9
08-17 15:51:03.671   872  4343 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.671   872  4343 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.671   872  4343 E DropBoxManagerService: 	... 5 more
08-17 15:51:03.686   280   280 E lowmemorykiller: Error writing /proc/4242/oom_score_adj; errno=22
08-17 15:51:03.700  2012  4342 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.704  4324  4324 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 15:51:03.704  4324  4324 D AndroidRuntime: Shutting down VM
,08-17 15:51:03.717   280   280 E lowmemorykiller: Error writing /proc/1715/oom_score_adj; errno=22
,08-17 15:51:03.717   280   280 E lowmemorykiller: Error writing /proc/4242/oom_score_adj; errno=22
,08-17 15:51:03.718  4336  4336 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-17 15:51:03.721  4324  4324 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:51:03.721  4324  4324 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4324
08-17 15:51:03.721  4324  4324 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(Co,ntentProvider.java:1748)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.721  4324  4324 E AndroidRuntime: 	... 10 more
08-17 15:51:03.722   872  1957 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 15:51:03.724  4336  4336 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-17 15:51:03.724   872  4351 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.724   872  4351 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.724   872  4351 E DropBoxManagerService: 	... 5 more
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableD,atabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.726  4336  4336 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.726  4336  4336 D AndroidRuntime: Shutting down VM
08-17 15:51:03.726  4336  4336 E AndroidRuntime: FATAL EXCEPTION: main
08-17 15:51:03.726  4336  4336 E AndroidRuntime: Process: com.google.process.gapps, PID: 4336
08-17 15:51:03.726  4336  4336 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 15:51:03.726  4336  4336 E AndroidRuntime: 	... 10 more
08-17 15:51:03.734   872   885 I ActivityManager: Start proc 4352:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-17 15:51:03.736   872  1974 W ActivityManager: Process com.google.process.gapps has crashed too many times: killing!
08-17 15:51:03.736   872  1974 I ActivityManager: Killing 4336:com.google.process.gapps/u0a11 (adj 1): crash
08-17 15:51:03.737   872  4358 E DropBoxManagerService: Can't write: system_app_crash
08-17 15:51:03.737   872  4358 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 15:51:03.737   872  4358 E DropBoxManagerService: 	... 5 more
08-17 15:51:03.758  2012  4342 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-17 15:51:03.766   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
