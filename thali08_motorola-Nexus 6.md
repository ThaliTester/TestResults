#### Test 80598264be6cebf_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-09 13:02:07.145  1651  1780 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-09 13:02:07.145  1651  1780 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-09 13:02:08.816  3344  3344 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 13:02:08.821  3344  3344 D AndroidRuntime: CheckJNI is OFF
08-09 13:02:08.863  3344  3344 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 13:02:08.915  3344  3344 I Radio-JNI: register_android_hardware_Radio DONE
08-09 13:02:08.937  3344  3344 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-09 13:02:08.941   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 13:02:08.969  1821  1837 W SearchService: Abort, client detached.
08-09 13:02:08.978  3344  3344 D AndroidRuntime: Shutting down VM
08-09 13:02:08.985  1821  2129 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ecf294f
08-09 13:02:08.986  1821  2138 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-09 13:02:08.986  1821  1821 I HotwordDetector: Closing mic
08-09 13:02:08.997   873  1767 I ActivityManager: Start proc 3353:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-09 13:02:09.007  1821  1821 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-09 13:02:09.044   376  2143 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-09 13:02:09.045   376  2143 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-09 13:02:09.048   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-09 13:02:09.049  1821  2134 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-09 13:02:09.049  1821  2137 I MicroRecognitionRnrImpl: Detection finished
08-09 13:02:09.061  3353  3353 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-09 13:02:09.081  3353  3353 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-09 13:02:09.087  3353  3353 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4601-4603)
08-09 13:02:09.087  3353  3353 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 13:02:09.098  3353  3353 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d009580}
08-09 13:02:09.098  3353  3353 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 13:02:09.098  3353  3353 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 13:02:09.104  3353  3353 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-09 13:02:09.105  3353  3353 E SysUtils: ApplicationContext is null in ApplicationStatus
08-09 13:02:09.120  3353  3369 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-09 13:02:09.126  3353  3353 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-09 13:02:09.136  3353  3353 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 13:02:09.136  3353  3353 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 13:02:09.137  3353  3353 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 13:02:09.137  3353  3353 I Adreno  : Build Date                       : 10/20/15
08-09 13:02:09.137  3353  3353 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 13:02:09.137  3353  3353 I Adreno  : Local Branch                     : M14
08-09 13:02:09.137  3353  3353 I Adreno  : Remote Branch                    : 
08-09 13:02:09.137  3353  3353 I Adreno  : Remote Branch                    : 
08-09 13:02:09.137  3353  3353 I Adreno  : Reconstruct Branch               : 
08-09 13:02:09.173   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@224c121:true
08-09 13:02:09.190   873  1708 I ActivityManager: Killing 2925:com.google.android.youtube/u0a86 (adj 15): empty #17
08-09 13:02:09.213  3353  3353 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-09 13:02:09.228  3353  3353 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-09 13:02:09.279  3353  3392 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-09 13:02:09.286  3353  3378 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-09 13:02:09.339  3353  3392 I OpenGLRenderer: Initialized EGL, version 1.4
,08-09 13:02:09.381  1651  1651 I Keyboard.Facilitator: onFinishInput()
,08-09 13:02:09.420   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +436ms
,08-09 13:02:09.489  3353  3353 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3353
,08-09 13:02:09.607  3353  3353 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 13:02:09.772  3353  3394 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1667303120
,08-09 13:02:09.778  3353  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 13:02:09.778  3353  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 13:02:09.778  3353  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 13:02:09.778  3353  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 13:02:09.778  3353  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-09 13:02:09.778  3353  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2743317 added. We now have 1 listener(s)
,08-09 13:02:09.781  3353  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-09 13:02:09.782  3353  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 13:02:09.783  3353  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 13:02:09.783  3353  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-09 13:02:09.788  3353  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aec2b22 added. We now have 1 listener(s)
08-09 13:02:09.788  3353  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 13:02:09.795   873  1308 D WifiService: New client listening to asynchronous messages
,08-09 13:02:09.796  3353  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 13:02:09.796  3353  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-09 13:02:09.798  3353  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-09 13:02:09.798  3353  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-09 13:02:09.798  3353  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-09 13:02:09.799   873  1731 I ActivityManager: Killing 2323:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-09 13:02:09.841   873  1731 I ActivityManager: Killing 3025:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-09 13:02:09.881  3353  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 13:02:09.882  3353  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-09 13:02:09.883  3353  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 13:02:09.884  3353  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 13:02:09.884  3353  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-09 13:02:09.884  3353  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 13:02:09.884  3353  3394 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-09 13:02:09.944  3353  3353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 13:02:09.947  3353  3353 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 13:02:10.520  3353  3403 E filemap : mmap(19017728,0) failed: Invalid argument
,08-09 13:02:10.520  3353  3403 W asset   : create map from entry failed
08-09 13:02:10.520  3353  3403 W jxcore-FileManager: aproxFileSize failed
08-09 13:02:10.521  3353  3403 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/write-stream/Makefile
08-09 13:02:10.521  3353  3403 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
08-09 13:02:10.521  3353  3403 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
08-09 13:02:10.521  3353  3403 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
,08-09 13:02:10.521  3353  3403 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
08-09 13:02:10.521  3353  3403 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
,08-09 13:02:10.521  3353  3403 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
08-09 13:02:10.521  3353  3403 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 13:02:10.521  3353  3403 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 13:02:10.521  3353  3403 W System.err: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:10.521  3353  3403 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,08-09 13:02:10.546  3353  3403 W jxcore-log: Initializing JXcore engine
08-09 13:02:10.546  3353  3403 W jxcore-log: JXcore engine is ready
,08-09 13:02:10.586  3403  3403 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-09 13:02:10.586  3403  3403 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10617]" dev="sockfs" ino=10617 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-09 13:02:10.586  3403  3403 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-09 13:02:10.586  3403  3403 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24599]" dev="sockfs" ino=24599 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-09 13:02:10.603  3353  3403 W jxcore-log: Starting JXcore engine
,08-09 13:02:10.690  3353  3403 W jxcore-log: Platform android
08-09 13:02:10.690  3353  3403 W jxcore-log: 
08-09 13:02:10.690  3353  3403 W jxcore-log: Process ARCH arm
08-09 13:02:10.690  3353  3403 W jxcore-log: 
,08-09 13:02:10.894  3353  3403 I jxcore-log: JXcore Cordova bridge is ready!
08-09 13:02:10.894  3353  3403 I jxcore-log: 
08-09 13:02:10.895  3353  3403 W jxcore-log: JXcore engine is started
,08-09 13:02:10.915  3353  3394 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-09 13:02:10.924  3353  3353 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-09 13:02:12.272  1500  1500 I ConfigService: onDestroy
,08-09 13:02:18.854   873   886 I ActivityManager: Waited long enough for: ServiceRecord{4bb224a u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-09 13:02:20.276  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 13:02:20.285  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 13:02:20.287  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 13:02:20.318  1500  1933 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 13:02:20.318  1500  1933 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 13:02:20.318  1500  1933 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 13:02:20.318  1500  1933 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 13:02:20.357  2590  2590 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-09 13:02:20.358  2590  2590 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 13:02:20.358  2590  2590 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-09 13:02:21.052  3353  3403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 13:02:21.052  3353  3403 I jxcore-log: 
,08-09 13:02:21.055  3353  3403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 13:02:21.055  3353  3403 I jxcore-log: 
,08-09 13:02:21.056  3353  3403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 13:02:21.056  3353  3403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 13:02:21.057  3353  3403 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 13:02:21.057  3353  3403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 13:02:21.060  3353  3403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 13:02:21.060  3353  3403 I jxcore-log: 
,08-09 13:02:21.063  3353  3403 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 13:02:21.063  3353  3403 I jxcore-log: 
,08-09 13:02:21.391  3353  3403 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
,08-09 13:02:21.392  3353  3403 I jxcore-log: Failed to execute UT.
08-09 13:02:21.392  3353  3403 I jxcore-log: 
08-09 13:02:21.392  3353  3403 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-09 13:02:21.392  3353  3403 I jxcore-log: 
08-09 13:02:21.394  3353  3403 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 13:02:21.394  3353  3403 I jxcore-log: 
,08-09 13:02:21.407  3353  3353 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-09 13:02:22.034  3407  3407 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-09 13:02:22.038  3407  3407 D AndroidRuntime: CheckJNI is OFF
,08-09 13:02:22.074  3407  3407 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-09 13:02:22.114  3407  3407 I Radio-JNI: register_android_hardware_Radio DONE
,08-09 13:02:22.134  3407  3407 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-09 13:02:22.147   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-09 13:02:22.148   873   886 I ActivityManager: Killing 3353:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-09 13:02:22.256   873   896 W PackageSettings: Skipping PackageSetting{43f22ef com.example.hello/10273} due to missing metadata
,08-09 13:02:22.260   873  1730 D GraphicsStats: Buffer count: 2
,08-09 13:02:22.260   873  1697 I WindowState: WIN DEATH: Window{c6f3491 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-09 13:02:22.261   873  1308 D WifiService: Client connection lost with reason: 4
,08-09 13:02:22.287   873   886 W ActivityManager: Force removing ActivityRecord{62635be u0 com.test.thalitest/.MainActivity t4}: app died, no saved state
,08-09 13:02:22.305   873   896 I art     : Starting a blocking GC Explicit
,08-09 13:02:22.318   873  1730 W ActivityManager: Spurious death for ProcessRecord{442b918 0:com.test.thalitest/u0a0}, curProc for 3353: null
,08-09 13:02:22.341   873  1767 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3353 uid 10000
,08-09 13:02:22.344  1651  1651 I Keyboard.Facilitator: onFinishInput()
,08-09 13:02:22.362   873   896 I art     : Explicit concurrent mark sweep GC freed 19584(1390KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 971us total 55.696ms
,08-09 13:02:22.373   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-09 13:02:22.376  3407  3407 I art     : System.exit called, status: 0
08-09 13:02:22.376  3407  3407 I AndroidRuntime: VM exiting with result code 0.
,08-09 13:02:22.385   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-09 13:02:22.404  1798  2028 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-09 13:02:22.405   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-09 13:02:22.417  3225  3225 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-09 13:02:22.428  1651  1651 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-09 13:02:22.438  1651  3424 I Keyboard.Facilitator.DecoderInitializer: run()
,08-09 13:02:22.443  1651  3424 I Decoder : createOrResetDecoder
,08-09 13:02:22.457  1746  1746 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-09 13:02:22.459  1821  3426 I MicroRecognitionRnrImpl: Starting detection.
,08-09 13:02:22.460  1821  3427 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@4a7d986
,08-09 13:02:22.461   376  3429 I AudioFlinger: AudioFlinger's thread 0xb1640000 ready to run
,08-09 13:02:22.464   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-09 13:02:22.464  1821  3427 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@4a7d986
,08-09 13:02:22.469  2761  3425 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-09 13:02:22.473   376  3429 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic),
,08-09 13:02:22.473   376  3429 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-09 13:02:22.474   376  3429 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-09 13:02:22.484   376  3429 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-09 13:02:22.507  1500  1500 I ConfigService: onCreate
,08-09 13:02:22.517  1500  1500 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-09 13:02:22.517  1500  1500 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-09 13:02:22.536  1651  3424 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-09 13:02:22.537  1864  3433 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-09 13:02:22.538  1864  3433 D AccountUtils: Clearing selected account for com.test.thalitest
,08-09 13:02:22.542  2761  3425 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,--------- beginning of crash
08-09 13:02:22.546  2761  3425 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-09 13:02:22.546  2761  3425 E AndroidRuntime: Process: android.process.acore, PID: 2761
08-09 13:02:22.546  2761  3425 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.546  2761  3425 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 13:02:22.550  1864  3433 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-09 13:02:22.557   873  3438 E DropBoxManagerService: Can't write: system_app_crash
08-09 13:02:22.557   873  3438 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.557   873  3438 E DropBoxManagerService: 	... 5 more
,08-09 13:02:22.559   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-09 13:02:22.561  1821  1821 I HotwordWorkerImpl: onReady
,08-09 13:02:22.567   873  3439 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-09 13:02:22.574  1864  3433 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.574  1864  3433 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.575  1864  3433 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.576  1864  3433 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-09 13:02:22.585  1864  1864 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-09 13:02:22.585  1864  1864 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-09 13:02:22.591  1864  1864 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-09 13:02:22.591  1864  1864 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.593  1864  3442 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.595  1864  3444 W BaseAppContext: Using Auth Proxy for data requests.
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.596  1864  3442 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.597  1821  3445 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-09 13:02:22.601  1864  3442 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-09 13:02:22.601  1864  3442 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-09 13:02:22.601  1864  3442 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-09 13:02:22.602  1864  3442 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-09 13:02:22.602  1864  3442 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-09 13:02:22.603  1864  3442 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-09 13:02:22.603  1864  3442 E AndroidRuntime: Process: com.google.android.gms, PID: 1864
08-09 13:02:22.603  1864  3442 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.603  1864  3442 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.609  1864  3444 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 13:02:22.613   873  3447 E DropBoxManagerService: Can't write: system_app_crash
08-09 13:02:22.613   873  3447 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.613   873  3447 E DropBoxManagerService: 	... 5 more
08-09 13:02:22.614  1651  3424 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-09 13:02:22.614   873  3439 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 13:02:22.614   873  3439 I Adreno  : Build Date                       : 10/20/15
08-09 13:02:22.614   873  3439 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 13:02:22.614   873  3439 I Adreno  : Local Branch                     : M14
08-09 13:02:22.614   873  3439 I Adreno  : Remote Branch                    : 
08-09 13:02:22.614   873  3439 I Adreno  : Remote Branch                    : 
08-09 13:02:22.614   873  3439 I Adreno  : Reconstruct Branch               : 
08-09 13:02:22.616  1651  3424 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-09 13:02:22.616  1651  3424 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-09 13:02:22.619  1651  3424 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-09 13:02:22.619  1651  3424 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-09 13:02:22.621  1651  3424 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-09 13:02:22.621  1651  3424 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-09 13:02:22.623  1651  3424 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-09 13:02:22.623  1651  3424 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-09 13:02:22.623  1651  3424 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-09 13:02:22.623  1651  3424 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-09 13:02:22.623  1651  3424 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-09 13:02:22.624  1651  3424 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/app_state.db'.
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 13:02:22.629  1864  3444 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-09 13:02:22.629  1864  3446 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-09 13:02:22.631  1765  3448 E ReflectionEngine: Failed to save models
08-09 13:02:22.631  1765  3448 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.631  1765  3448 E ReflectionEngine: 	... 16 more
08-09 13:02:22.633  1821  3445 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-09 13:02:22.641   873  3439 I OpenGLRenderer: Initialized EGL, version 1.4
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: Failed to write the stream file
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2427: open failed: EROFS (Read-only file system)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.643  1765  3448 E ObservedEventLogger: 	... 16 more
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: Failed to write the stream file
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.646  1765  3448 E ObservedEventLogger: 	... 16 more
,08-09 13:02:22.656   873   884 I ActivityManager: Start proc 3449:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-09 13:02:22.676   873  1708 I ActivityManager: Start proc 3462:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-09 13:02:22.677  1864  3446 I Process : Sending signal. PID: 1864 SIG: 9
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: Runtime exception while performing operation
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 13:02:22.677  1864  3444 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
08-09 13:02:22.681  1821  3445 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-09 13:02:22.682  1821  3445 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-09 13:02:22.682  1821  3445 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1821
08-09 13:02:22.682  1821  3445 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.682  1821  3445 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 13:02:22.689   873  3476 E DropBoxManagerService: Can't write: system_app_crash
08-09 13:02:22.689   873  3476 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.689   873  3476 E DropBoxManagerService: 	... 5 more
,08-09 13:02:22.713  1765  1849 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-09 13:02:22.714   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-09 13:02:22.716  1765  1849 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-09 13:02:22.716  1765  1849 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1765
08-09 13:02:22.716  1765  1849 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	,at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.716  1765  1849 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.717   873  1681 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-09 13:02:22.717   873  1681 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 13:02:22.721   873  1681 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-09 13:02:22.724   873  1681 I ActivityManager: Killing 1765:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
,08-09 13:02:22.728   873  3479 E DropBoxManagerService: Can't write: system_app_crash
08-09 13:02:22.728   873  3479 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.728   873  3479 E DropBoxManagerService: 	... 5 more
,08-09 13:02:22.736  3449  3449 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,08-09 13:02:22.741   873   885 E PackageManager: Failed to write settings, restoring backup
08-09 13:02:22.741   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-09 13:02:22.741   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-09 13:02:22.741   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-09 13:02:22.741   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-09 13:02:22.741   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-09 13:02:22.741   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.741   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.741   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.742  3449  3449 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-09 13:02:22.752   873  1697 D GraphicsStats: Buffer count: 2
,08-09 13:02:22.781   873  1681 I ActivityManager: Start proc 3482:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-09 13:02:22.783   873  1731 I ActivityManager: Process com.google.android.gms (pid 1864) has died
08-09 13:02:22.783   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-09 13:02:22.783   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-09 13:02:22.783   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.783   873   886 E DropBoxManagerService: 	... 13 more
08-09 13:02:22.784   873  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-09 13:02:22.784   873  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
,08-09 13:02:22.784   873  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
08-09 13:02:22.784   873  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
08-09 13:02:22.784   873  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
08-09 13:02:22.784   873  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
08-09 13:02:22.784   873  1731 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
,08-09 13:02:22.787   873  1762 W ActivityManager: Spurious death for ProcessRecord{62330f0 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1765: null
,08-09 13:02:22.816  1821  1821 E AttachedClient: AttachedClient[7580617299026, ClientConfig[mFlags=[210d800202] mSuggestFlags=[3b] mClientStats=SearchBoxStats[gel/android-search-app]]]: failed callback onGenericEvent()
08-09 13:02:22.816  1821  1821 E AttachedClient: android.os.DeadObjectException
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at android.os.BinderProxy.transact(Binder.java:503)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.google.android.apps.gsa.search.shared.service.l.c(ISearchServiceUiCallback.java:578)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.google.android.search.core.service.a.c(AttachedClient.java:4725)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.google.android.search.core.service.a.b(AttachedClient.java:185)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.google.android.search.core.ad.c(SearchController.java:51069)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.google.android.search.core.service.SearchService.bca(SearchService.java:373)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.google.android.search.core.service.SearchService$1.run(SearchService.java:83)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 13:02:22.816  1821  1821 E AttachedClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 13:02:22.816  1821  1821 I SearchService: Ignoring already detached client
,08-09 13:02:22.839  1821  2129 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4a7d986
08-09 13:02:22.839  1821  3427 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-09 13:02:22.839  1821  1821 I HotwordDetector: Closing mic
,08-09 13:02:22.842  3482  3482 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 13:02:22.842  3482  3482 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 13:02:22.843  3482  3482 D AndroidRuntime: Shutting down VM
,08-09 13:02:22.854  1821  1821 W ErrorReporter: reportError [type: 29, code: 917507]: null
,08-09 13:02:22.858   873   873 I ActivityManager: Start proc 3499:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-09 13:02:22.863  3482  3482 E AndroidRuntime: FATAL EXCEPTION: main
08-09 13:02:22.863  3482  3482 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3482
08-09 13:02:22.863  3482  3482 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-09 13:02:22.863  3482  3482 E AndroidRuntime: 	... 10 more
08-09 13:02:22.867   873  3509 E DropBoxManagerService: Can't write: system_app_crash
08-09 13:02:22.867   873  3509 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.867   873  3509 E DropBoxManagerService: 	... 5 more
,08-09 13:02:22.881  3449  3495 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.881  3449  3495 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-09 13:02:22.882  3449  3495 E AndroidRuntime: Process: com.android.keychain, PID: 3449
08-09 13:02:22.882  3449  3495 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.j,ava:791)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 13:02:22.882  3449  3495 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 13:02:22.882   873  1681 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-09 13:02:22.887   376  3429 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-09 13:02:22.888   376  3429 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-09 13:02:22.894   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-09 13:02:22.897  1821  3426 I MicroRecognitionRnrImpl: Detection finished
,08-09 13:02:22.897  1821  2134 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-09 13:02:22.907   873  1762 I ActivityManager: Start proc 3512:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-09 13:02:22.909   873  3520 E DropBoxManagerService: Can't write: system_app_crash
08-09 13:02:22.909   873  3520 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 13:02:22.909   873  3520 E DropBoxManagerService: 	... 5 more
,08-09 13:02:22.981   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-09 13:02:22.981   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-09 13:02:22.981   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-09 13:02:22.981   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,08-09 13:02:22.981   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-09 13:02:22.981   281   281 E qdoverlay: MdpCtrl close error in unset

```
