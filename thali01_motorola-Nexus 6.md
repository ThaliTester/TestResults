#### Test 828946820542738_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-06 19:09:32.811   870  2077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=116103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-06 19:09:33.524  3775  3775 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-06 19:09:33.529  3775  3775 D AndroidRuntime: CheckJNI is OFF
09-06 19:09:33.573  3775  3775 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-06 19:09:33.624  3775  3775 I Radio-JNI: register_android_hardware_Radio DONE
09-06 19:09:33.646  3775  3775 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 19:09:33.650   870  1963 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 19:09:33.694  2013  2027 W SearchService: Abort, client detached.
09-06 19:09:33.700  3775  3775 D AndroidRuntime: Shutting down VM
09-06 19:09:33.707  2013  2351 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a0c830b
09-06 19:09:33.707  2013  2357 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-06 19:09:33.708  2013  2013 I HotwordDetector: Closing mic
09-06 19:09:33.720   870  1954 I ActivityManager: Start proc 3784:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-06 19:09:33.766   377  2359 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-06 19:09:33.768   377  2359 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-06 19:09:33.772   377  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-06 19:09:33.773  2013  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-06 19:09:33.774  2013  2355 I MicroRecognitionRnrImpl: Detection finished
09-06 19:09:33.800  3784  3784 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-06 19:09:33.828  3784  3784 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-06 19:09:33.835  3784  3784 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7125-7128)
09-06 19:09:33.835  3784  3784 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:09:33.852  3784  3784 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bf57ecc}
09-06 19:09:33.853  3784  3784 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:09:33.853  3784  3784 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:09:33.864  3784  3784 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-06 19:09:33.866  3784  3784 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:09:33.880  3784  3784 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-06 19:09:33.894  3784  3784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:09:33.894  3784  3784 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:09:33.895  3784  3784 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:09:33.895  3784  3784 I Adreno  : Build Date                       : 10/20/15
09-06 19:09:33.895  3784  3784 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:09:33.895  3784  3784 I Adreno  : Local Branch                     : M14
09-06 19:09:33.895  3784  3784 I Adreno  : Remote Branch                    : 
09-06 19:09:33.895  3784  3784 I Adreno  : Remote Branch                    : 
09-06 19:09:33.895  3784  3784 I Adreno  : Reconstruct Branch               : 
09-06 19:09:33.945   870   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69295d4:true
,09-06 19:09:33.979  3784  3784 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 19:09:33.993  3784  3784 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-06 19:09:34.047  3784  3822 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-06 19:09:34.058  3784  3809 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-06 19:09:34.115  3784  3822 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:09:34.180   870   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +477ms
09-06 19:09:34.192  1875  1875 I Keyboard.Facilitator: onFinishInput()
09-06 19:09:34.264  3784  3784 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3784
09-06 19:09:34.333  3784  3784 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-06 19:09:34.474  3784  3826 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1717831376
09-06 19:09:34.479  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:09:34.479  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:09:34.479  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:09:34.479  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:09:34.479  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 19:09:34.480  3784  3826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139ad53 added. We now have 1 listener(s)
09-06 19:09:34.482  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-06 19:09:34.484  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:09:34.485  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:09:34.485  3784  3826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:09:34.488  3784  3826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19ba78e added. We now have 1 listener(s)
09-06 19:09:34.488  3784  3826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:34.493   870  1308 D WifiService: New client listening to asynchronous messages
09-06 19:09:34.494  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:09:34.494  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 19:09:34.495  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:09:34.495  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:09:34.495  3784  3826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 19:09:34.510  3784  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:34.510  3784  3826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-06 19:09:34.517  3784  3826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:34.517  3784  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:34.517  3784  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:09:34.518  3784  3826 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:34.519  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:34.520  3784  3826 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:09:34.521  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:34.530   870  1975 I ActivityManager: Killing 2987:com.google.android.calendar/u0a37 (adj 15): empty #17
09-06 19:09:34.550  3784  3784 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-06 19:09:34.573   870  1975 I ActivityManager: Killing 3206:com.google.android.gm/u0a78 (adj 15): empty #18
09-06 19:09:35.159  3784  3835 E filemap : mmap(18165760,0) failed: Invalid argument
09-06 19:09:35.159  3784  3835 W asset   : create map from entry failed
09-06 19:09:35.159  3784  3835 W jxcore-FileManager: aproxFileSize failed
09-06 19:09:35.159  3784  3835 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/thali/node_modules/hoek/test/modules/ignore.txt
09-06 19:09:35.160  3784  3835 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
09-06 19:09:35.160  3784  3835 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
09-06 19:09:35.160  3784  3835 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
09-06 19:09:35.160  3784  3835 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
09-06 19:09:35.160  3784  3835 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
09-06 19:09:35.160  3784  3835 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
09-06 19:09:35.160  3784  3835 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:09:35.160  3784  3835 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:09:35.160  3784  3835 W System.err: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:35.160  3784  3835 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-06 19:09:35.327  3784  3835 W jxcore-log: Initializing JXcore engine
09-06 19:09:35.327  3784  3835 W jxcore-log: JXcore engine is ready
09-06 19:09:35.365  3835  3835 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-06 19:09:35.365  3835  3835 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9626]" dev="sockfs" ino=9626 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-06 19:09:35.365  3835  3835 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 19:09:35.365  3835  3835 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26453]" dev="sockfs" ino=26453 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-06 19:09:35.381  3784  3835 W jxcore-log: Starting JXcore engine
09-06 19:09:35.479  3784  3835 W jxcore-log: Platform android
09-06 19:09:35.479  3784  3835 W jxcore-log: 
09-06 19:09:35.479  3784  3835 W jxcore-log: Process ARCH arm
09-06 19:09:35.479  3784  3835 W jxcore-log: 
09-06 19:09:35.717  3784  3835 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:09:35.717  3784  3835 I jxcore-log: 
09-06 19:09:35.717  3784  3835 W jxcore-log: JXcore engine is started
09-06 19:09:35.724  3784  3826 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-06 19:09:35.733  3784  3784 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:09:40.429   870  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-06 19:09:43.982  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:09:43.987  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:09:43.989  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:09:44.010  1501  3103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-06 19:09:44.010  1501  3103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-06 19:09:44.011  1501  3103 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:09:44.011  1501  3103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:09:44.023  3522  3522 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-06 19:09:44.023  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-06 19:09:44.024  3522  3522 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-06 19:09:45.683  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:09:45.683  3784  3835 I jxcore-log: 
,09-06 19:09:45.686  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:09:45.686  3784  3835 I jxcore-log: 
,09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:45.696  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:45.702  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:45.705  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:09:45.705  3784  3835 I jxcore-log: 
,09-06 19:09:45.707  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:09:45.707  3784  3835 I jxcore-log: 
,09-06 19:09:46.007  1501  3001 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-06 19:09:46.007  1501  3001 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-06 19:09:46.007  1501  3001 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:09:46.008  1501  3001 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:09:46.037  3007  3848 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-06 19:09:46.037  3007  3848 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jdm.a(PG:82)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jcs.o(PG:406)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jcn.a(PG:1379)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jcs.i(PG:143)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at blb.a(PG:3937)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at czp.a(PG:18188)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at czp.a(PG:9081)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at czq.run(PG:1686)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:09:46.037  3007  3848 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jdj.a(PG:4091)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jdj.a(PG:1125)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jdm.a(PG:77)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	... 12 more
09-06 19:09:46.037  3007  3848 E HttpOperation: Caused by: faj: BadAuthentication
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at fal.a(PG:38)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	at jdj.a(PG:4089)
09-06 19:09:46.037  3007  3848 E HttpOperation: 	... 14 more
,09-06 19:09:46.115  1501  2417 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-06 19:09:46.115  1501  2417 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 19:09:46.115  1501  2417 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:09:46.115  1501  2417 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:09:46.132  3007  3848 E HttpOperation: [getmobileexperiments] Unexpected exception
09-06 19:09:46.132  3007  3848 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jdm.a(PG:82)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jcs.o(PG:406)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jcn.a(PG:1379)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jcs.i(PG:143)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at hec.a(PG:42)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at hee.a(PG:102)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at czr.a(PG:65)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at kka.a(PG:108)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at czp.a(PG:19176)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at czp.a(PG:9081)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at czq.run(PG:1686)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:09:46.132  3007  3848 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jdj.a(PG:4091)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jdj.a(PG:1125)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jdm.a(PG:77)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	... 15 more
09-06 19:09:46.132  3007  3848 E HttpOperation: Caused by: faj: BadAuthentication
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at fal.a(PG:38)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	at jdj.a(PG:4089)
09-06 19:09:46.132  3007  3848 E HttpOperation: 	... 17 more
,09-06 19:09:46.132  3007  3848 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-06 19:09:46.132  3007  3848 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jdm.a(PG:82)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jcs.o(PG:406)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jcn.a(PG:1379)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jcs.i(PG:143)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at hec.a(PG:42)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at hee.a(PG:102)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at czr.a(PG:65)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at kka.a(PG:108)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at czp.a(PG:19176)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at czp.a(PG:9081)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at czq.run(PG:1686)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jdj.a(PG:4091)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jdj.a(PG:1125)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jdm.a(PG:77)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	... 15 more
09-06 19:09:46.132  3007  38,48 E ExperimentLoader: Caused by: faj: BadAuthentication
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	,at fal.a(PG:38)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	at jdj.a(PG:4089)
09-06 19:09:46.132  3007  3848 E ExperimentLoader: 	... 17 more
,09-06 19:09:46.231  3784  3835 D executeNativeTests: Running unit tests
,09-06 19:09:46.269   870   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129049, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-06 19:09:46.289  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:09:46.289  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 added. We now have 2 listener(s)
09-06 19:09:46.290  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:09:46.290  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:09:46.290  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:09:46.290  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:46.290  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 added. We now have 2 listener(s)
09-06 19:09:46.290  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:46.291  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:09:46.294  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:46.304  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:46.308  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:46.308  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:46.311  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:09:46.313  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:09:46.313  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:09:46.314  3784  3835 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:09:46.313  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.314  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-06 19:09:46.314  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:46.314  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:46.314  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:46.315  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 19:09:46.315  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.315  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.315  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.315  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:46.315  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:46.315  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:09:46.316  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 removed from the list
09-06 19:09:46.316  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.316  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 removed from the list
,09-06 19:09:46.322  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.323  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.323  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.323  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:46.323  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:46.325  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.325  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:09:46.325  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.325  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.327  3784  3835 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-06 19:09:46.327  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.327  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:46.327  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.327  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.328  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.328  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.328  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.328  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:46.328  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.328  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.328  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.328  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.328  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.328  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.329  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.329  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.329  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.329  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
,09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:09:46.333  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:46.334  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:46.335  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:46.335  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.335  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.335  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.335  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.335  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.335  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.335  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.335  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.335  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.335  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.335  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.335  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.335  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.335  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.337  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.337  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.337  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.337  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.337  3784  3835 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:09:46.338  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:46.343  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:46.349  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:46.349  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:46.349  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:46.350  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:09:46.350  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:09:46.350  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:46.350  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:09:46.353  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.355  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:09:46.355  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:09:46.359  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.363  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:46.364  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:09:46.364  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:46.368  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-06 19:09:46.371  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-06 19:09:46.371  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-06 19:09:46.371  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:46.372  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:46.373  3784  3835 D BluetoothAdapter: STATE_ON
,09-06 19:09:46.377  2674  2685 D BtGatt.GattService: registerClient() - UUID=3dffed9e-60c2-4b75-98a1-296a5cde4ffe
,09-06 19:09:46.378  2674  2698 D BtGatt.GattService: onClientRegistered() - UUID=3dffed9e-60c2-4b75-98a1-296a5cde4ffe, clientIf=5
,09-06 19:09:46.379  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:09:46.381  2674  2790 D BtGatt.GattService: start scan with filters
,09-06 19:09:46.389  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:46.390  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:09:46.390  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:09:46.390  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:09:46.390  2674  2701 D BtGatt.ScanManager: handling starting scan,
,09-06 19:09:46.393  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:46.393  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:09:46.393  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:46.394  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:09:46.395  2674  2701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:46.396  3784  3835 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:46.400  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.400  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:46.400  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.400  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:09:46.400  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:46.400  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:09:46.400  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:46.400  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:46.400  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:09:46.400  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:46.401  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:46.401  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:09:46.401  3784  3835 D BluetoothAdapter: STATE_ON
09-06 19:09:46.402  2674  2685 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:46.402  2674  2790 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:09:46.403  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:09:46.403  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:46.403  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:46.403  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:09:46.403  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:09:46.404  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:46.404  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:46.404  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:46.404  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:46.407  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:46.409  2674  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:09:46.409  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.409  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:09:46.410  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:46.410  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:46.409  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:46.411  2674  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:09:46.415  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:46.415  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
,09-06 19:09:46.415  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:46.416  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
,09-06 19:09:46.416  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:46.416  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:46.416  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.417  3784  3835 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
09-06 19:09:46.418  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:46.421  2674  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:09:46.422  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-06 19:09:46.422  2674  2701 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:09:46.422  2674  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,09-06 19:09:46.423  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:46.425  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:46.425  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:46.425  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:46.425  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:46.425  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:09:46.426  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:46.426  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:09:46.429  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 19:09:46.429  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-06 19:09:46.431  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.433  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:09:46.433  2674  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:09:46.433  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.434  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:09:46.434  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:46.436  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.440  2674  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 19:09:46.440  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.440  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:09:46.440  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:46.441  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:46.441  3784  3835 D BluetoothAdapter: STATE_ON
,09-06 19:09:46.445  2674  2780 D BtGatt.GattService: registerClient() - UUID=23164d3e-d7f0-4b3e-972e-26158fe0065c
,09-06 19:09:46.446  2674  2698 D BtGatt.GattService: onClientRegistered() - UUID=23164d3e-d7f0-4b3e-972e-26158fe0065c, clientIf=5
,09-06 19:09:46.446  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:09:46.447  2674  2685 D BtGatt.GattService: start scan with filters
09-06 19:09:46.449  2674  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:09:46.449  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.449  2674  2701 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:09:46.452  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:46.452  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:09:46.452  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:09:46.452  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:46.455  2674  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:09:46.455  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.456  2674  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 19:09:46.458  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:46.458  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:46.458  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:09:46.461  2674  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 19:09:46.461  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.462  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:46.463  2674  2701 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:46.466  3784  3835 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:46.468  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.468  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:46.469  2674  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:09:46.469  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.469  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.469  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:09:46.469  2674  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:09:46.469  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.469  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:46.469  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:46.469  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:46.469  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:09:46.469  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:46.469  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:46.469  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:46.471  3784  3835 D BluetoothAdapter: STATE_ON
09-06 19:09:46.471  2674  2686 D BtGatt.GattService: stopScan() - queue size =1
09-06 19:09:46.472  2674  2685 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 19:09:46.472  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:09:46.472  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:09:46.472  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:46.472  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:09:46.472  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:09:46.473  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:46.473  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:46.473  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:09:46.474  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:09:46.474  2674  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:09:46.474  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.474  2674  2701 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:09:46.474  2674  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:09:46.474  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:46.476  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:46.476  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:46.476  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:46.476  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.476  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.476  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:46.476  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.476  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.477  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
,09-06 19:09:46.477  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.477  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:46.477  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.477  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:46.478  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.478  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.478  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.478  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.479  3784  3835 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:09:46.481  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:46.485  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:46.487  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.487  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:46.487  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:46.487  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:46.487  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:46.487  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:46.487  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:09:46.488  2674  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:09:46.489  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:09:46.489  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.490  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:09:46.490  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:09:46.491  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.493  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:46.493  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:09:46.493  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:46.496  2674  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 19:09:46.496  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.497  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:09:46.497  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:46.497  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:09:46.497  3784  3835 D BluetoothAdapter: STATE_ON
,09-06 19:09:46.499  2674  2686 D BtGatt.GattService: registerClient() - UUID=71457d03-6987-447c-aafb-0d93401eae9a
09-06 19:09:46.500  2674  2698 D BtGatt.GattService: onClientRegistered() - UUID=71457d03-6987-447c-aafb-0d93401eae9a, clientIf=5
,09-06 19:09:46.500  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 19:09:46.500  2674  2790 D BtGatt.GattService: start scan with filters
,09-06 19:09:46.503  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:46.503  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:09:46.503  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:09:46.503  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:46.505  2674  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:09:46.505  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.505  2674  2701 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:09:46.506  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:46.506  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:09:46.506  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:46.507  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:46.509  3784  3835 I io.jxcore.node.ConnectionHelper: start: OK
09-06 19:09:46.509  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.509  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:46.509  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.509  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:09:46.509  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.509  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:46.509  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:46.509  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:46.509  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:46.509  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:46.509  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:46.509  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:09:46.510  3784  3835 D BluetoothAdapter: STATE_ON
,09-06 19:09:46.510  2674  2790 D BtGatt.GattService: stopScan() - queue size =0
09-06 19:09:46.511  2674  2685 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:09:46.511  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:09:46.511  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:09:46.511  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:46.511  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:46.511  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:09:46.512  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:46.512  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:46.512  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:46.512  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:09:46.513  2674  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:09:46.513  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:09:46.513  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:46.513  2674  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:09:46.514  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:46.514  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:46.514  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:46.514  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.514  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:09:46.514  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.514  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.514  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.515  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.515  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:46.515  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.515  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.515  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
,09-06 19:09:46.515  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.515  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.515  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.515  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.516  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.516  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.516  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.516  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
,09-06 19:09:46.516  3784  3835 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:09:46.517  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.517  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.517  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.517  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.517  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.517  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:46.517  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.517  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.518  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.518  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.518  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.518  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.518  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.518  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:46.519  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.519  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.519  2674  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:09:46.519  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.519  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.519  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.520  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-06 19:09:46.520  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.520  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.520  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.520  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.520  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.520  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.520  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
,09-06 19:09:46.520  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.520  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.523  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.522  2674  2701 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:46.523  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.523  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.523  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.523  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.524  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.524  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.524  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.524  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
,09-06 19:09:46.525  3784  3835 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:09:46.525  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.525  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.525  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.525  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.525  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:46.525  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.525  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.525  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.525  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.525  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.525  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.525  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.525  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.525  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:46.526  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.526  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.526  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.526  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.527  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:09:46.527  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.527  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.527  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:09:46.527  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.527  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.527  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.527  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.527  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.527  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.527  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.527  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.527  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.528  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.528  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.528  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.528  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.528  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.528  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.529  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:09:46.529  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:46.529  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:46.529  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:46.529  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:09:46.529  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:46.529  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.529  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.529  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.530  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.530  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.530  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.530  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.530  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.530  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.530  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.530  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.530  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.530  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.530  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.531  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.531  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.531  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.531  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.531  2674  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 19:09:46.531  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:46.531  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.532  3784  3835 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:46.532  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:46.532  2674  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 19:09:46.534  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:46.535  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:46.535  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:46.536  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:46.536  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:09:46.536  3784  3835 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:46.537  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:09:46.537  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:46.537  3784  3835 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:46.537  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:09:46.537  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:46.537  3784  3835 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:46.537  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:46.539  2674  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:09:46.540  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.540  2674  2701 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:46.540  2674  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:09:46.541  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:09:46.542  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:09:46.542  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:09:46.543  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:09:46.543  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:09:46.543  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:09:46.543  3784  3835 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:46.543  3784  3835 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:09:46.543  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.543  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.544  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.544  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.544  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.544  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.544  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:09:46.544  3784  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
09-06 19:09:46.544  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.544  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.544  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.544  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:46.544  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.545  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.545  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.545  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.545  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.545  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.545  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.545  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.546  3784  3851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:46.546  3784  3835 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:09:46.547  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.547  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.547  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.547  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.547  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.547  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.547  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.547  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.547  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.547  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.547  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.547  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.547  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.547  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.548  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.549  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.549  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.549  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.549  3784  3835 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:09:46.549  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.549  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.550  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.550  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.550  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.550  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.550  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.550  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.550  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.550  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.550  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.550  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.550  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.550  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.551  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.551  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.551  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.552  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.553  3784  3835 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:09:46.553  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:09:46.554  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:46.554  3784  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
09-06 19:09:46.554  3784  3835 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:09:46.554  3784  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 389)
09-06 19:09:46.554  3784  3835 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:09:46.554  2674  2778 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-06 19:09:46.554  3784  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
09-06 19:09:46.554  3784  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 389)
09-06 19:09:46.555  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:09:46.555  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:46.555  3784  3835 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:09:46.555  3784  3835 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:09:46.555  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:46.555  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:46.555  3784  3835 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:09:46.555  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.555  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.555  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.555  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.555  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.555  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.555  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.555  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.556  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.556  2674  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:09:46.556  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.556  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.556  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.556  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.556  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.556  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.557  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.557  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.557  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.557  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.558  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.558  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.558  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.558  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.558  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.558  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.558  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.558  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.558  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.558  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.558  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.558  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.558  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.558  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.559  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.559  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.559  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.559  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.559  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.559  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.559  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.559  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.559  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.559  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.559  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.559  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.559  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.559  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.559  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.560  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.560  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.560  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.560  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.561  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:09:46.561  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:46.562  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:09:46.563  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:09:46.563  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:09:46.563  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:09:46.563  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:46.563  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.563  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:09:46.564  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:09:46.564  3784  3784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:09:46.564  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:09:46.564  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.564  3784  3835 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:09:46.564  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.564  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.564  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:46.564  3784  3853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:46.564  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:46.564  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:46.564  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.564  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.564  3784  3784 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:09:46.565  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:46.565  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.565  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:46.565  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.565  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:46.565  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.565  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.565  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:46.565  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.565  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.565  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.565  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.565  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.565  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.565  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.565  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.565  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.566  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.566  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.566  3784  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 19:09:46.566  3784  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:09:46.566  3784  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 19:09:46.566  3784  3784 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:09:46.566  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.566  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.566  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.567  2674  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:09:46.567  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.567  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.568  3784  3835 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:09:46.568  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:09:46.568  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:46.568  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:46.568  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.568  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.568  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.568  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.568  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.569  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.569  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.569  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.569  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.569  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.569  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.569  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.569  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.569  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.570  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.570  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.570  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.570  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.573  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.573  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.573  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.573  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.574  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.574  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.574  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.574  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.574  2674  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:09:46.574  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.574  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.574  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.574  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.574  2674  2701 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:09:46.574  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.574  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.575  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.576  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.576  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.576  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.576  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.577  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:46.577  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:46.577  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:46.577  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:46.577  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.577  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.577  3784  3835 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f20963 not in the list
09-06 19:09:46.577  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.577  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.577  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:46.577  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.577  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.577  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:46.577  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:46.578  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:46.578  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:46.578  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:46.579  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57c5960 not in the list
09-06 19:09:46.579  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:09:46.579  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:46.580  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:09:46.580  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:46.580  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:09:46.580  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:46.580  2674  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 19:09:46.580  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.580  2674  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:09:46.582  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:09:46.582  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:09:46.582  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:09:46.583  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:46.583  3784  3835 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:09:46.583  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:46.583  3784  3835 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:09:46.583  3784  3835 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:09:46.583  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:09:46.583  3784  3835 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:09:46.584  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:09:46.584  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:09:46.584  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:09:46.584  3784  3835 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:09:46.585  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:46.585  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a28ad42 added. We now have 2 listener(s)
09-06 19:09:46.585  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:46.586  2674  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:09:46.586  2674  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:09:46.586  3784  3835 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 19:09:46.587   870  1975 D WifiService: setWifiEnabled: true pid=3784, uid=10000
09-06 19:09:46.587   870  1975 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 19:09:46.587  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:46.588  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b281153 added. We now have 3 listener(s)
09-06 19:09:46.588  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:46.593  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:46.593  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e88da90 added. We now have 4 listener(s)
09-06 19:09:46.593  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:46.594  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:46.594  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3d1f89 added. We now have 5 listener(s)
09-06 19:09:46.594  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:46.596   870  1602 D WifiService: setWifiEnabled: false pid=3784, uid=10000
09-06 19:09:46.596   870  1602 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:09:46.603  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:46.603  2674  2694 D BluetoothAdapterState: Current state: ON, message: 23
09-06 19:09:46.603  2674  2694 D BluetoothAdapterProperties: Setting state to 13
09-06 19:09:46.603  2674  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:09:46.604  2674  2694 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:09:46.606  2674  2674 D BluetoothMapService: onReceive
09-06 19:09:46.606  2674  2674 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:46.606  2674  2674 D BluetoothMapService: STATE_TURNING_OFF
09-06 19:09:46.606  2674  2674 D BluetoothMapService: MAP Service closeService in
09-06 19:09:46.606  2674  2674 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 19:09:46.606  2674  2674 D ObexServerSockets0: shutdown(block = true)
09-06 19:09:46.607  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:09:46.607  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:09:46.607  2674  2794 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 19:09:46.607  2674  2778 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 19:09:46.608  2674  2793 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-06 19:09:46.608  2674  2694 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:09:46.608  2674  2674 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:46.608  2674  3436 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:09:46.609  2674  3436 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:09:46.611  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:46.611  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:46.612  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:46.612  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.612  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:46.614  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.615  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.616  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 19:09:46.618  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:46.618  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:46.618   870  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:09:46.618   870  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-06 19:09:46.618   870  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:09:46.619   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:09:46.619   870   885 I ActivityManager: Start proc 3856:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-06 19:09:46.619  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:46.619  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:46.620  2674  2698 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:46.620  2674  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 19:09:46.622  2674  2674 D HeadsetService: Received stop request...Stopping profile...
09-06 19:09:46.623  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.624   870   870 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:46.624   870   870 D BluetoothHeadset: Proxy object disconnected
,09-06 19:09:46.624  1363  2038 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:46.624  1363  1363 D HeadsetProfile: Bluetooth service disconnected
09-06 19:09:46.625   870   870 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:46.625  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.625  1949  2084 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:46.625  2674  2674 D A2dpService: Received stop request...Stopping profile...
09-06 19:09:46.626  2674  2785 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:09:46.627  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.630   870  2082 D DhcpClient: Clearing IP address
09-06 19:09:46.630   373   868 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:09:46.631   870   870 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:46.632  1363  1363 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:46.632  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:46.632  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:46.632  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:46.632  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:09:46.633  2674  2674 D HidService: Received stop request...Stopping profile...
09-06 19:09:46.633  2674  2674 D HidService: Stopping Bluetooth HidService
09-06 19:09:46.634  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:46.634  1363  1363 D HidProfile: Bluetooth service disconnected
,09-06 19:09:46.634  1501  2558 V NativeCrypto: Read error: ssl=0x9ae94e00: I/O error during system call, Connection timed out
,09-06 19:09:46.634   373   868 D CommandListener: Setting iface cfg
,09-06 19:09:46.635  1501  2558 V NativeCrypto: SSL shutdown failed: ssl=0x9ae94e00: I/O error during system call, Broken pipe
,09-06 19:09:46.637   870  2140 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-06 19:09:46.637   870  2067 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-06 19:09:46.637  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:09:46.637  2674  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:46.637  2674  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:46.637  2674  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:09:46.638   870  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-06 19:09:46.638   870  2067 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-06 19:09:46.637  2674  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 19:09:46.639   870  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:09:46.639  2674  2698 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-06 19:09:46.639  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:09:46.641   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 19:09:46.641   396   396 E Parcel  : Reading a NULL string not supported here.
09-06 19:09:46.641   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-06 19:09:46.641   870  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-06 19:09:46.642   870  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 19:09:46.642   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-06 19:09:46.644  2674  2674 D HealthService: Received stop request...Stopping profile...
09-06 19:09:46.646   373   868 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:09:46.646  2674  2674 D PanService: Received stop request...Stopping profile...
09-06 19:09:46.648  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:46.648  1363  1363 D PanProfile: Bluetooth service disconnected
09-06 19:09:46.648   870  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 19:09:46.648  2674  2674 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:09:46.649  2674  2674 D BluetoothMapService: stop()
09-06 19:09:46.654   870  2085 D DhcpClient: Receive thread stopped
,09-06 19:09:46.652  2674  2674 D BluetoothMapAppObserver: deinitObservers()
09-06 19:09:46.655  2674  2674 D BluetoothMapAppObserver: removeReceiver()
09-06 19:09:46.657   870  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 19:09:46.661  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:46.661  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:46.661  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:46.661  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:09:46.661  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:46.661  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:46.662  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:46.662  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:46.662  2674  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 19:09:46.662  2674  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:46.662   870  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:09:46.662  2674  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:09:46.662  2674  2755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:46.663  2674  2755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:46.663  2674  2755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:46.663  2674  2755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:46.663  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-06 19:09:46.663  2674  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:09:46.663  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:46.663  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:46.664  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:09:46.664  2674  2698 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:09:46.664  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:09:46.664  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:46.664  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:46.664  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:46.664  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:46.664  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:46.664  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:46.664  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:09:46.664  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:46.664  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:09:46.665  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:46.665  2674  2674 D BluetoothMapService: MAP Service closeService in
09-06 19:09:46.665  2674  2674 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:46.665  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:46.665  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:46.665  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:46.665  2674  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 19:09:46.666  2674  2694 D BluetoothAdapterProperties: Setting state to 15
09-06 19:09:46.666  2674  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 19:09:46.666  2674  2674 D BluetoothMapService: cleanup()
09-06 19:09:46.666  2674  2674 D BluetoothMapService: MAP Service closeService in
,09-06 19:09:46.666  2674  2694 I BluetoothAdapterState: Entering BleOnState
09-06 19:09:46.666  1363  1363 D BluetoothMap: Proxy object disconnected
09-06 19:09:46.666  1363  1363 D MapProfile: Bluetooth service disconnected
09-06 19:09:46.668  1363  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:09:46.669  1363  2038 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:09:46.669  1363  1372 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:09:46.670  1363  1377 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:09:46.670   870   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:46.670   870   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:46.670  1363  2038 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:09:46.671   870   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:46.671  1363  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:46.671   870   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:46.671  1949  2388 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:46.672  2674  2694 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 19:09:46.672  2674  2694 D BluetoothAdapterProperties: Setting state to 16
09-06 19:09:46.672  2674  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 19:09:46.672  2674  2694 D BluetoothAdapterProperties: onBleDisable
,09-06 19:09:46.672  2674  2694 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:09:46.673  2674  2695 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 19:09:46.674  2674  2755 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:09:46.674  2674  2755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:46.674  2674  2698 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:46.675  1909  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:46.676  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.677  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.681  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.682  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.698   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 19:09:46.710  3856  3856 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-06 19:09:46.715   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-06 19:09:46.716   870  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-06 19:09:46.716   870  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:46.719   870   889 D Tethering: MasterInitialState.processMessage what=3
09-06 19:09:46.721  3404  3404 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9904690 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-06 19:09:46.721  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:46.722  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.739  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:46.743   870   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85e8ef4:true
,09-06 19:09:46.744  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:46.756   870  2136 I ActivityManager: Start proc 3877:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-06 19:09:46.764  3856  3856 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 19:09:46.767  3856  3856 D BluetoothMap: Create BluetoothMap proxy object
,09-06 19:09:46.774   373   868 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:09:46.775   870  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 19:09:46.776  3856  3856 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-06 19:09:46.786  3877  3877 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-06 19:09:46.789  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:46.796   870  2139 I ActivityManager: Killing 3404:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-06 19:09:46.877  2674  2698 I bt_hci  : shut_down
,09-06 19:09:46.877  2674  2702 D bt_hwcfg: hw_epilog_process
,09-06 19:09:46.879  2674  2702 I bt_vendor: low_power_mode_cb
,09-06 19:09:46.908  2674  2702 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:09:46.908  2674  2702 I bt_vendor: epilog_cb
,09-06 19:09:46.909  2674  2702 I bt_hci  : epilog_finished_callback
,09-06 19:09:46.919  2674  2698 I bt_hci_h4: hal_close
,09-06 19:09:46.920  2674  2698 I bt_userial_vendor: device fd = 51 close
,09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.k.d(PG:583)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:09:46.983  3877  3877 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:09:46.983  3877  3877 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:09:47.038   870  1376 I ActivityManager: Start proc 3908:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-06 19:09:47.040   870  1376 I ActivityManager: Killing 3563:com.google.process.gapps/u0a99 (adj 15): empty #17
09-06 19:09:47.066  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:09:47.103  2674  2695 D bt_stack_manager: event_shut_down_stack finished.
,09-06 19:09:47.104  2674  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:09:47.108  2674  2674 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:09:47.110  2674  2694 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-06 19:09:47.111  2674  2674 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:09:47.111  2674  2674 D BtGatt.GattService: stop()
,09-06 19:09:47.111  2674  2674 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:09:47.115  2674  2674 V BluetoothAdapterState: isTurningOff()=false
09-06 19:09:47.115  2674  2674 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:47.115  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:09:47.115  2674  2674 V BluetoothAdapterState: isBleTurningOff()=true
,09-06 19:09:47.116  2674  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-06 19:09:47.116  2674  2694 D BluetoothAdapterProperties: Setting state to 10
,09-06 19:09:47.116  2674  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10,
09-06 19:09:47.117  2674  2694 I BluetoothAdapterState: Entering OffState
,09-06 19:09:47.118   870   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 19:09:47.121  3908  3908 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-06 19:09:47.125  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-06 19:09:47.125  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-06 19:09:47.127  2674  2695 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 19:09:47.125  2674  2674 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:09:47.134  2674  2695 D bt_stack_manager: event_clean_up_stack finished.
,09-06 19:09:47.138  2674  2674 I art     : System.exit called, status: 0
,09-06 19:09:47.138  2674  2674 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:09:47.193  3908  3908 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-06 19:09:47.207  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:47.210   870  1879 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-06 19:09:47.210   870  1879 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-06 19:09:47.211   870  1879 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-06 19:09:47.211   870  1879 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-06 19:09:47.211   870  1879 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-06 19:09:47.229   870  1879 I ActivityManager: Start proc 3936:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-06 19:09:47.231   870  2136 W ActivityManager: Spurious death for ProcessRecord{aedc530 3936:com.android.bluetooth/1002}, curProc for 2674: null
09-06 19:09:47.232  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:47.241  3877  3899 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:09:47.260   870   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad49754:true
,09-06 19:09:47.303  3936  3936 D AdapterServiceConfig: Adding HeadsetService
,09-06 19:09:47.303  3936  3936 D AdapterServiceConfig: Adding A2dpService
,09-06 19:09:47.304  3936  3936 D AdapterServiceConfig: Adding HidService
09-06 19:09:47.304  3936  3936 D AdapterServiceConfig: Adding HealthService
,09-06 19:09:47.304  3936  3936 D AdapterServiceConfig: Adding PanService
09-06 19:09:47.304  3936  3936 D AdapterServiceConfig: Adding GattService
,09-06 19:09:47.304  3936  3936 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:09:47.305   870  2139 I ActivityManager: Killing 3456:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-06 19:09:47.345  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:47.360  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:09:47.364  1721  1721 D SystemUpdateService: onCreate
,09-06 19:09:47.376  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:09:47.388  1721  3948 I SystemUpdateService: active receiver: enabled
,09-06 19:09:47.393  1721  3948 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:09:47.394  1721  3948 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-06 19:09:47.397  1721  3948 I SystemUpdateService: now status is 0 (complete)
09-06 19:09:47.397  1721  3948 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:09:47.397  1721  3948 I SystemUpdateService: file has been verified
,09-06 19:09:47.398  1721  3948 I SystemUpdateService: OTA package size = 12249756
,09-06 19:09:47.402  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:09:47.405  1721  2520 I iu.UploadsManager: num queued entries: 0
,09-06 19:09:47.405  1721  2520 I iu.UploadsManager: num updated entries: 0
09-06 19:09:47.406  1721  3948 I SystemUpdateService: showing system update notification
09-06 19:09:47.406  1721  2520 I iu.SyncManager: NEXT; no task
,09-06 19:09:47.422  1721  1721 D SystemUpdateService: onDestroy
,09-06 19:09:47.429  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:09:47.430  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:09:47.447   870  1975 I ActivityManager: Start proc 3950:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-06 19:09:47.514  3950  3950 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-06 19:09:47.516  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:47.526  3950  3950 D SprintDMHelper: simOperator: 
,09-06 19:09:47.526  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:09:47.569   870  1975 I ActivityManager: Start proc 3962:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-06 19:09:47.570   870  1975 I ActivityManager: Killing 3504:android.process.acore/u0a5 (adj 15): empty #17
,09-06 19:09:47.790   870  2139 I ActivityManager: Start proc 3977:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-06 19:09:47.795   870  2136 I ActivityManager: Killing 3640:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-06 19:09:47.884  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-06 19:09:47.962  3977  3977 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:09:47.962  3977  3977 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:09:47.962  3977  3977 I GAv4    :   adb logcat -s GAv4
,09-06 19:09:47.978  3977  3977 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:47.985  3977  3977 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:48.007  3977  3994 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:48.119  3977  3977 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-06 19:09:48.154  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-06 19:09:48.164  3977  3977 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1451-1457)
09-06 19:09:48.164  3977  3977 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:09:48.172  3977  3977 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fca73c0}
,09-06 19:09:48.172  3977  3977 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:09:48.172  3977  3977 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:09:48.178  3977  3977 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 19:09:48.179  3977  3977 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:09:48.192  3977  3977 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 19:09:48.203  3977  3977 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:09:48.203  3977  3977 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 19:09:48.203  3977  3977 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:09:48.203  3977  3977 I Adreno  : Build Date                       : 10/20/15
09-06 19:09:48.203  3977  3977 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:09:48.203  3977  3977 I Adreno  : Local Branch                     : M14
09-06 19:09:48.203  3977  3977 I Adreno  : Remote Branch                    : 
09-06 19:09:48.203  3977  3977 I Adreno  : Remote Branch                    : 
09-06 19:09:48.203  3977  3977 I Adreno  : Reconstruct Branch               : 
,09-06 19:09:48.263  3977  3977 I NSApplication: Starting up...
,09-06 19:09:48.270  3977  4023 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 19:09:48.306   870  2139 I ActivityManager: Start proc 4028:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-06 19:09:48.308   870  2139 I ActivityManager: Killing 3657:com.android.musicfx/u0a18 (adj 15): empty #17
,09-06 19:09:48.380  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-06 19:09:48.562   870  2140 I ActivityManager: Killing 2203:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-06 19:09:49.614   870  2140 D WifiService: setWifiEnabled: true pid=3784, uid=10000
09-06 19:09:49.615   870  2140 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:09:49.631   870  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:09:49.639  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:49.639  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:49.639  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:49.640  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:49.643  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:49.644  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:49.644  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:49.644  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:49.664   870  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:09:49.665   870  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-06 19:09:49.666   870  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 19:09:49.667   870  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:09:49.667   870  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-06 19:09:49.667   870  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-06 19:09:49.668   870  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:09:49.684   373   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:09:49.684   870  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=11.25 delta 1000 -> 994
,09-06 19:09:49.685   373   868 D CommandListener: Setting iface cfg
,09-06 19:09:49.686   870  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-06 19:09:49.686   870  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:09:49.694   870  1304 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 19:09:49.694   870  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:09:49.694   870  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-06 19:09:49.694   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:49.702   870  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:09:49.782   870  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:09:49.786  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:09:50.208  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:09:50.245  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:09:50.247  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 19:09:50.251   870  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:09:50.262   870  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:09:50.262   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:09:50.262   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 19:09:50.288   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:50.302   373   868 D CommandListener: Setting iface cfg
,09-06 19:09:50.302   870  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:09:50.327   870  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-06 19:09:50.333   870  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 19:09:50.360   870  4051 D DhcpClient: Receive thread started
,09-06 19:09:50.445   870  1306 E native  : do suspend false
,09-06 19:09:50.465   870  2082 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 19:09:50.485   870  4051 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172690, domain null
,09-06 19:09:50.487   870  2082 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172690 seconds
,09-06 19:09:50.490   870  2082 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:09:50.503   870  4051 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 19:09:50.504   870  2082 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 19:09:50.509   373   868 D CommandListener: Setting iface cfg
,09-06 19:09:50.521   870  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 19:09:50.521   870  2082 D DhcpClient: Scheduling renewal in 86399s
,09-06 19:09:50.545   870  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 19:09:50.548   870  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:09:50.548   870  1306 D WifiConfigStore: No blacklist allowed without epno enabled
09-06 19:09:50.550   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-06 19:09:50.552   870  1310 D ConnectivityService: Adding iface wlan0 to network 101
,09-06 19:09:50.562   870  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:09:50.634   870  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:09:50.635   870  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-06 19:09:50.638   870  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-06 19:09:50.640   870  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-06 19:09:50.643   870  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-06 19:09:50.653   870  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:09:50.659   870  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-06 19:09:50.659   870  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-06 19:09:50.660   870  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 19:09:50.661   870  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 19:09:50.662   870  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-06 19:09:50.662   870  1310 D ConnectivityService:    accepting network in place of null
,09-06 19:09:50.663   870  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:09:50.675   870  4050 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133968, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 19:09:50.725   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:09:50.749   870  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:816::200e
,09-06 19:09:50.782   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:09:50.791   870  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 19:09:50.791   870  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:50.792   870  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-06 19:09:50.794   870   889 D Tethering: MasterInitialState.processMessage what=3
09-06 19:09:50.818  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:50.818  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:50.818  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:50.819  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:50.822  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:50.822  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:50.822  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:50.822  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:50.829  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-06 19:09:50.832  1721  1721 D SystemUpdateService: onCreate
,09-06 19:09:50.836  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:09:50.838   870  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 17:09:50 GMT], X-Android-Received-Millis=[1473181790837], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473181790807]}
,09-06 19:09:50.838  1721  4061 I SystemUpdateService: active receiver: enabled
,09-06 19:09:50.839   870  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-06 19:09:50.839   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-06 19:09:50.839   870  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 19:09:50.840   870  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 19:09:50.847  1721  4061 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:09:50.850  1721  4061 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-06 19:09:50.850  1721  4061 I SystemUpdateService: now status is 0 (complete)
,09-06 19:09:50.850  1721  4061 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:09:50.850  1721  4061 I SystemUpdateService: file has been verified
09-06 19:09:50.850  1721  4061 I SystemUpdateService: OTA package size = 12249756
,09-06 19:09:50.856  1721  4061 I SystemUpdateService: showing system update notification
,09-06 19:09:50.861  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:09:50.865  1721  2520 I iu.UploadsManager: num queued entries: 0
,09-06 19:09:50.865  1721  2520 I iu.UploadsManager: num updated entries: 0
,09-06 19:09:50.867  1721  2520 I iu.SyncManager: NEXT; no task
,09-06 19:09:50.868  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:09:50.870  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:09:50.872  1721  4066 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-06 19:09:50.872  1721  4066 W BaseAppContext: Using Auth Proxy for data requests.
09-06 19:09:50.873  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:50.873  1721  4066 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 19:09:50.877  1721  1721 D SystemUpdateService: onDestroy
09-06 19:09:50.877  3950  3950 D SprintDMHelper: simOperator: 
09-06 19:09:50.877  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:09:50.908  1501  2069 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 19:09:50.908  1501  2069 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 19:09:50.908  1501  2069 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:09:50.908  1501  2069 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:09:50.922  1721  4066 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-06 19:09:51.002  2270  4068 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 19:09:51.189  1501  4073 I GCM     : Ack for not saved message 136
,09-06 19:09:51.791   870  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 19:09:52.279   870  1879 I ActivityManager: Killing 3679:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-06 19:09:52.626   870   881 D WifiService: setWifiEnabled: false pid=3784, uid=10000
,09-06 19:09:52.626   870   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:09:52.661  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-06 19:09:52.672   870  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 19:09:52.672   870  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-06 19:09:52.672   870  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:09:52.673   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:52.696   870  2082 D DhcpClient: Clearing IP address
,09-06 19:09:52.697   373   868 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:52.711  1501  4073 V NativeCrypto: Read error: ssl=0x9a5ce600: I/O error during system call, Connection timed out
,09-06 19:09:52.716  1501  4073 V NativeCrypto: SSL shutdown failed: ssl=0x9a5ce600: I/O error during system call, Broken pipe
,09-06 19:09:52.718   373   868 D CommandListener: Setting iface cfg
,09-06 19:09:52.722   870  4051 D DhcpClient: Receive thread stopped
,09-06 19:09:52.724   870  1954 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
09-06 19:09:52.725   870  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-06 19:09:52.725   870  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:816::200e
,09-06 19:09:52.733   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 19:09:52.733   870  4049 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-06 19:09:52.733   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-06 19:09:52.736   396   396 E Parcel  : Reading a NULL string not supported here.
09-06 19:09:52.736   870  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-06 19:09:52.737   870  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:09:52.741   373   868 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:52.748   870  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-06 19:09:52.748   870  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 19:09:52.751  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:52.751  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:52.751  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:52.751  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:52.752  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:52.752  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:52.753  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:52.753  1909  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:52.753  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:52.757   870  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 19:09:52.777   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:09:52.814   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:09:52.816   870  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 19:09:52.816   870  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:52.820   870   889 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:09:52.821  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:52.822  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:52.828  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:09:52.830  1721  1721 D SystemUpdateService: onCreate
,09-06 19:09:52.833  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:09:52.842  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:09:52.843  1721  2520 I iu.UploadsManager: num queued entries: 0
,09-06 19:09:52.844  1721  2520 I iu.UploadsManager: num updated entries: 0
09-06 19:09:52.844  1721  2520 I iu.SyncManager: NEXT; no task
,09-06 19:09:52.849  1721  4083 I SystemUpdateService: active receiver: enabled
,09-06 19:09:52.851  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:09:52.853  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:09:52.855  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:52.859  3950  3950 D SprintDMHelper: simOperator: 
09-06 19:09:52.859  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:09:52.883  1721  4083 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:09:52.889  2270  4087 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-06 19:09:52.917  1721  4083 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 19:09:52.917  1721  4083 I SystemUpdateService: now status is 0 (complete)
09-06 19:09:52.917  1721  4083 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 19:09:52.917  1721  4083 I SystemUpdateService: file has been verified
,09-06 19:09:52.917  1721  4083 I SystemUpdateService: OTA package size = 12249756
,09-06 19:09:52.918   373   868 E Netd    : netlink response contains error (No such file or directory)
,09-06 19:09:52.920   870  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-06 19:09:52.920   870  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 19:09:52.934  1721  4083 I SystemUpdateService: showing system update notification
,09-06 19:09:52.948  1721  1721 D SystemUpdateService: onDestroy
,09-06 19:09:55.679   870   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4e1cf86:true
09-06 19:09:55.679  3936  3936 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 19:09:55.685  3936  3936 I bt_bluedroid: init
,09-06 19:09:55.686  3936  4090 I BluetoothAdapterState: Entering OffState
,09-06 19:09:55.691  3936  4091 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:09:55.692  3936  4091 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:09:55.692  3936  4091 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:09:55.692  3936  4091 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:09:55.694  3936  3936 I bt_bluedroid: get_profile_interface socket,
,09-06 19:09:55.699  3936  3936 I bt_bluedroid: get_profile_interface sdp
,09-06 19:09:55.699  3936  4094 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:09:55.703  3936  4094 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:09:55.705  3936  3946 I bt_bluedroid: config_hci_snoop_log
,09-06 19:09:55.709   870   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:09:55.717  3936  4090 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 19:09:55.718  3936  4090 D BluetoothAdapterProperties: Setting state to 14
,09-06 19:09:55.718  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:09:55.722  3936  4090 D BluetoothBondStateMachine: make
,09-06 19:09:55.727  3936  4095 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:09:55.733  3936  4090 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:09:55.736  3936  3936 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:09:55.743  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:55.745  3936  3936 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:09:55.746  3936  3936 D BtGatt.GattService: Received start request. Starting profile...
,09-06 19:09:55.746  3936  3936 D BtGatt.GattService: start()
,09-06 19:09:55.747  3936  3936 I bt_bluedroid: get_profile_interface gatt
,09-06 19:09:55.749  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:55.749  3936  3936 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:09:55.760  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:09:55.760  3936  3936 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:09:55.760  3936  3936 V BluetoothAdapterState: isBleTurningOn()=true
,09-06 19:09:55.761  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:55.761  3936  4090 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-06 19:09:55.762  3936  4090 I bt_bluedroid: enable
,09-06 19:09:55.762  3936  4091 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 19:09:55.763  3936  4091 I bt_hci  : start_up
,09-06 19:09:55.776  3936  4091 I bt_vendor: alloc value 0xb3a29189
09-06 19:09:55.776  3936  4091 I bt_vendor: init
,09-06 19:09:55.776  3936  4091 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 19:09:55.776  3936  4091 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:09:55.885  3936  4091 D bt_hci  : start_up starting async portion
,09-06 19:09:55.886  3936  4098 I bt_hci  : event_finish_startup
,09-06 19:09:55.886  3936  4098 I bt_hci_h4: hal_open
09-06 19:09:55.887  3936  4098 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:09:55.897  3936  4098 I bt_userial_vendor: device fd = 51 open
,09-06 19:09:55.927  3936  4098 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:09:55.959  3936  4098 D bt_hwcfg: Chipset BCM4354A2
,09-06 19:09:55.959  3936  4098 D bt_hwcfg: Target name = [BCM4354A2]
09-06 19:09:55.960  3936  4098 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:09:56.629  3936  4098 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:09:56.630  3936  4098 D bt_hwcfg: Settlement delay -- 100 ms
09-06 19:09:56.631  3936  4098 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:09:56.748  3936  4098 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:09:56.750  3936  4098 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:09:56.778  3936  4098 I bt_hwcfg: vendor lib fwcfg completed
,09-06 19:09:56.779  3936  4098 I bt_vendor: firmware callback
,09-06 19:09:56.779  3936  4098 I bt_hci  : firmware_config_callback
,09-06 19:09:56.790  3936  4101 I bt_btu  : btu_task pending for preload complete event
,09-06 19:09:56.790  3936  4101 I bt_btu_task: Bluetooth chip preload is complete
,09-06 19:09:56.790  3936  4101 I bt_btu  : btu_task received preload complete event
,09-06 19:09:56.802  3936  4101 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:09:56.802  3936  4101 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-06 19:09:56.803  3936  4101 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 19:09:56.803  3936  4101 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-06 19:09:56.803  3936  4101 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-06 19:09:56.804  3936  4101 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 19:09:56.804  3936  4101 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-06 19:09:56.804  3936  4101 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 19:09:56.804  3936  4101 I         : BTE_InitTraceLevels -- TRC_GAP
,09-06 19:09:56.805  3936  4101 I         : BTE_InitTraceLevels -- TRC_PAN
,09-06 19:09:56.805  3936  4101 I         : BTE_InitTraceLevels -- TRC_SDP
,09-06 19:09:56.805  3936  4101 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 19:09:56.805  3936  4101 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:09:56.806  3936  4101 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:09:56.806  3936  4101 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:09:56.941  3936  4101 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a6d9d
,09-06 19:09:56.941  3936  4101 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a6d9d 
,09-06 19:09:56.958  3936  4094 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 19:09:56.960  3936  4094 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:09:56.961  3936  4094 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:09:56.965  3936  4094 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:09:56.968  3936  4094 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:56.968  3936  4094 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:09:56.968  3936  4094 D bt_hci  : do_postload posting postload work item
,09-06 19:09:56.969  3936  4098 I bt_hci  : event_postload
,09-06 19:09:56.969  3936  4098 I bt_vendor: sco_config_cb
,09-06 19:09:56.969  3936  4098 I bt_hci  : sco_config_callback postload finished.
,09-06 19:09:56.973  3936  4094 D bt_bte_conf: Device ID record 1 : primary
09-06 19:09:56.973  3936  4094 D bt_bte_conf:   vendorId            = 000f
,09-06 19:09:56.973  3936  4094 D bt_bte_conf:   vendorIdSource      = 0001
09-06 19:09:56.973  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:56.973  3936  4094 D bt_bte_conf:   product             = 1200
,09-06 19:09:56.974  3936  4098 I bt_vendor: low_power_mode_cb
09-06 19:09:56.974  3936  4094 D bt_bte_conf:   version             = 1436
,09-06 19:09:56.974  3936  4094 D bt_bte_conf:   clientExecutableURL = 
09-06 19:09:56.974  3936  4094 D bt_bte_conf:   serviceDescription  = 
,09-06 19:09:56.974  3936  4094 D bt_bte_conf:   documentationURL    = 
,09-06 19:09:56.975  3936  4094 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:09:56.975  3936  4091 D bt_stack_manager: event_start_up_stack finished
,09-06 19:09:56.976  3936  4090 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 19:09:56.976  3936  4090 D BluetoothAdapterProperties: Setting state to 15
,09-06 19:09:56.977  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-06 19:09:56.977  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:56.979  3936  4090 I BluetoothAdapterState: Entering BleOnState
09-06 19:09:56.983  3936  4090 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 19:09:56.984  3936  4090 D BluetoothAdapterProperties: Setting state to 11
,09-06 19:09:56.984  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 19:09:56.994  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:56.996  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:57.009  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:57.013  3936  3936 D HeadsetService: Received start request. Starting profile...
,09-06 19:09:57.019  3936  3936 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:09:57.020  3936  4090 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:09:57.020  3936  3936 D HeadsetStateMachine: make
,09-06 19:09:57.031  3936  3936 D HeadsetStateMachine: max_hf_connections = 1
,09-06 19:09:57.031  3936  3936 I bt_bluedroid: get_profile_interface handsfree
,09-06 19:09:57.031  3936  4094 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 19:09:57.032  3936  4094 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 19:09:57.037  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:57.037  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:09:57.038  3936  3936 D A2dpService: Received start request. Starting profile...
09-06 19:09:57.038  3936  3936 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:09:57.038  3936  3936 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:09:57.044  3936  3936 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:09:57.045  3936  3936 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:09:57.045  3936  3936 D A2dpStateMachine: make
,09-06 19:09:57.046  3936  3936 I bt_bluedroid: get_profile_interface a2dp
,09-06 19:09:57.047  3936  4094 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:09:57.048  3936  4110 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:09:57.048  3936  3936 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:09:57.049  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
09-06 19:09:57.051  3936  3936 D HidService: Received start request. Starting profile...
09-06 19:09:57.051  3936  3936 I bt_bluedroid: get_profile_interface hidhost
09-06 19:09:57.051  3936  4094 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39883e5
,09-06 19:09:57.051  3936  3936 D HidService: setHidService(): set to: null
09-06 19:09:57.051  3936  4094 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-06 19:09:57.051  3936  3936 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:09:57.052  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:57.053  3936  3936 D HealthService: Received start request. Starting profile...
09-06 19:09:57.051  3856  3856 D BluetoothInputDevice: Proxy object connected
09-06 19:09:57.055  3936  3936 I bt_bluedroid: get_profile_interface health
,09-06 19:09:57.056  3936  3936 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:09:57.057  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:57.058  3936  3936 D PanService: Received start request. Starting profile...
,09-06 19:09:57.058  3936  3936 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-06 19:09:57.059  3936  3936 I bt_bluedroid: get_profile_interface pan
,09-06 19:09:57.060  3936  4094 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:09:57.061  3856  3856 D HidProfile: Bluetooth service connected
,09-06 19:09:57.062  3856  3856 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:57.063  3936  3936 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:09:57.063  3856  3856 D PanProfile: Bluetooth service connected,
09-06 19:09:57.064  3936  3936 D BluetoothMapService: Received start request. Starting profile...
,09-06 19:09:57.064  3936  3936 D BluetoothMapService: start()
,09-06 19:09:57.065  3856  3856 D BluetoothMap: Proxy object connected
,09-06 19:09:57.067  3936  3936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:09:57.067  3856  3856 D MapProfile: Bluetooth service connected
09-06 19:09:57.067  3856  3856 D BluetoothMap: getConnectedDevices()
09-06 19:09:57.068  3936  3936 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-06 19:09:57.068  3936  3936 D BluetoothMapAppObserver: createReceiver()
09-06 19:09:57.069  3856  3856 D BluetoothMap: Bluetooth is Not enabled
,09-06 19:09:57.070  3936  3936 D BluetoothMapAppObserver: initObservers()
09-06 19:09:57.070  3936  3936 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:09:57.078  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:09:57.078  3936  3936 V BluetoothAdapterState: isTurningOn()=true
09-06 19:09:57.078  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false,
09-06 19:09:57.078  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:09:57.081  3936  4108 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 19:09:57.083  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:09:57.084  3936  3936 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:09:57.084  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:57.084  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:57.084  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:09:57.084  3936  3936 V BluetoothAdapterState: isTurningOn()=true
09-06 19:09:57.084  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:57.084  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isTurningOn()=true
09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isTurningOff()=false
09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isTurningOn()=true
09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:57.085  3936  3936 V BluetoothAdapterState: isTurningOff()=false
09-06 19:09:57.086  3936  3936 V BluetoothAdapterState: isTurningOn()=true
09-06 19:09:57.086  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:57.086  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:57.086  3936  4090 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-06 19:09:57.086  3936  4090 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:09:57.086  3936  4090 D BluetoothAdapterProperties: State =  11
09-06 19:09:57.087  3936  4094 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:09:57.087  3936  4094 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:09:57.087  3936  4090 D BluetoothAdapterProperties: Setting state to 12
,09-06 19:09:57.088  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:09:57.089  3856  3868 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:09:57.089  3936  4090 I BluetoothAdapterState: Entering OnState
09-06 19:09:57.090  1363  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:57.092  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:57.094  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:57.096  1363  2038 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:09:57.097  3936  3936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:57.097  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:57.097  3936  3936 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-06 19:09:57.098  1363  1363 D BluetoothMap: Proxy object connected
09-06 19:09:57.098  1363  1372 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:09:57.098  1363  1363 D MapProfile: Bluetooth service connected
09-06 19:09:57.098  1363  1363 D BluetoothMap: getConnectedDevices()
09-06 19:09:57.099  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:57.100  3936  3936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:57.100  3856  3867 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:09:57.101  3856  3868 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:09:57.101  1363  1377 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:09:57.102  3936  3936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:57.103  3936  3936 D ObexServerSockets: Succeed to create listening sockets 
09-06 19:09:57.103  3936  3936 D ObexServerSockets0: startAccept()
09-06 19:09:57.103  3936  3936 D ObexServerSockets0: prepareForNewConnect()
09-06 19:09:57.104  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:57.105  1363  1363 D PanProfile: Bluetooth service connected
,09-06 19:09:57.105  3936  3936 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:09:57.105  3936  3936 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-06 19:09:57.105   870   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:09:57.106   870   870 D BluetoothA2dp: Proxy object connected
,09-06 19:09:57.107  1363  1363 D BluetoothA2dp: Proxy object connected
,09-06 19:09:57.107   870   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:09:57.108  1363  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:09:57.109  3936  4115 D ObexServerSockets0: Accepting socket connection...
09-06 19:09:57.109  3936  4116 D ObexServerSockets0: Accepting socket connection...
09-06 19:09:57.110  1363  1363 D BluetoothInputDevice: Proxy object connected
09-06 19:09:57.110  1363  1363 D HidProfile: Bluetooth service connected
09-06 19:09:57.110   870   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:09:57.110  1363  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:09:57.110   870   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:09:57.111  3856  3867 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 19:09:57.111  1949  1962 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:09:57.112   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:09:57.113  3936  3936 D BluetoothMapService: onReceive
09-06 19:09:57.113  3936  3936 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:57.113  3936  3936 D BluetoothMapService: STATE_ON
,09-06 19:09:57.114  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:57.115  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:57.115  3856  3856 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 19:09:57.120  3856  3856 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 19:09:57.126  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:57.128  3856  3856 D BluetoothA2dp: Proxy object connected
,09-06 19:09:57.130  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:57.134  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:57.137  1363  1363 D BluetoothPbap: Proxy object connected
,09-06 19:09:57.137  1363  1363 D PbapServerProfile: Bluetooth service connected
09-06 19:09:57.138  3856  3856 D BluetoothPbap: Proxy object connected
09-06 19:09:57.138  3936  3936 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:09:57.138  3936  3936 D ObexServerSockets0: prepareForNewConnect()
09-06 19:09:57.138  3856  3856 D PbapServerProfile: Bluetooth service connected
,09-06 19:09:57.146  3936  4121 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:57.157  3936  4125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:57.159  3936  4125 I BtOppRfcommListener: Accept thread started.
,09-06 19:09:57.213   870   870 D BluetoothHeadset: Proxy object connected
09-06 19:09:57.213   870   870 D BluetoothHeadset: Proxy object connected
,09-06 19:09:57.214  1363  1372 D BluetoothHeadset: Proxy object connected
09-06 19:09:57.215  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-06 19:09:57.216   870   870 D BluetoothHeadset: Proxy object connected
,09-06 19:09:57.217  1949  2084 D BluetoothHeadset: Proxy object connected
,09-06 19:09:57.226  3856  3867 D BluetoothHeadset: Proxy object connected
,09-06 19:09:57.231  3856  3856 D HeadsetProfile: Bluetooth service connected
,09-06 19:09:58.642  3936  4090 D BluetoothAdapterState: Current state: ON, message: 23
,09-06 19:09:58.643  3936  4090 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:09:58.643  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-06 19:09:58.645  3936  4090 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 19:09:58.650  3936  4090 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:09:58.659  3936  3936 D BluetoothMapService: onReceive
,09-06 19:09:58.659  3936  3936 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:58.660  3936  3936 D BluetoothMapService: STATE_TURNING_OFF
,09-06 19:09:58.660  3936  3936 D BluetoothMapService: MAP Service closeService in
,09-06 19:09:58.661  3936  3936 D BluetoothMapMasInstance0: MAP Service shutdown
,09-06 19:09:58.661  3936  3936 D ObexServerSockets0: shutdown(block = true)
,09-06 19:09:58.662  3936  4115 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-06 19:09:58.663   870  1310 D ConnectivityService: handlePromptUnvalidated 101
09-06 19:09:58.665  3936  3936 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-06 19:09:58.665  3936  4116 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 19:09:58.668  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:58.668  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:58.670  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:58.670  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:58.672  3936  4104 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 19:09:58.672  3936  3936 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 19:09:58.673  3936  3936 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:58.673  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:58.674  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:58.674  3936  4125 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:09:58.674  3936  4094 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:58.674  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:09:58.674  3784  3784 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:58.674  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:58.675  3936  4090 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 19:09:58.675  3936  4125 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 19:09:58.677  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:58.678  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:58.680  3936  3936 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:09:58.685  3856  3868 D BluetoothHeadset: Proxy object disconnected
,09-06 19:09:58.685   870   870 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:58.685   870   870 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:58.685  1363  1377 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:58.685   870   870 D BluetoothHeadset: Proxy object disconnected
09-06 19:09:58.686  1363  1363 D HeadsetProfile: Bluetooth service disconnected
09-06 19:09:58.686  1949  2388 D BluetoothHeadset: Proxy object disconnected
,09-06 19:09:58.687  3936  3936 D A2dpService: Received stop request...Stopping profile...,
09-06 19:09:58.687  3936  4110 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:09:58.688   870   870 D BluetoothA2dp: Proxy object disconnected
,09-06 19:09:58.688  1363  1363 D BluetoothA2dp: Proxy object disconnected
,09-06 19:09:58.689  3936  3936 D HidService: Received stop request...Stopping profile...
,09-06 19:09:58.690  3936  3936 D HidService: Stopping Bluetooth HidService
,09-06 19:09:58.691  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:58.691  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:58.691  1363  1363 D HidProfile: Bluetooth service disconnected
09-06 19:09:58.691  3936  3936 D HealthService: Received stop request...Stopping profile...
09-06 19:09:58.693  3936  3936 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:58.693  3936  3936 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:58.693  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:58.693  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:09:58.694  3936  3936 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:09:58.694  3936  3936 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:09:58.694  3936  4094 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 19:09:58.695  3936  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:58.695  3936  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:58.695  3936  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:58.695  3936  4094 E bt_btif : btif_hf_upstreams_evt: Invalid index 30574
09-06 19:09:58.695  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:58.696  3856  3856 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:09:58.696  3936  3936 D PanService: Received stop request...Stopping profile...
09-06 19:09:58.697  3856  3856 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:58.697  3856  3856 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:58.697  3856  3856 D HidProfile: Bluetooth service disconnected
09-06 19:09:58.697  3856  3856 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:58.697  3856  3856 D PanProfile: Bluetooth service disconnected
09-06 19:09:58.700  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:58.700  1363  1363 D PanProfile: Bluetooth service disconnected
09-06 19:09:58.701  3936  3936 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:09:58.701  3936  3936 D BluetoothMapService: stop()
09-06 19:09:58.701  3936  3936 D BluetoothMapAppObserver: deinitObservers()
09-06 19:09:58.701  3936  3936 D BluetoothMapAppObserver: removeReceiver()
,09-06 19:09:58.703  1363  1363 D BluetoothMap: Proxy object disconnected
,09-06 19:09:58.703  1363  1363 D MapProfile: Bluetooth service disconnected
09-06 19:09:58.704  3936  3936 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:09:58.704  3856  3856 D BluetoothMap: Proxy object disconnected
09-06 19:09:58.704  3936  3936 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:58.704  3856  3856 D MapProfile: Bluetooth service disconnected
,09-06 19:09:58.704  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:09:58.704  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:58.705  3936  4094 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 19:09:58.705  3936  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:58.705  3936  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 19:09:58.706  3936  4101 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:58.706  3936  4101 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:58.706  3936  4101 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:09:58.706  3936  4101 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-06 19:09:58.706  3856  3856 D BluetoothPbap: Proxy object disconnected
,09-06 19:09:58.706  3856  3856 D PbapServerProfile: Bluetooth service disconnected
09-06 19:09:58.706  1363  1363 D BluetoothPbap: Proxy object disconnected
,09-06 19:09:58.706  1363  1363 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:09:58.706  3936  3936 V BluetoothAdapterState: isTurningOff()=true
,09-06 19:09:58.706  3936  3936 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:58.707  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:09:58.707  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:58.707  3936  3936 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:09:58.707  3936  4094 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 19:09:58.707  3936  3936 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:09:58.708  3936  3936 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:58.708  3936  3936 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:09:58.708  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:58.708  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:58.710  3936  3936 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-06 19:09:58.710  3936  4094 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 19:09:58.710  3936  3936 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:09:58.710  3936  3936 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:58.710  3936  3936 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:09:58.711  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:58.711  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:09:58.711  3936  3936 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:09:58.711  3936  3936 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:09:58.712  3936  3936 D BluetoothMapService: MAP Service closeService in
09-06 19:09:58.712  3936  3936 V BluetoothAdapterState: isTurningOff()=true
09-06 19:09:58.712  3936  3936 V BluetoothAdapterState: isTurningOn()=false
09-06 19:09:58.712  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:09:58.712  3936  3936 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:09:58.712  3936  4090 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 19:09:58.713  3936  4090 D BluetoothAdapterProperties: Setting state to 15
09-06 19:09:58.713  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-06 19:09:58.713  3936  4090 I BluetoothAdapterState: Entering BleOnState
09-06 19:09:58.713  3936  3936 D BluetoothMapService: cleanup()
09-06 19:09:58.713  3936  3936 D BluetoothMapService: MAP Service closeService in
09-06 19:09:58.713  3856  3867 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:09:58.714  1363  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:09:58.715  1363  1372 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:09:58.715  1363  2038 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:09:58.716  3856  3868 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:09:58.716  3856  3867 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:09:58.717  1363  1377 D BluetoothPan: onBluetoothStateChange on: false
09-06 19:09:58.717  3856  3868 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:09:58.717   870   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 19:09:58.718   870   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:58.718  1363  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:09:58.718   870   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:58.718  1363  2038 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:58.718   870   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:58.719  3856  3867 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 19:09:58.719  3856  3868 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:58.720  1949  1965 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 19:09:58.720  3936  4090 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 19:09:58.720  3936  4090 D BluetoothAdapterProperties: Setting state to 16
09-06 19:09:58.720  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 19:09:58.721  3936  4090 D BluetoothAdapterProperties: onBleDisable
09-06 19:09:58.721  3936  4090 I BluetoothAdapterState: Entering PendingCommandState
09-06 19:09:58.721  3936  4091 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 19:09:58.722  3936  4101 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:09:58.722  3936  4101 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 19:09:58.725  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:58.725  3936  4094 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:58.726  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:58.726  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 19:09:58.727  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:58.728  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:58.731  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:58.735  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:58.923  3936  4094 I bt_hci  : shut_down
,09-06 19:09:58.941  3936  4098 I bt_vendor: low_power_mode_cb
,09-06 19:09:58.945  3936  4098 D bt_hwcfg: hw_epilog_process
,09-06 19:09:58.959  3936  4098 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 19:09:58.959  3936  4098 I bt_vendor: epilog_cb
09-06 19:09:58.959  3936  4098 I bt_hci  : epilog_finished_callback
,09-06 19:09:58.967  3936  4094 I bt_hci_h4: hal_close
,09-06 19:09:58.969  3936  4094 I bt_userial_vendor: device fd = 51 close
,09-06 19:09:59.096  3936  4091 D bt_stack_manager: event_shut_down_stack finished.
,09-06 19:09:59.097  3936  4090 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 19:09:59.104  3936  4090 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-06 19:09:59.105  3936  3936 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:09:59.106  3936  3936 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:09:59.107  3936  3936 D BtGatt.GattService: stop()
09-06 19:09:59.107  3936  3936 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 19:09:59.113  3936  3936 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:09:59.113  3936  3936 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:09:59.113  3936  3936 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:09:59.114  3936  3936 V BluetoothAdapterState: isBleTurningOff()=true
,09-06 19:09:59.115  3936  4090 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-06 19:09:59.116  3936  4090 D BluetoothAdapterProperties: Setting state to 10
,09-06 19:09:59.116  3936  4090 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-06 19:09:59.118  3936  4090 I BluetoothAdapterState: Entering OffState
09-06 19:09:59.120   870   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 19:09:59.148  3936  3936 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-06 19:09:59.148  3936  3936 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 19:09:59.148  3936  4091 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 19:09:59.151  3936  4091 D bt_stack_manager: event_clean_up_stack finished.
09-06 19:09:59.151  3936  3936 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:09:59.153  3936  3936 I art     : System.exit called, status: 0
09-06 19:09:59.153  3936  3936 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:09:59.194   870  1376 I ActivityManager: Process com.android.bluetooth (pid 3936) has died
,09-06 19:10:01.640  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:01.640  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:04.648  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:04.649  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6986faf added. We now have 6 listener(s)
09-06 19:10:04.649  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:04.656  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:04.656  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1490fbc added. We now have 7 listener(s)
09-06 19:10:04.657  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:04.658  3784  3835 I System.out: IsBluetoothEnabled
,09-06 19:10:04.670  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:04.716   870   889 I ActivityManager: Start proc 4135:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 19:10:04.842  4135  4135 D AdapterServiceConfig: Adding HeadsetService
,09-06 19:10:04.843  4135  4135 D AdapterServiceConfig: Adding A2dpService
,09-06 19:10:04.843  4135  4135 D AdapterServiceConfig: Adding HidService
,09-06 19:10:04.843  4135  4135 D AdapterServiceConfig: Adding HealthService
,09-06 19:10:04.843  4135  4135 D AdapterServiceConfig: Adding PanService
,09-06 19:10:04.844  4135  4135 D AdapterServiceConfig: Adding GattService
,09-06 19:10:04.844  4135  4135 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 19:10:04.865  4135  4135 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 19:10:04.865   870   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4b487a:true
,09-06 19:10:04.870  4135  4135 I bt_bluedroid: init
,09-06 19:10:04.871  4135  4147 I BluetoothAdapterState: Entering OffState
,09-06 19:10:04.877  4135  4148 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:10:04.878  4135  4148 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:10:04.878  4135  4148 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 19:10:04.878  4135  4148 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:10:04.881  4135  4135 I bt_bluedroid: get_profile_interface socket
,09-06 19:10:04.883  4135  4135 I bt_bluedroid: get_profile_interface sdp
,09-06 19:10:04.889  4135  4146 I bt_bluedroid: config_hci_snoop_log
,09-06 19:10:04.890  4135  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:10:04.892  4135  4151 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 19:10:04.892   870   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 19:10:04.902  4135  4147 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 19:10:04.902  4135  4147 D BluetoothAdapterProperties: Setting state to 14
,09-06 19:10:04.903  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 19:10:04.907  4135  4147 D BluetoothBondStateMachine: make
,09-06 19:10:04.911  4135  4152 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:10:04.918  4135  4147 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:10:04.919  4135  4135 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 19:10:04.924  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:10:04.925  4135  4135 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:10:04.927  4135  4135 D BtGatt.GattService: Received start request. Starting profile...
,09-06 19:10:04.927  4135  4135 D BtGatt.GattService: start()
09-06 19:10:04.927  4135  4135 I bt_bluedroid: get_profile_interface gatt
09-06 19:10:04.928  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
09-06 19:10:04.928  4135  4135 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:10:04.939  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:10:04.939  4135  4135 V BluetoothAdapterState: isTurningOn()=false
,09-06 19:10:04.939  4135  4135 V BluetoothAdapterState: isBleTurningOn()=true
,09-06 19:10:04.939  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:10:04.940  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-06 19:10:04.940  4135  4147 I bt_bluedroid: enable
09-06 19:10:04.941  4135  4148 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 19:10:04.942  4135  4148 I bt_hci  : start_up
,09-06 19:10:04.962  4135  4148 I bt_vendor: alloc value 0xb3a7d189
09-06 19:10:04.963  4135  4148 I bt_vendor: init
09-06 19:10:04.963  4135  4148 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 19:10:04.963  4135  4148 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 19:10:05.072  4135  4148 D bt_hci  : start_up starting async portion
,09-06 19:10:05.073  4135  4155 I bt_hci  : event_finish_startup
,09-06 19:10:05.074  4135  4155 I bt_hci_h4: hal_open
09-06 19:10:05.075  4135  4155 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 19:10:05.090  4135  4155 I bt_userial_vendor: device fd = 51 open
,09-06 19:10:05.114  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:10:05.146  4135  4155 D bt_hwcfg: Chipset BCM4354A2
,09-06 19:10:05.146  4135  4155 D bt_hwcfg: Target name = [BCM4354A2]
,09-06 19:10:05.147  4135  4155 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 19:10:05.821  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 19:10:05.822  4135  4155 D bt_hwcfg: Settlement delay -- 100 ms
,09-06 19:10:05.823  4135  4155 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 19:10:05.940  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 19:10:05.941  4135  4155 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 19:10:05.970  4135  4155 I bt_hwcfg: vendor lib fwcfg completed
,09-06 19:10:05.970  4135  4155 I bt_vendor: firmware callback
,09-06 19:10:05.971  4135  4155 I bt_hci  : firmware_config_callback
,09-06 19:10:05.981  4135  4158 I bt_btu  : btu_task pending for preload complete event
,09-06 19:10:05.982  4135  4158 I bt_btu_task: Bluetooth chip preload is complete
09-06 19:10:05.982  4135  4158 I bt_btu  : btu_task received preload complete event
,09-06 19:10:05.991  4135  4158 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 19:10:05.991  4135  4158 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:10:05.991  4135  4158 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:10:05.991  4135  4158 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:10:05.992  4135  4158 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 19:10:06.122  4135  4158 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fad9d
,09-06 19:10:06.122  4135  4158 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fad9d 
,09-06 19:10:06.136  4135  4151 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 19:10:06.137  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 19:10:06.138  4135  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 19:10:06.141  4135  4151 D BluetoothAdapterProperties: Name is: Nexus 6
09-06 19:10:06.145  4135  4151 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:10:06.145  4135  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:10:06.145  4135  4151 D bt_hci  : do_postload posting postload work item
09-06 19:10:06.147  4135  4155 I bt_hci  : event_postload
09-06 19:10:06.147  4135  4155 I bt_vendor: sco_config_cb
09-06 19:10:06.147  4135  4155 I bt_hci  : sco_config_callback postload finished.
09-06 19:10:06.150  4135  4151 D bt_bte_conf: Device ID record 1 : primary
09-06 19:10:06.150  4135  4151 D bt_bte_conf:   vendorId            = 000f
,09-06 19:10:06.150  4135  4151 D bt_bte_conf:   vendorIdSource      = 0001
,09-06 19:10:06.151  4135  4151 D bt_bte_conf:   product             = 1200
09-06 19:10:06.151  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:06.151  4135  4151 D bt_bte_conf:   version             = 1436
09-06 19:10:06.151  4135  4151 D bt_bte_conf:   clientExecutableURL = 
09-06 19:10:06.151  4135  4151 D bt_bte_conf:   serviceDescription  = 
09-06 19:10:06.151  4135  4151 D bt_bte_conf:   documentationURL    = 
09-06 19:10:06.152  4135  4151 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-06 19:10:06.152  4135  4148 D bt_stack_manager: event_start_up_stack finished
09-06 19:10:06.155  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 19:10:06.155  4135  4147 D BluetoothAdapterProperties: Setting state to 15
09-06 19:10:06.156  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-06 19:10:06.156  4135  4155 I bt_vendor: low_power_mode_cb
09-06 19:10:06.157  4135  4147 I BluetoothAdapterState: Entering BleOnState
,09-06 19:10:06.162  4135  4147 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 19:10:06.162  4135  4147 D BluetoothAdapterProperties: Setting state to 11
,09-06 19:10:06.162  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 19:10:06.172  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:06.180  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
09-06 19:10:06.181  4135  4135 D HeadsetService: Received start request. Starting profile...
,09-06 19:10:06.184  4135  4135 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:10:06.184  4135  4135 D HeadsetStateMachine: make
,09-06 19:10:06.192  4135  4147 I BluetoothAdapterState: Entering PendingCommandState
,09-06 19:10:06.192  4135  4135 D HeadsetStateMachine: max_hf_connections = 1
,09-06 19:10:06.192  4135  4135 I bt_bluedroid: get_profile_interface handsfree
,09-06 19:10:06.192  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 19:10:06.193  4135  4151 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-06 19:10:06.198  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:10:06.198  4135  4135 D A2dpService: Received start request. Starting profile...
09-06 19:10:06.198  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:10:06.199  4135  4135 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:10:06.199  4135  4135 I bt_bluedroid: get_profile_interface avrcp
,09-06 19:10:06.208  4135  4135 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:10:06.208  4135  4135 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:10:06.208  4135  4135 D A2dpStateMachine: make
,09-06 19:10:06.210  4135  4135 I bt_bluedroid: get_profile_interface a2dp
,09-06 19:10:06.211  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 19:10:06.212  4135  4166 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:10:06.212  4135  4135 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 19:10:06.213  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:10:06.214  4135  4135 D HidService: Received start request. Starting profile...
,09-06 19:10:06.214  4135  4135 I bt_bluedroid: get_profile_interface hidhost
09-06 19:10:06.214  4135  4151 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39dc3e5
,09-06 19:10:06.214  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-06 19:10:06.215  4135  4135 D HidService: setHidService(): set to: null
,09-06 19:10:06.215  4135  4135 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:10:06.216  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:10:06.217  4135  4135 D HealthService: Received start request. Starting profile...
,09-06 19:10:06.218  4135  4135 I bt_bluedroid: get_profile_interface health
,09-06 19:10:06.220  4135  4135 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:10:06.221  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:10:06.221  4135  4135 D PanService: Received start request. Starting profile...,
09-06 19:10:06.222  4135  4135 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-06 19:10:06.222  4135  4135 I bt_bluedroid: get_profile_interface pan
,09-06 19:10:06.222  4135  4151 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:10:06.225  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
09-06 19:10:06.225  4135  4135 D BluetoothMapService: Received start request. Starting profile...
09-06 19:10:06.225  4135  4135 D BluetoothMapService: start()
,09-06 19:10:06.228  4135  4135 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 19:10:06.228  4135  4135 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 19:10:06.228  4135  4135 D BluetoothMapAppObserver: createReceiver()
,09-06 19:10:06.229  4135  4135 D BluetoothMapAppObserver: initObservers()
09-06 19:10:06.230  4135  4135 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 19:10:06.237  4135  4164 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 19:10:06.238  4135  4135 V BluetoothAdapterState: isTurningOff()=false
09-06 19:10:06.238  4135  4135 V BluetoothAdapterState: isTurningOn()=true
09-06 19:10:06.238  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:10:06.238  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isTurningOn()=true
,09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isTurningOff()=false
09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isTurningOn()=true
09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 19:10:06.242  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isTurningOff()=false
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isTurningOn()=true
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isTurningOff()=false
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isTurningOn()=true
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:10:06.243  4135  4135 V BluetoothAdapterState: isTurningOff()=false
09-06 19:10:06.244  4135  4135 V BluetoothAdapterState: isTurningOn()=true
09-06 19:10:06.244  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
09-06 19:10:06.244  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
09-06 19:10:06.246  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 19:10:06.246  4135  4147 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:10:06.246  4135  4147 D BluetoothAdapterProperties: State =  11
09-06 19:10:06.247  4135  4151 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:10:06.248  4135  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:10:06.249  4135  4147 D BluetoothAdapterProperties: Setting state to 12
09-06 19:10:06.249  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 19:10:06.249  4135  4147 I BluetoothAdapterState: Entering OnState
09-06 19:10:06.250  3856  3868 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:06.252  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:10:06.253  1363  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:10:06.255  1363  2038 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:10:06.255  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:06.256  1363  1363 D BluetoothA2dp: Proxy object connected
09-06 19:10:06.256  4135  4135 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 19:10:06.257  4135  4135 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-06 19:10:06.257  1363  1372 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:10:06.258  1363  1363 D BluetoothMap: Proxy object connected
09-06 19:10:06.258  1363  1363 D MapProfile: Bluetooth service connected
09-06 19:10:06.258  1363  1363 D BluetoothMap: getConnectedDevices()
09-06 19:10:06.258  3856  3856 D BluetoothMap: Proxy object connected
09-06 19:10:06.258  3856  3856 D MapProfile: Bluetooth service connected
,09-06 19:10:06.258  3856  3856 D BluetoothMap: getConnectedDevices()
09-06 19:10:06.259  4135  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:10:06.260  3856  3868 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:10:06.261  4135  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:10:06.262  3856  3867 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:10:06.262  4135  4135 D ObexServerSockets: Succeed to create listening sockets 
09-06 19:10:06.262  4135  4135 D ObexServerSockets0: startAccept()
09-06 19:10:06.262  4135  4135 D ObexServerSockets0: prepareForNewConnect()
09-06 19:10:06.264  1363  1377 D BluetoothPan: onBluetoothStateChange on: true
09-06 19:10:06.264  4135  4135 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 19:10:06.264  4135  4135 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 19:10:06.265  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:10:06.266  1363  1363 D PanProfile: Bluetooth service connected
09-06 19:10:06.266  3856  3867 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:10:06.266  4135  4173 D ObexServerSockets0: Accepting socket connection...
09-06 19:10:06.266  4135  4174 D ObexServerSockets0: Accepting socket connection...
09-06 19:10:06.267   870   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:10:06.268   870   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:10:06.268   870   870 D BluetoothA2dp: Proxy object connected
09-06 19:10:06.268  3856  3856 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:10:06.268  3856  3856 D PanProfile: Bluetooth service connected
09-06 19:10:06.268  3856  3856 D BluetoothA2dp: Proxy object connected
09-06 19:10:06.268  1363  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:10:06.270   870   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:10:06.271  1363  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:10:06.271  1363  1363 D BluetoothInputDevice: Proxy object connected
,09-06 19:10:06.271  1363  1363 D HidProfile: Bluetooth service connected
09-06 19:10:06.271   870   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:10:06.272  3856  3868 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:10:06.275  3856  4175 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 19:10:06.275  3856  3856 D BluetoothInputDevice: Proxy object connected
09-06 19:10:06.275  3856  3856 D HidProfile: Bluetooth service connected
,09-06 19:10:06.275  1949  1965 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 19:10:06.278   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:10:06.278  4135  4135 D BluetoothMapService: onReceive,
09-06 19:10:06.279  4135  4135 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:10:06.279  4135  4135 D BluetoothMapService: STATE_ON
,09-06 19:10:06.279  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:06.283  3856  3856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:10:06.290  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:10:06.297  1363  1363 D BluetoothPbap: Proxy object connected
,09-06 19:10:06.297  1363  1363 D PbapServerProfile: Bluetooth service connected
,09-06 19:10:06.298  3856  3856 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:10:06.299  3856  3856 D BluetoothPbap: Proxy object connected
,09-06 19:10:06.299  3856  3856 D PbapServerProfile: Bluetooth service connected
,09-06 19:10:06.304  4135  4135 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 19:10:06.304  4135  4135 D ObexServerSockets0: prepareForNewConnect()
,09-06 19:10:06.305  4135  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:10:06.323  4135  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:10:06.325  4135  4184 I BtOppRfcommListener: Accept thread started.
,09-06 19:10:06.370  3856  3868 D BluetoothHeadset: Proxy object connected
,09-06 19:10:06.370   870   870 D BluetoothHeadset: Proxy object connected
09-06 19:10:06.371   870   870 D BluetoothHeadset: Proxy object connected
09-06 19:10:06.371   870   889 D BluetoothHeadset: Proxy object connected
,09-06 19:10:06.371  3856  3856 D HeadsetProfile: Bluetooth service connected
,09-06 19:10:06.371  1363  1377 D BluetoothHeadset: Proxy object connected
,09-06 19:10:06.371  1363  2038 D BluetoothHeadset: Proxy object connected
09-06 19:10:06.371   870   889 D BluetoothHeadset: Proxy object connected
,09-06 19:10:06.371   870   870 D BluetoothHeadset: Proxy object connected
,09-06 19:10:06.372  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-06 19:10:06.372  1949  1962 D BluetoothHeadset: Proxy object connected
09-06 19:10:06.375  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-06 19:10:06.376  3856  4175 D BluetoothHeadset: Proxy object connected
09-06 19:10:06.376  3856  3856 D HeadsetProfile: Bluetooth service connected
09-06 19:10:06.376  1949  2084 D BluetoothHeadset: Proxy object connected
,09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:06.692  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:06.699  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:06.704  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:06.704  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@64f2b45 added. We now have 8 listener(s)
,09-06 19:10:06.705  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:06.712   870  2140 D WifiService: setWifiEnabled: false pid=3784, uid=10000
,09-06 19:10:06.712   870  2140 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:10:06.725  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:06.726   870  2108 D WifiService: setWifiEnabled: true pid=3784, uid=10000
09-06 19:10:06.726   870  2108 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 19:10:06.740   870  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:06.757  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:06.761  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:06.770   870  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-06 19:10:06.771   870  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-06 19:10:06.772   870  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 19:10:06.773   870  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:10:06.774   870  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-06 19:10:06.774   870  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-06 19:10:06.774   870  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 19:10:06.789   373   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 19:10:06.790   870  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.65 rxSuccessRate=0.90 delta 1000 -> 1000,
09-06 19:10:06.791   373   868 D CommandListener: Setting iface cfg
,09-06 19:10:06.791   870  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-06 19:10:06.792   870  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:10:06.795   870  1304 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 19:10:06.795   870  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 19:10:06.801   870  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 19:10:06.801   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:06.818   870  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 19:10:06.886   870  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 19:10:06.888  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 19:10:06.990   870   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
09-06 19:10:06.999  1875  1875 I Keyboard.Facilitator: onFinishInput()
,09-06 19:10:07.010   870   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 19:10:07.010   870   892 I Adreno  : Build Date                       : 10/20/15
09-06 19:10:07.010   870   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 19:10:07.010   870   892 I Adreno  : Local Branch                     : M14
09-06 19:10:07.010   870   892 I Adreno  : Remote Branch                    : 
09-06 19:10:07.010   870   892 I Adreno  : Remote Branch                    : 
09-06 19:10:07.010   870   892 I Adreno  : Reconstruct Branch               : 
,09-06 19:10:07.046   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (198 us)
,09-06 19:10:07.370  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 19:10:07.419  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 19:10:07.421  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 19:10:07.423   870  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:10:07.437   870  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 19:10:07.437   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 19:10:07.438   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:07.455   870  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:07.470   373   868 D CommandListener: Setting iface cfg
,09-06 19:10:07.471   870  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,09-06 19:10:07.489   870  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:10:07.490   870  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-06 19:10:07.493   870  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 19:10:07.515   870  4194 D DhcpClient: Receive thread started
,09-06 19:10:07.598   870  1306 E native  : do suspend false
,09-06 19:10:07.621   870  2082 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 19:10:07.636   870  4194 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-06 19:10:07.639   870  2082 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-06 19:10:07.673  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:10:07.673  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:10:07.710   870  2082 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 19:10:07.711   870   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-06 19:10:07.711  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e1a3a82 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b42a29a, 16908290=android.view.AbsSavedState$1@b42a29a}, android:focusedViewId=100}]}]
,09-06 19:10:07.711  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-06 19:10:07.712  3784  3784 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:10:07.712  3784  3784 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-06 19:10:07.719   870   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-06 19:10:07.722   870  4194 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-06 19:10:07.722   870  2082 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-06 19:10:07.725   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
09-06 19:10:07.725   373   868 D CommandListener: Setting iface cfg
09-06 19:10:07.725   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-06 19:10:07.725   870   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-06 19:10:07.730   870  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 19:10:07.733   870  2082 D DhcpClient: Scheduling renewal in 86399s
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:07.739  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:07.739   870  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 19:10:07.740   870  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-06 19:10:07.743   870  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 19:10:07.743  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:07.745   870  1310 D ConnectivityService: Adding iface wlan0 to network 102
,09-06 19:10:07.746  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 19:10:07.746   870  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 19:10:07.747  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:10:07.748  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e1a3a82 Bundle[{}]
,09-06 19:10:07.749  3784  3835 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 19:10:07.749  3784  3835 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-06 19:10:07.750  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:10:07.751  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:10:07.751  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:10:07.752  3784  3835 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-06 19:10:07.755  3784  3835 I System.out: Running OutgoingSocketThread
,09-06 19:10:07.756  3784  4198 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
09-06 19:10:07.757  3784  4198 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49383
09-06 19:10:07.757  3784  4198 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:10:07.764   870   879 I art     : Background partial concurrent mark sweep GC freed 36572(2MB) AllocSpace objects, 11(360KB) LOS objects, 33% free, 29MB/43MB, paused 4.953ms total 112.456ms
,09-06 19:10:07.773   870  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 19:10:07.774   870  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-06 19:10:07.774   870  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-06 19:10:07.775   870  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-06 19:10:07.776   870  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-06 19:10:07.779   870  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:10:07.782   870  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-06 19:10:07.782   870  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-06 19:10:07.782   870  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-06 19:10:07.782   870  1310 D ConnectivityService:    accepting network in place of null
09-06 19:10:07.782   870  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-06 19:10:07.783   870  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -58]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-06 19:10:07.783   870  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 19:10:07.804   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:10:07.827   373   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 19:10:07.830   870  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-06 19:10:07.830   870  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:07.831   870  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-06 19:10:07.831   870   889 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:07.845  3784  3784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:07.847  3784  3784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:10:07.854  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 19:10:07.867  1721  1721 D SystemUpdateService: onCreate
,09-06 19:10:07.872  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 19:10:07.879  1721  4206 I SystemUpdateService: active receiver: enabled
,09-06 19:10:07.883  1721  4206 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 19:10:07.889  1721  4206 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-06 19:10:07.889  1721  4206 I SystemUpdateService: now status is 0 (complete)
09-06 19:10:07.889  1721  4206 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 19:10:07.890  1721  4206 I SystemUpdateService: file has been verified
09-06 19:10:07.890  1721  4206 I SystemUpdateService: OTA package size = 12249756
,09-06 19:10:07.903  1721  4206 I SystemUpdateService: showing system update notification
,09-06 19:10:07.905  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:10:07.914  1721  4209 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-06 19:10:07.914  1721  4209 W BaseAppContext: Using Auth Proxy for data requests.
,09-06 19:10:07.916  1721  4209 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,09-06 19:10:07.919  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-06 19:10:07.920  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 19:10:07.923  3950  3950 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:07.922  1721  2520 I iu.UploadsManager: num queued entries: 0
09-06 19:10:07.926  1721  2520 I iu.UploadsManager: num updated entries: 0
,09-06 19:10:07.929  3950  3950 D SprintDMHelper: simOperator: 
09-06 19:10:07.929  3950  3950 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 19:10:07.935  1721  2520 I iu.SyncManager: NEXT; no task
,09-06 19:10:07.941  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:10:07.946   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
09-06 19:10:07.946  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 19:10:07.947   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-06 19:10:07.948   870  1331 D SurfaceControl: Excessive delay in setPowerMode(): 225ms
09-06 19:10:07.949   870   892 I DreamManagerService: Entering dreamland.
,09-06 19:10:07.950   870   892 I PowerManagerService: Dozing...
,09-06 19:10:07.950   870   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-06 19:10:07.977  1721  1721 D SystemUpdateService: onDestroy
,09-06 19:10:07.997  1501  2417 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 19:10:07.997  1501  2417 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 19:10:07.997  1501  2417 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 19:10:07.997  1501  2417 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 19:10:08.008  1721  4209 E MDM     : [180] SitrepService.a: Error sending sitrep.
,09-06 19:10:08.016   377  1456 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-06 19:10:08.016   377  1456 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-06 19:10:08.021   870  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:10:08.024  1937  4216 D NfcService: Discovery configuration equal, not updating.
,09-06 19:10:08.030   870  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 19:10:08.032   870  1306 E native  : do suspend false
,09-06 19:10:08.048   870  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-06 19:10:08.060   870  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 19:10:08.062   870  1306 E native  : do suspend true
,09-06 19:10:08.154   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-06 19:10:08.155   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-06 19:10:08.525   870  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,09-06 19:10:08.758  3784  3835 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,09-06 19:10:08.759  3784  3835 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,09-06 19:10:08.771  3784  3835 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,09-06 19:10:08.775  3784  3835 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 19:10:08.775  3784  3835 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,09-06 19:10:08.783  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:08.783  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60657cb added. We now have 2 listener(s)
,09-06 19:10:08.786  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:10:08.786  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:08.786  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:08.786  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:08.786  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1756ba8 added. We now have 9 listener(s)
09-06 19:10:08.786  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:08.787  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:10:08.791  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:08.799  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:08.802  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:10:08.802  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:08.803  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:08.803  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184e66 added. We now have 3 listener(s)
,09-06 19:10:08.804  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:10:08.805  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:08.805  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:08.805  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:08.805  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b20a5a7 added. We now have 10 listener(s)
,09-06 19:10:08.805  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:08.805  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:10:08.805  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:08.805  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:08.806  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:08.806  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.806  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:08.806  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:08.806  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60657cb removed from the list
09-06 19:10:08.806  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:08.806  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1756ba8 removed from the list
09-06 19:10:08.810  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:08.810  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:08.810  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:08.811  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.811  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:08.812  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:08.812  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:08.812  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:08.813  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1756ba8 not in the list
09-06 19:10:08.813  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.813  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:08.813   870  4193 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152105, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-06 19:10:08.816  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:08.816  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:08.816  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:08.816  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b20a5a7 removed from the list
09-06 19:10:08.816  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:08.816  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.816  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:08.816  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:08.816  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184e66 removed from the list
,09-06 19:10:08.817  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:08.817  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5899a54 added. We now have 2 listener(s)
,09-06 19:10:08.818  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:08.819  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:10:08.819  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-06 19:10:08.819  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:08.819  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:08.819  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9947dfd added. We now have 9 listener(s)
09-06 19:10:08.819  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:08.821  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:10:08.825  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:08.830   870  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network,
09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:08.835  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:08.840  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:08.840  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:08.840  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:08.841  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a7f543 added. We now have 3 listener(s)
,09-06 19:10:08.845  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:10:08.845  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:08.845  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:08.845  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:08.846  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:08.846  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1007c0 added. We now have 10 listener(s)
,09-06 19:10:08.847  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:08.847  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:08.848  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:10:08.848  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:08.848  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:08.848  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:08.850  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:08.852  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 19:10:08.853  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:08.858  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:10:08.859  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:10:08.859  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:08.866  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:08.866  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:08.866  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:08.868  3784  3835 D BluetoothAdapter: STATE_ON
,09-06 19:10:08.873  4135  4146 D BtGatt.GattService: registerClient() - UUID=51cbc148-b305-43f2-a1a5-8635de1e42df
,09-06 19:10:08.874  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=51cbc148-b305-43f2-a1a5-8635de1e42df, clientIf=5
,09-06 19:10:08.875  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:10:08.878  4135  4145 D BtGatt.GattService: start scan with filters
,09-06 19:10:08.887  4135  4154 D BtGatt.ScanManager: handling starting scan
,09-06 19:10:08.889  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:10:08.889  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:08.889  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:08.889  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:08.890  4135  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d4ec4f6
,09-06 19:10:08.893  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:08.893  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:08.893  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:08.895  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:08.897  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:10:08.897  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:08.898  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:10:08.899  3784  3835 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:10:08.899  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:08.899  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:10:08.899  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.899  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:10:08.899  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:10:08.899  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:10:08.899  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:08.900  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:10:08.900  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:08.901  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:10:08.902  3784  3835 D BluetoothAdapter: STATE_ON
09-06 19:10:08.903  4135  4146 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:08.906  4135  4145 D BtGatt.GattService: unregisterClient() - clientIf=5,
,09-06 19:10:08.907  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:10:08.907  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:10:08.907  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:08.908  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:10:08.908  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:08.910  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:08.910  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:08.910  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:08.910  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:10:08.912  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:08.913  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:10:08.913  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:08.913  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:08.914  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:08.914  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:08.914  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:10:08.914  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:08.916  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:08.917  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:08.917  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:08.917  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:08.917  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.917  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:08.917  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:08.917  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5899a54 removed from the list
09-06 19:10:08.917  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:08.918  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9947dfd removed from the list
09-06 19:10:08.918  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:08.918  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:08.918  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.918  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:08.920  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:08.921  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:08.921  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:08.921  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9947dfd not in the list
09-06 19:10:08.921  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.921  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:08.923  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:10:08.923  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:08.923  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:08.923  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1007c0 removed from the list
,09-06 19:10:08.923  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:08.923  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:08.923  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:08.923  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-06 19:10:08.924  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a7f543 removed from the list
09-06 19:10:08.925  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:08.925  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cddfec added. We now have 2 listener(s)
09-06 19:10:08.927  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:10:08.928  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-06 19:10:08.928  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:08.928  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:08.928  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96a6fb5 added. We now have 9 listener(s)
,09-06 19:10:08.928  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:08.929  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
09-06 19:10:08.933  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:08.942  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:08.943  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:10:08.943  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:08.945  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:10:08.946  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:08.948  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:08.948  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@240c9bb added. We now have 3 listener(s)
,09-06 19:10:08.950  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:08.951  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 19:10:08.951  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-06 19:10:08.954  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:08.955  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:10:08.955  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-06 19:10:08.955  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:08.955  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:08.955  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4af0ed8 added. We now have 10 listener(s)
,09-06 19:10:08.955  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:08.955  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:10:08.956  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:10:08.956  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:10:08.957  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:10:08.957  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:08.957  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:08.961  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:10:08.961  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:10:08.961  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 19:10:08.961  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:08.962  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:08.968  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:10:08.969  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:10:08.969  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:08.969  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 19:10:08.970  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:10:08.970  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:08.976  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:08.976  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:08.976  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:08.978  3784  3835 D BluetoothAdapter: STATE_ON
,09-06 19:10:08.978  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 19:10:08.978  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:08.982  4135  4145 D BtGatt.GattService: registerClient() - UUID=aa5bb77a-4c79-4a80-b17b-d4c902fc6aea
,09-06 19:10:08.983  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=aa5bb77a-4c79-4a80-b17b-d4c902fc6aea, clientIf=5
,09-06 19:10:08.983  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:10:08.984  4135  4172 D BtGatt.GattService: start scan with filters
,09-06 19:10:08.988  4135  4154 D BtGatt.ScanManager: handling starting scan
09-06 19:10:08.988  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:10:08.988  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:10:08.988  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:08.988  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:08.993  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:08.993  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:08.993  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:08.995  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:08.997  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:10:08.997  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:08.997  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:10:08.998  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:10:08.998  3784  3835 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 19:10:08.999  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:10:08.999  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:08.999  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:08.999  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:08.999  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:08.999  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:08.999  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:08.999  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cddfec removed from the list
,09-06 19:10:08.999  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:08.999  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96a6fb5 removed from the list
09-06 19:10:08.999  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:09.000  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:09.000  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:09.000  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:10:09.000  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:09.000  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:09.001  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:09.001  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:09.001  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:09.002  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96a6fb5 not in the list
09-06 19:10:09.002  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:09.002  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:10:09.002  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:09.002  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:09.002  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:10:09.005  3784  3835 D BluetoothAdapter: STATE_ON
09-06 19:10:09.005  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 19:10:09.005  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:09.005  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:09.006  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:10:09.006  4135  4172 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:09.008  4135  4176 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-06 19:10:09.009  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:10:09.009  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:09.009  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:09.009  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:10:09.009  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:10:09.011  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:09.012  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:09.012  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:09.012  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:10:09.014  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:09.016  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:10:09.016  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:09.016  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:09.016  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:09.017  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:09.017  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:09.017  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4af0ed8 removed from the list
09-06 19:10:09.017  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:09.017  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:09.018  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:09.018  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:09.019  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 19:10:09.019  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:09.019  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@240c9bb removed from the list
,09-06 19:10:09.021  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:09.022  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7724084 added. We now have 2 listener(s)
,09-06 19:10:09.027  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 19:10:09.027  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:09.028  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:10:09.028  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:09.029  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 19:10:09.029  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:09.029  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@565e06d added. We now have 9 listener(s)
,09-06 19:10:09.029  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:09.030  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:09.033  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:09.035  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 19:10:09.035  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-06 19:10:09.035  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:09.039  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:09.041  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:10:09.041  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:09.041  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:09.041  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0b533 added. We now have 3 listener(s)
,09-06 19:10:09.043  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:10:09.043  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:09.043  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 19:10:09.044  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:10:09.044  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:09.044  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:09.044  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:09.044  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e14e0f0 added. We now have 10 listener(s),
,09-06 19:10:09.045  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:09.045  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:09.045  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:10:09.045  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:10:09.045  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:09.045  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:09.045  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:09.048  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:09.049  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 19:10:09.049  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:09.050  3784  3835 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 19:10:09.050  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:09.054  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:10:09.055  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-06 19:10:09.055  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:09.058  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:09.058  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:09.058  3784  3835 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:10:09.059  3784  3835 D BluetoothAdapter: STATE_ON
,09-06 19:10:09.061  4135  4172 D BtGatt.GattService: registerClient() - UUID=95a3f24d-711e-40ed-a5a5-9f6299e49577
,09-06 19:10:09.062  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=95a3f24d-711e-40ed-a5a5-9f6299e49577, clientIf=5
09-06 19:10:09.062  3784  3795 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 19:10:09.062  4135  4176 D BtGatt.GattService: start scan with filters
,09-06 19:10:09.065  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:10:09.065  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:09.065  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:09.065  4135  4154 D BtGatt.ScanManager: handling starting scan
,09-06 19:10:09.065  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:09.068  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:09.068  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:10:09.068  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:09.070  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:09.072  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 19:10:09.073  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:09.073  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 19:10:09.076  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:09.076  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:09.076  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:09.076  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:09.076  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:09.076  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:09.076  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:09.076  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7724084 removed from the list
,09-06 19:10:09.077  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:09.077  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@565e06d removed from the list
09-06 19:10:09.077  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:09.077  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:09.077  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:09.077  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:10:09.077  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:09.078  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:09.079  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:09.079  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:10:09.079  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:09.079  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@565e06d not in the list
09-06 19:10:09.079  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:09.079  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:09.079  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:10:09.080  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 19:10:09.080  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:09.080  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:09.080  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:10:09.080  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 19:10:09.080  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 19:10:09.081  3784  3835 D BluetoothAdapter: STATE_ON
09-06 19:10:09.082  4135  4172 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:09.082  4135  4146 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 19:10:09.083  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:09.083  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:09.083  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:09.083  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 19:10:09.083  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:10:09.084  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:09.084  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:10:09.084  3784  3835 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:09.084  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:10:09.085  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:09.086  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:09.087  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:09.087  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:09.087  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e14e0f0 removed from the list
,09-06 19:10:09.087  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:09.087  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:09.087  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:09.087  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:09.087  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:09.087  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0b533 removed from the list
09-06 19:10:09.087  3784  3784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:09.087  3784  3784 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:09.088  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:09.088  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1c1c added. We now have 2 listener(s)
09-06 19:10:09.090  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 19:10:09.090  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:09.090  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:09.090  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:09.090  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed7b025 added. We now have 9 listener(s)
09-06 19:10:09.090  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:09.091  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:10:09.092  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 19:10:09.092  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:09.094  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:09.098  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 19:10:09.098  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:09.100  3784  3835 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:09.102  3784  3835 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:10:09.102  3784  3835 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:09.103  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:09.103  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb397ab added. We now have 3 listener(s)
,09-06 19:10:09.105  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 19:10:09.105  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:09.105  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:09.105  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:09.105  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cefde08 added. We now have 10 listener(s)
09-06 19:10:09.105  3784  3835 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:09.105  3784  3835 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:09.105  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:09.105  3784  3835 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:09.106  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:09.106  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:09.106  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:09.106  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:09.107  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:09.107  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ff1c1c removed from the list
09-06 19:10:09.107  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:09.107  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed7b025 removed from the list
,09-06 19:10:09.108  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 19:10:09.108  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:09.108  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:10:09.109  3784  3784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:09.109  3784  3835 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:09.109  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:09.109  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:09.110  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:09.111  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:09.111  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:09.111  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:09.111  3784  3835 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed7b025 not in the list
,09-06 19:10:09.111  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:09.111  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:09.112  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:09.112  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:09.112  3784  3835 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:09.112  3784  3835 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cefde08 removed from the list
09-06 19:10:09.112  3784  3835 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:09.112  3784  3835 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:09.112  3784  3835 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:09.112  3784  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:09.112  3784  3835 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb397ab removed from the list
09-06 19:10:09.113  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:10:09.114  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-06 19:10:09.114  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:10:09.114  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:09.114  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:10:09.114  3784  3835 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:09.116  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 19:10:09.116  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 19:10:09.116  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 19:10:09.120  3784  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
,09-06 19:10:09.121  3784  4220 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
09-06 19:10:09.121  3784  4220 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 19:10:09.122  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 19:10:09.122  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 19:10:09.124  3784  4221 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
09-06 19:10:09.124  3784  4221 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
,09-06 19:10:09.124  3784  4221 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:10:09.126  3784  3835 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-06 19:10:09.126  3784  3835 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:10:09.126  3784  3835 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-06 19:10:09.126  3784  3835 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:10:09.126  3784  3835 D com.test.thalitest.ThaliTestRunner: Total duration: 22839 ms
,09-06 19:10:09.128  3784  3835 I jxcore-log: *Native tests were executed*
09-06 19:10:09.128  3784  3835 I jxcore-log: 
,09-06 19:10:09.129  3784  3835 I jxcore-log: Total number of executed tests:  80
09-06 19:10:09.129  3784  3835 I jxcore-log: 
09-06 19:10:09.129  3784  3835 I jxcore-log: Number of passed tests:  80
09-06 19:10:09.129  3784  3835 I jxcore-log: 
,09-06 19:10:09.129  3784  3835 I jxcore-log: Number of failed tests:  0
09-06 19:10:09.129  3784  3835 I jxcore-log: 
09-06 19:10:09.129  3784  3835 I jxcore-log: Number of ignored tests:  0
09-06 19:10:09.129  3784  3835 I jxcore-log: 
,09-06 19:10:09.130  3784  3835 I jxcore-log: Total duration:  22839
09-06 19:10:09.130  3784  3835 I jxcore-log: 
09-06 19:10:09.130  3784  3835 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:10:09.130  3784  3835 I jxcore-log: 
,09-06 19:10:09.133  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.133  3784  3835 I jxcore-log: 
09-06 19:10:09.136  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.136  3784  3835 I jxcore-log: 
09-06 19:10:09.137  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.137  3784  3835 I jxcore-log: 
09-06 19:10:09.139  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.139  3784  3835 I jxcore-log: 
09-06 19:10:09.140  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.140  3784  3835 I jxcore-log: 
09-06 19:10:09.141  3784  3784 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 19:10:09.141  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.141  3784  3835 I jxcore-log: 
09-06 19:10:09.144  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.144  3784  3835 I jxcore-log: 
09-06 19:10:09.146  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.146  3784  3835 I jxcore-log: 
,09-06 19:10:09.147  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.147  3784  3835 I jxcore-log: 
,09-06 19:10:09.148  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:09.148  3784  3835 I jxcore-log: 
,09-06 19:10:09.149  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:09.149  3784  3835 I jxcore-log: 
09-06 19:10:09.149  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:09.149  3784  3835 I jxcore-log: 
,09-06 19:10:09.150  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.150  3784  3835 I jxcore-log: 
09-06 19:10:09.150  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.150  3784  3835 I jxcore-log: 
,09-06 19:10:09.151  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.151  3784  3835 I jxcore-log: 
09-06 19:10:09.151  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.151  3784  3835 I jxcore-log: 
,09-06 19:10:09.152  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.152  3784  3835 I jxcore-log: 
09-06 19:10:09.152  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.152  3784  3835 I jxcore-log: 
,09-06 19:10:09.153  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.153  3784  3835 I jxcore-log: 
09-06 19:10:09.153  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.153  3784  3835 I jxcore-log: 
,09-06 19:10:09.154  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.154  3784  3835 I jxcore-log: 
09-06 19:10:09.154  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:09.154  3784  3835 I jxcore-log: 
,09-06 19:10:09.155  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:09.155  3784  3835 I jxcore-log: 
09-06 19:10:09.155  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:09.155  3784  3835 I jxcore-log: 
,09-06 19:10:09.156  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.156  3784  3835 I jxcore-log: 
,09-06 19:10:09.157  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.157  3784  3835 I jxcore-log: 
09-06 19:10:09.157  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.157  3784  3835 I jxcore-log: 
09-06 19:10:09.157  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.157  3784  3835 I jxcore-log: 
,09-06 19:10:09.158  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.158  3784  3835 I jxcore-log: 
09-06 19:10:09.158  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:09.158  3784  3835 I jxcore-log: 
,09-06 19:10:09.416  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:10:09.419  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:09.419  3784  3835 I jxcore-log: 
,09-06 19:10:09.517  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:10:09.520  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:09.520  3784  3835 I jxcore-log: 
,09-06 19:10:09.588  3784  3784 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:10:09.591  3784  3835 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:09.591  3784  3835 I jxcore-log: 
,09-06 19:10:09.789  4222  4222 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-06 19:10:09.794  4222  4222 D AndroidRuntime: CheckJNI is OFF
,09-06 19:10:09.837  4222  4222 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-06 19:10:09.885  4222  4222 I Radio-JNI: register_android_hardware_Radio DONE
,09-06 19:10:09.908  4222  4222 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:10:09.921   870   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-06 19:10:09.922   870   885 I ActivityManager: Killing 3784:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-06 19:10:10.045   870   895 W PackageSettings: Skipping PackageSetting{be566ab com.example.hello/10273} due to missing metadata
,09-06 19:10:10.059   870  1954 I WindowState: WIN DEATH: Window{711c04 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:10:10.059   870  1963 D GraphicsStats: Buffer count: 2
,09-06 19:10:10.063   870  1308 D WifiService: Client connection lost with reason: 4
,09-06 19:10:10.089   870   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-06 19:10:10.089   870   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-06 19:10:10.091   870   885 E ActivityManager: Failure starting process com.test.thalitest
09-06 19:10:10.091   870   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-06 19:10:10.091   870   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.091   870   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.091   870   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:10:10.091   870   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-06 19:10:10.092   870   885 I ActivityManager:   Force finishing activity ActivityRecord{24f6855 u0 com.test.thalitest/.MainActivity t2}
,09-06 19:10:10.096   870  2138 W ActivityManager: Spurious death for ProcessRecord{ed7b025 0:com.test.thalitest/u0a0}, curProc for 3784: null
,09-06 19:10:10.098   870   895 I art     : Starting a blocking GC Explicit
,09-06 19:10:10.146   870   895 I art     : Explicit concurrent mark sweep GC freed 31172(1911KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 685us total 46.630ms
,09-06 19:10:10.176   870   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-06 19:10:10.182  4222  4222 I art     : System.exit called, status: 0
,09-06 19:10:10.183  4222  4222 I AndroidRuntime: VM exiting with result code 0.
,09-06 19:10:10.190   870   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-06 19:10:10.216   870   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-06 19:10:10.221  4135  4135 D BluetoothMapAppObserver: onReceive
09-06 19:10:10.222  4135  4135 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-06 19:10:10.223  1909  2295 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:10:10.225   870  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:10:10.237  3626  3626 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-06 19:10:10.241  1875  1875 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-06 19:10:10.249  1875  4236 I Keyboard.Facilitator.DecoderInitializer: run()
,09-06 19:10:10.256  1949  1949 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-06 19:10:10.262  1875  4236 I Decoder : createOrResetDecoder
,09-06 19:10:10.293   870  1954 I ActivityManager: Start proc 4237:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-06 19:10:10.297  1501  1501 I ConfigService: onCreate
,09-06 19:10:10.316   870   870 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:10:10.325  1875  4236 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-06 19:10:10.348   870  1332 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,09-06 19:10:10.348   870  1332 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-06 19:10:10.348   870  1332 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-06 19:10:10.348   870  1332 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
,09-06 19:10:10.349   870  1332 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
09-06 19:10:10.349   870  1332 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
09-06 19:10:10.349   870  1332 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
,09-06 19:10:10.349   870  1332 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
09-06 19:10:10.349   870  1332 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
09-06 19:10:10.349   870  1332 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-06 19:10:10.349   870  1332 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,09-06 19:10:10.349   870  1332 W System.err: 	... 4 more
09-06 19:10:10.349   870  1332 D skia    : ------- write threw an exception
,09-06 19:10:10.360   870  1879 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3784 uid 10000
,09-06 19:10:10.361  1875  1875 I Keyboard.Facilitator: onFinishInput()
,09-06 19:10:10.364  4237  4237 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-06 19:10:10.367  1966  2041 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-06 19:10:10.368   870   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-06 19:10:10.369   870   884 E PackageManager: Failed to write settings, restoring backup
09-06 19:10:10.369   870   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-06 19:10:10.369   870   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-06 19:10:10.369   870   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-06 19:10:10.369   870   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-06 19:10:10.369   870   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-06 19:10:10.369   870   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.369   870   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.369   870   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:10:10.372   870   885 E DropBoxManagerService: Can't write: system_server_wtf
09-06 19:10:10.372   870   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-06 19:10:10.372   870   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:10:10.372   870   885 E DropBoxManagerService: 	... 13 more
,09-06 19:10:10.374  1875  4236 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-06 19:10:10.376  1875  4236 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-06 19:10:10.376  1875  4236 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-06 19:10:10.378  1875  4236 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict,
09-06 19:10:10.378  1875  4236 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-06 19:10:10.379  1875  4236 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict,
09-06 19:10:10.379  1875  4236 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-06 19:10:10.381   870  2138 I ActivityManager: Start proc 4251:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-06 19:10:10.381  1966  2041 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-06 19:10:10.381  1966  2041 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1966
09-06 19:10:10.381  1966  2041 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.381  1966  2041 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:10:10.381  1875  4236 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-06 19:10:10.382  1875  4236 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-06 19:10:10.383   870  4257 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:10:10.383   870  4257 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:10:10.383   870  4257 E DropBoxManagerService: 	... 5 more
09-06 19:10:10.383   870   881 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-06 19:10:10.388  1966  2041 I Process : Sending signal. PID: 1966 SIG: 9
,09-06 19:10:10.399  1875  4236 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-06 19:10:10.402  1875  4236 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-06 19:10:10.402  1875  4236 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-06 19:10:10.402  1875  4236 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-06 19:10:10.427   870  1602 D GraphicsStats: Buffer count: 1
,09-06 19:10:10.427   870   881 I WindowState: WIN DEATH: Window{1078518 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-06 19:10:10.438   870  2141 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1966) has died
,09-06 19:10:10.439   870  2141 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-06 19:10:10.440   870  2141 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 19:10:10.454   870   885 I ActivityManager: Start proc 4268:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:10:10.497  4268  4268 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:10:10.497  4268  4268 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:10:10.498  4268  4268 D AndroidRuntime: Shutting down VM
,09-06 19:10:10.504  4268  4268 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:10:10.504  4268  4268 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4268
09-06 19:10:10.504  4268  4268 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:10:10.504  4268  4268 E AndroidRuntime: 	... 10 more
09-06 19:10:10.505   870  2136 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-06 19:10:10.505  4237  4237 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-06 19:10:10.506  4268  4268 I Process : Sending signal. PID: 4268 SIG: 9
,09-06 19:10:10.510   870  4281 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:10:10.510   870  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:10:10.510   870  4281 E DropBoxManagerService: 	... 5 more
,09-06 19:10:10.548   870  2136 I ActivityManager: Start proc 4285:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-06 19:10:10.549   870  2128 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4268) has died
,09-06 19:10:10.550   870  2128 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 19:10:10.564   870   885 I ActivityManager: Start proc 4296:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:10:10.595  4237  4283 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 19:10:10.613  4285  4285 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-06 19:10:10.615  4296  4296 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:10:10.615  4296  4296 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 19:10:10.615  4296  4296 D AndroidRuntime: Shutting down VM
,09-06 19:10:10.622  1721  4282 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-06 19:10:10.622  1721  4282 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-06 19:10:10.626  4296  4296 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:10:10.626  4296  4296 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4296
09-06 19:10:10.626  4296  4296 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-06 19:10:10.626  4296  4296 E AndroidRuntime: 	... 10 more
09-06 19:10:10.627   870  2108 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-06 19:10:10.628  4296  4296 I Process : Sending signal. PID: 4296 SIG: 9
,09-06 19:10:10.629  1721  4282 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-06 19:10:10.629  1721  4282 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-06 19:10:10.629   870  4309 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:10:10.629   870  4309 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:10:10.629   870  4309 E DropBoxManagerService: 	... 5 more
,09-06 19:10:10.634   870  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 16 -> obsolete
,09-06 19:10:10.640  1721  4282 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-06 19:10:10.641  1721  4282 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-06 19:10:10.654  4237  4265 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.654  4237  4265 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.654  4237  4265 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:10:10.654  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-06 19:10:10.655  1501  1501 D AndroidRuntime: Shutting down VM
09-06 19:10:10.656  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
09-06 19:10:10.656  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
09-06 19:10:10.656  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-06 19:10:10.656  1501  1501 E AndroidRuntime: 	... 8 more
,09-06 19:10:10.659   870  4313 E DropBoxManagerService: Can't write: system_app_crash
09-06 19:10:10.659   870  4313 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 19:10:10.659   870  4313 E DropBoxManagerService: 	... 5 more
,09-06 19:10:10.660  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
,09-06 19:10:10.661   870  2139 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4296) has died
09-06 19:10:10.662   870  2139 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-06 19:10:10.675   870   885 I ActivityManager: Start proc 4314:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-06 19:10:10.695   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
