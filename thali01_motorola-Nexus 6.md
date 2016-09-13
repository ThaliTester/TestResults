#### Test 846487404bc066c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-13 11:56:45.154  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:56:45.166  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 11:56:45.171  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 11:56:45.218  1550  2428 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 11:56:45.218  1550  2428 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 11:56:45.218  1550  2428 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:56:45.219  1550  2428 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 11:56:45.260  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 11:56:45.260  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 11:56:45.261  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
09-13 11:56:45.804  3797  3797 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 11:56:45.809  3797  3797 D AndroidRuntime: CheckJNI is OFF
09-13 11:56:45.851  3797  3797 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 11:56:45.901  3797  3797 I Radio-JNI: register_android_hardware_Radio DONE
09-13 11:56:45.924  3797  3797 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 11:56:45.928   874   885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 11:56:45.972  2017  2031 W SearchService: Abort, client detached.
09-13 11:56:45.986  3797  3797 D AndroidRuntime: Shutting down VM
09-13 11:56:45.989  2017  2349 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@da3d2d0
09-13 11:56:45.990  2017  2360 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 11:56:45.990  2017  2017 I HotwordDetector: Closing mic
09-13 11:56:46.010   874  2032 I ActivityManager: Start proc 3806:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 11:56:46.054   377  2362 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 11:56:46.056   377  2362 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 11:56:46.061   377  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 11:56:46.064  2017  2355 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 11:56:46.064  2017  2359 I MicroRecognitionRnrImpl: Detection finished
09-13 11:56:46.095  3806  3806 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 11:56:46.116  3806  3806 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 11:56:46.128  3806  3806 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 4510-4519)
09-13 11:56:46.129  3806  3806 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:56:46.145  3806  3806 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5d4ba3}
09-13 11:56:46.145  3806  3806 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 11:56:46.146  3806  3806 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 11:56:46.155  3806  3806 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 11:56:46.156  3806  3806 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 11:56:46.175  3806  3806 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 11:56:46.184  3806  3806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 11:56:46.184  3806  3806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 11:56:46.184  3806  3806 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 11:56:46.184  3806  3806 I Adreno  : Build Date                       : 10/20/15
09-13 11:56:46.184  3806  3806 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 11:56:46.184  3806  3806 I Adreno  : Local Branch                     : M14
09-13 11:56:46.184  3806  3806 I Adreno  : Remote Branch                    : 
09-13 11:56:46.184  3806  3806 I Adreno  : Remote Branch                    : 
09-13 11:56:46.184  3806  3806 I Adreno  : Reconstruct Branch               : 
,09-13 11:56:46.254   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30f072f:true
,09-13 11:56:46.304  3806  3806 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 11:56:46.317  3806  3806 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 11:56:46.391  3806  3845 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 11:56:46.398  3806  3831 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 11:56:46.415  3806  3845 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 11:56:46.483   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +491ms
,09-13 11:56:46.494  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-13 11:56:46.624  3806  3806 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3806
,09-13 11:56:46.757  3806  3806 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 11:56:46.828   874  2034 I ActivityManager: Killing 2974:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-13 11:56:46.829   279   279 E lowmemorykiller: Error writing /proc/2974/oom_score_adj; errno=22
,09-13 11:56:46.933   874  2034 I ActivityManager: Killing 3216:com.google.android.gm/u0a78 (adj 15): empty #18
,09-13 11:56:47.019  3806  3847 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1703151312
,09-13 11:56:47.026  3806  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 11:56:47.026  3806  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 11:56:47.026  3806  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 11:56:47.026  3806  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 11:56:47.026  3806  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 11:56:47.026  3806  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@248cab7 added. We now have 1 listener(s)
,09-13 11:56:47.029  3806  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 11:56:47.031  3806  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:56:47.031  3806  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:56:47.031  3806  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 11:56:47.034  3806  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b4df42 added. We now have 1 listener(s)
,09-13 11:56:47.034  3806  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:56:47.037  3806  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:56:47.037  3806  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 11:56:47.037  3806  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 11:56:47.038  3806  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 11:56:47.038  3806  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 11:56:47.038   874  1317 D WifiService: New client listening to asynchronous messages
09-13 11:56:47.040  3806  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:56:47.040  3806  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 11:56:47.044  3806  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:47.045  3806  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:56:47.045  3806  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 11:56:47.045  3806  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:56:47.045  3806  3847 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 11:56:47.104  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:56:47.106  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:47.108  3806  3806 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 11:56:48.297  3806  3857 E filemap : mmap(20557824,0) failed: Invalid argument
,09-13 11:56:48.297  3806  3857 W asset   : create map from entry failed
09-13 11:56:48.298  3806  3857 W jxcore-FileManager: aproxFileSize failed
,09-13 11:56:48.298  3806  3857 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/write-stream/Makefile
09-13 11:56:48.299  3806  3857 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
09-13 11:56:48.299  3806  3857 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
,09-13 11:56:48.299  3806  3857 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
09-13 11:56:48.299  3806  3857 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
09-13 11:56:48.299  3806  3857 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
,09-13 11:56:48.299  3806  3857 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
09-13 11:56:48.299  3806  3857 W System.err: ,	at android.os.Handler.handleCallback(Handler.java:739)
09-13 11:56:48.299  3806  3857 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 11:56:48.299  3806  3857 W System.err: 	at android.os.Looper.loop(Looper.java:148)
,09-13 11:56:48.299  3806  3857 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,09-13 11:56:48.313  3806  3857 W jxcore-log: Initializing JXcore engine
,09-13 11:56:48.313  3806  3857 W jxcore-log: JXcore engine is ready
,09-13 11:56:48.348  3857  3857 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 11:56:48.348  3857  3857 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11595]" dev="sockfs" ino=11595 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 11:56:48.348  3857  3857 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 11:56:48.348  3857  3857 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25769]" dev="sockfs" ino=25769 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 11:56:48.358  3806  3857 W jxcore-log: Starting JXcore engine
,09-13 11:56:48.437  3806  3857 W jxcore-log: Platform android
09-13 11:56:48.437  3806  3857 W jxcore-log: 
09-13 11:56:48.437  3806  3857 W jxcore-log: Process ARCH arm
09-13 11:56:48.437  3806  3857 W jxcore-log: 
,09-13 11:56:48.625  3806  3857 I jxcore-log: JXcore Cordova bridge is ready!
09-13 11:56:48.625  3806  3857 I jxcore-log: 
09-13 11:56:48.625  3806  3857 W jxcore-log: JXcore engine is started
,09-13 11:56:48.636  3806  3847 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 11:56:48.642  3806  3806 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 11:56:54.127   874  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 11:56:55.553   874  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 11:56:56.136   874   883 I art     : Background partial concurrent mark sweep GC freed 51106(3MB) AllocSpace objects, 14(320KB) LOS objects, 33% free, 29MB/44MB, paused 1.623ms total 102.003ms
,09-13 11:56:58.442  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 11:56:58.442  3806  3857 I jxcore-log: 
,09-13 11:56:58.445  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 11:56:58.445  3806  3857 I jxcore-log: 
,09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:58.449  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:56:58.451  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:56:58.453  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 11:56:58.453  3806  3857 I jxcore-log: 
,09-13 11:56:58.455  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 11:56:58.455  3806  3857 I jxcore-log: 
,09-13 11:56:58.947  3806  3857 D executeNativeTests: Running unit tests
,09-13 11:56:59.005  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:56:59.005  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d added. We now have 2 listener(s)
09-13 11:56:59.006  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:56:59.006  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:56:59.006  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:56:59.006  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:56:59.006  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 added. We now have 2 listener(s)
09-13 11:56:59.006  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:56:59.007  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:56:59.010  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:59.013  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:56:59.014  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:56:59.014  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:56:59.019  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.024  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 11:56:59.026  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 11:56:59.027  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-13 11:56:59.027  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:56:59.030  3806  3857 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 11:56:59.031  3806  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 11:56:59.031  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 11:56:59.031  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:56:59.031  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:56:59.033  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.034  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:56:59.034  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.034  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.034  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.034  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:56:59.034  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:56:59.034  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d removed from the list
09-13 11:56:59.035  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.035  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 removed from the list
09-13 11:56:59.035  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.035  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.036  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.036  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.036  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.036  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.037  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.037  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.038  3806  3857 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 11:56:59.039  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.039  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.039  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:56:59.039  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.039  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.039  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.039  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.039  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.039  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.039  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.039  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.039  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 1,1:56:59.039  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.040  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.040  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.040  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.040  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.040  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 11:56:59.046  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOu,tgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 11:56:59.047  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 11:56:59.047  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.047  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.047  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:56:59.048  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.048  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.048  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.048  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.048  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.048  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.048  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.048  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.048  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.048  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.048  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.050  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.050  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.050  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.050  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.050  3806  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 11:56:59.054  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:59.056  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:56:59.059  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.059  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:56:59.060  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 11:56:59.060  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:56:59.060  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-13 11:56:59.060  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:56:59.060  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:56:59.061  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:56:59.065  3806  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 11:56:59.065  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 11:56:59.065  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:56:59.069  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:56:59.071  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 11:56:59.072  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:56:59.073  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 11:56:59.076  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-13 11:56:59.076  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 11:56:59.076  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:56:59.077  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:56:59.078  3806  3857 D BluetoothAdapter: STATE_ON
,09-13 11:56:59.082  2666  2679 D BtGatt.GattService: registerClient() - UUID=1d691c6b-0436-473d-a372-078286be2c44
,09-13 11:56:59.084  2666  2698 D BtGatt.GattService: onClientRegistered() - UUID=1d691c6b-0436-473d-a372-078286be2c44, clientIf=5
,09-13 11:56:59.085  3806  3853 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 11:56:59.086  2666  2811 D BtGatt.GattService: start scan with filters
,09-13 11:56:59.089  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 11:56:59.089  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 11:56:59.089  2666  2701 D BtGatt.ScanManager: handling starting scan
09-13 11:56:59.090  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 11:56:59.090  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 11:56:59.092  2666  2701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:56:59.092  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:56:59.093  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:56:59.093  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:56:59.094  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:56:59.097  3806  3857 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 11:56:59.100  2666  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 11:56:59.101  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.101  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.101  3806  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 11:56:59.101  2666  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 11:56:59.101  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.101  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 11:56:59.102  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.102  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:56:59.102  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:56:59.102  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:56:59.102  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 11:56:59.102  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 11:56:59.104  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:56:59.104  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 11:56:59.106  3806  3857 D BluetoothAdapter: STATE_ON
09-13 11:56:59.107  2666  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:56:59.107  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.107  2666  2679 D BtGatt.GattService: stopScan() - queue size =1
09-13 11:56:59.107  2666  2701 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:56:59.107  2666  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:56:59.109  2666  2811 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 11:56:59.110  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:56:59.110  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:56:59.110  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 11:56:59.110  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:56:59.110  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 11:56:59.112  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 11:56:59.114  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 11:56:59.114  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:56:59.114  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:56:59.115  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 11:56:59.115  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:56:59.115  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.115  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:56:59.115  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.115  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.115  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.116  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.116  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.116  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.116  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:56:59.116  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.116  3806  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 11:56:59.117  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:59.123  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:56:59.124  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:56:59.124  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:56:59.126  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:56:59.126  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:56:59.126  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:56:59.126  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 11:56:59.127  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.126  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:56:59.127  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 11:56:59.129  2666  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 11:56:59.129  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.130  3806  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 11:56:59.130  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:56:59.132  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:56:59.133  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 11:56:59.133  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:56:59.135  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:56:59.135  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:56:59.135  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:56:59.135  3806  3857 D BluetoothAdapter: STATE_ON
,09-13 11:56:59.136  2666  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 11:56:59.136  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.137  2666  2677 D BtGatt.GattService: registerClient() - UUID=b56d047d-b261-4bb2-b176-2fb32338cb07
09-13 11:56:59.137  2666  2698 D BtGatt.GattService: onClientRegistered() - UUID=b56d047d-b261-4bb2-b176-2fb32338cb07, clientIf=5
,09-13 11:56:59.138  3806  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 11:56:59.138  2666  2811 D BtGatt.GattService: start scan with filters
,09-13 11:56:59.140  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 11:56:59.140  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 11:56:59.140  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 11:56:59.140  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 11:56:59.142  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:56:59.142  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:56:59.142  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 11:56:59.143  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:56:59.147  3806  3857 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 11:56:59.148  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.148  3806  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 11:56:59.148  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.148  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 11:56:59.148  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.148  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:56:59.148  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:56:59.148  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:56:59.148  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:56:59.149  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:56:59.149  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:56:59.149  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 11:56:59.151  3806  3857 D BluetoothAdapter: STATE_ON
09-13 11:56:59.151  2666  2677 D BtGatt.GattService: stopScan() - queue size =0
09-13 11:56:59.151  2666  2811 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 11:56:59.151  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:56:59.151  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:56:59.152  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:56:59.152  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:56:59.152  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 11:56:59.152  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:56:59.152  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 11:56:59.152  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:56:59.153  2666  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 11:56:59.153  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.153  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:56:59.153  2666  2701 D BtGatt.ScanManager: stopping BLe Batch
09-13 11:56:59.153  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:56:59.154  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.154  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.154  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 11:56:59.154  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.154  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.154  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:56:59.154  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
,09-13 11:56:59.155  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.155  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.155  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.155  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.156  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.156  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.163  2666  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 11:56:59.163  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.163  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:56:59.166  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:56:59.166  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.166  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.166  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.167  3806  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 11:56:59.169  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:56:59.172  2666  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 11:56:59.172  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:59.173  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:56:59.174  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.174  2666  2701 D BtGatt.ScanManager: handling starting scan
09-13 11:56:59.174  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:56:59.174  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:56:59.174  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:56:59.174  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 11:56:59.175  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:56:59.175  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:56:59.176  3806  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 11:56:59.177  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 11:56:59.177  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:56:59.181  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:56:59.183  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:56:59.185  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 11:56:59.185  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:56:59.186  2666  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 11:56:59.187  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.187  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:56:59.187  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:56:59.187  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:56:59.187  2666  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 11:56:59.188  3806  3857 D BluetoothAdapter: STATE_ON
,09-13 11:56:59.192  2666  2679 D BtGatt.GattService: registerClient() - UUID=14b38e3e-c5be-4f3d-96eb-c28fa8bc5977
,09-13 11:56:59.193  2666  2698 D BtGatt.GattService: onClientRegistered() - UUID=14b38e3e-c5be-4f3d-96eb-c28fa8bc5977, clientIf=5
,09-13 11:56:59.193  3806  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 11:56:59.194  2666  2819 D BtGatt.GattService: start scan with filters
09-13 11:56:59.195  2666  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:56:59.195  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.195  2666  2701 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 11:56:59.195  2666  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:56:59.204  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 11:56:59.204  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 11:56:59.204  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 11:56:59.204  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 11:56:59.206  2666  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 11:56:59.206  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.208  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:56:59.208  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:56:59.208  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:56:59.210  2666  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 11:56:59.210  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.211  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:56:59.214  3806  3857 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 11:56:59.214  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.214  3806  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 11:56:59.214  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
09-13 11:56:59.214  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 11:56:59.214  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.214  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:56:59.215  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 11:56:59.215  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:56:59.215  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 11:56:59.215  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 11:56:59.215  2666  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 11:56:59.215  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.215  2666  2701 D BtGatt.ScanManager: stopping BLe Batch
09-13 11:56:59.215  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:56:59.216  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-13 11:56:59.217  3806  3857 D BluetoothAdapter: STATE_ON
09-13 11:56:59.218  2666  2677 D BtGatt.GattService: stopScan() - queue size =0
09-13 11:56:59.218  2666  2679 D BtGatt.GattService: unregisterClient() - clientIf=5,
09-13 11:56:59.219  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:56:59.219  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:56:59.219  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:56:59.219  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:56:59.220  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 11:56:59.221  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:56:59.221  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 11:56:59.221  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:56:59.221  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:56:59.221  2666  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 11:56:59.221  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:56:59.221  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.222  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 11:56:59.222  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.222  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.223  3806  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 11:56:59.223  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:56:59.223  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:56:59.223  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.223  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.223  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:56:59.223  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.223  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.223  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.223  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.223  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.223  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.224  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:56:59.224  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.224  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.225  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.225  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.225  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.225  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.225  3806  3857 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 11:56:59.226  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.226  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.226  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.226  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.226  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.226  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 11:56:59.226  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.226  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 11:56:59.226  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.226  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:56:59.226  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.226  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 11:56:59.226  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.226  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 11:56:59.227  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.227  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:56:59.227  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.227  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.228  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 11:56:59.228  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 11:56:59.228  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.228  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-13 11:56:59.228  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.228  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.228  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.228  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
,09-13 11:56:59.228  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.228  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.228  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 11:56:59.228  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.228  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.229  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.229  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 11:56:59.229  2666  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 11:56:59.229  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.229  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:56:59.229  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.229  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.229  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.230  3806  3857 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-13 11:56:59.231  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.231  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.231  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.231  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.231  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.231  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.231  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.231  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.231  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.231  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:56:59.231  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.231  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.231  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.232  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.236  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.236  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:56:59.236  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.236  2666  2701 D BtGatt.ScanManager: handling starting scan
09-13 11:56:59.239  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list,
09-13 11:56:59.243  3806  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 11:56:59.243  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.243  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.243  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.243  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.243  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.243  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.245  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list,
09-13 11:56:59.245  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.245  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.245  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.245  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 11:56:59.245  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.245  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.245  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.247  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:56:59.247  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:56:59.247  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.247  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.247  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 11:56:59.247  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 11:56:59.248  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 11:56:59.248  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 11:56:59.248  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 11:56:59.248  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 11:56:59.248  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.248  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:56:59.248  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.248  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.248  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.248  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.248  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
,09-13 11:56:59.249  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.248  2666  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
09-13 11:56:59.250  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.250  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:56:59.250  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.251  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.251  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.251  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.250  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.252  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:56:59.252  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.252  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.252  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.252  3806  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:56:59.252  2666  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 11:56:59.253  3806  3857 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 11:56:59.253  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 11:56:59.255  3806  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:56:59.255  3806  3857 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 11:56:59.255  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 11:56:59.256  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
09-13 11:56:59.256  3806  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 11:56:59.257  3806  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 11:56:59.257  3806  3857 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 11:56:59.258  3806  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 11:56:59.258  3806  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 11:56:59.258  3806  3857 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
09-13 11:56:59.258  3806  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:56:59.258  3806  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 11:56:59.258  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-13 11:56:59.264  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 11:56:59.264  2666  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:56:59.264  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.264  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 11:56:59.264  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 11:56:59.264  2666  2701 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:56:59.265  2666  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:56:59.265  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 11:56:59.265  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 11:56:59.266  3806  3857 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-13 11:56:59.266  3806  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 11:56:59.266  3806  3857 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 11:56:59.266  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.266  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.266  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:56:59.267  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.267  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.267  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.267  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 11:56:59.267  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
,09-13 11:56:59.267  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.267  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.267  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.267  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.267  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.268  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.268  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.269  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.269  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.269  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.269  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.270  3806  3857 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-13 11:56:59.270  3806  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 395
09-13 11:56:59.270  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.270  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-13 11:56:59.270  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.270  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.270  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.270  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.270  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
,09-13 11:56:59.270  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.270  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.270  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:56:59.271  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.271  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.271  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.271  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.272  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.272  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:56:59.272  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.272  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.273  3806  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true,
09-13 11:56:59.273  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.273  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.273  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.273  3806  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 395)
09-13 11:56:59.273  3806  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 395)
09-13 11:56:59.274  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.274  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.274  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.274  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.274  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.274  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.274  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.274  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.274  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.274  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.274  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.275  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.275  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.275  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.276  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.276  3806  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 11:56:59.276  3806  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 11:56:59.276  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
09-13 11:56:59.276  3806  3857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 11:56:59.277  3806  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 11:56:59.277  3806  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-13 11:56:59.277  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:56:59.277  3806  3857 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 11:56:59.277  3806  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-13 11:56:59.277  3806  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 11:56:59.277  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:56:59.277  3806  3857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 11:56:59.277  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.277  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.277  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:56:59.277  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.277  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.277  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.277  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.277  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.277  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.278  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 11:56:59.278  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.278  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.278  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.278  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.278  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.278  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.278  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.279  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.279  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.279  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.279  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.279  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.279  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.279  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.279  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.279  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.279  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.279  2666  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 11:56:59.279  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.279  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.280  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.280  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.280  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.280  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.280  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
,09-13 11:56:59.280  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.280  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.280  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:56:59.280  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.280  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.280  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.280  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.280  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.280  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.280  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:56:59.280  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.280  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.280  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.280  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.281  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.281  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.281  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.281  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.282  3806  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 11:56:59.282  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:56:59.283  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 11:56:59.283  3806  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 11:56:59.284  3806  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 11:56:59.284  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 11:56:59.284  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 11:56:59.284  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:56:59.284  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.284  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 11:56:59.284  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 11:56:59.284  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 11:56:59.284  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.284  3806  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 11:56:59.285  2666  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 11:56:59.285  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 11:56:59.285  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.285  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.285  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.285  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:56:59.285  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 11:56:59.285  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:56:59.285  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.285  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.286  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:56:59.286  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.286  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:56:59.286  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:56:59.286  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.286  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.286  3806  3872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:56:59.286  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.286  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.287  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.287  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.287  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.287  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.287  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.287  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.287  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.287  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.287  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.287  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.287  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.288  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,09-13 11:56:59.288  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:56:59.288  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.288  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.288  3806  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 11:56:59.288  3806  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 11:56:59.288  3806  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 11:56:59.289  3806  3857 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 11:56:59.289  3806  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 11:56:59.289  3806  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 11:56:59.289  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 11:56:59.289  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 11:56:59.290  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.290  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:56:59.290  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.290  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.290  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.290  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.290  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.290  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.290  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.290  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:56:59.290  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.290  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.290  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.290  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.291  2666  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 11:56:59.291  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.291  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.291  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.291  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.291  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.292  2666  2701 D BtGatt.ScanManager: stopping BLe Batch
09-13 11:56:59.294  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:56:59.294  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:56:59.294  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:56:59.294  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:56:59.294  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.294  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.294  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.294  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.294  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
,09-13 11:56:59.294  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.294  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.294  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.294  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.294  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.295  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.295  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.295  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.295  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.296  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:56:59.296  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:56:59.296  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:56:59.296  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:56:59.297  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.297  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:56:59.297  3806  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f72b1d not in the list
09-13 11:56:59.297  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:56:59.297  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.297  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:56:59.297  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:56:59.297  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.297  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:56:59.297  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:56:59.297  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:56:59.298  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:56:59.298  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:56:59.298  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ce6192 not in the list
09-13 11:56:59.298  2666  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 11:56:59.298  3806  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 11:56:59.298  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:56:59.298  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 11:56:59.298  3806  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 11:56:59.298  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 11:56:59.299  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 11:56:59.299  3806  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 11:56:59.299  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 11:56:59.300  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 11:56:59.300  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 11:56:59.301  3806  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 11:56:59.301  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 11:56:59.301  3806  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 11:56:59.301  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 11:56:59.301  3806  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-13 11:56:59.301  3806  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 11:56:59.301  3806  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 11:56:59.301  3806  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 11:56:59.302  3806  3857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 11:56:59.302  3806  3857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 11:56:59.302  3806  3857 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-13 11:56:59.302  3806  3857 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 11:56:59.303  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:56:59.303  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc39624 added. We now have 2 listener(s)
09-13 11:56:59.303  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:56:59.304  3806  3857 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 11:56:59.304   874  2000 D WifiService: setWifiEnabled: true pid=3806, uid=10000
09-13 11:56:59.304  2666  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 11:56:59.304   874  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 11:56:59.304  2666  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:56:59.305  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:56:59.305  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ade158d added. We now have 3 listener(s)
09-13 11:56:59.305  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:56:59.310  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:56:59.310  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32e5342 added. We now have 4 listener(s)
,09-13 11:56:59.310  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:56:59.312  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:56:59.312  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f23bf53 added. We now have 5 listener(s)
09-13 11:56:59.312  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:56:59.315   874   884 D WifiService: setWifiEnabled: false pid=3806, uid=10000
09-13 11:56:59.315   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 11:56:59.319  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:56:59.319  2666  2693 D BluetoothAdapterState: Current state: ON, message: 23
09-13 11:56:59.319  2666  2693 D BluetoothAdapterProperties: Setting state to 13
09-13 11:56:59.319  2666  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 11:56:59.320  2666  2693 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 11:56:59.321  2666  2693 I BluetoothAdapterState: Entering PendingCommandState
09-13 11:56:59.322  2666  2666 D BluetoothMapService: onReceive
,09-13 11:56:59.322  2666  2666 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:56:59.322  2666  2666 D BluetoothMapService: STATE_TURNING_OFF
09-13 11:56:59.322  2666  2666 D BluetoothMapService: MAP Service closeService in
09-13 11:56:59.322  2666  2666 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 11:56:59.322  2666  2666 D ObexServerSockets0: shutdown(block = true)
09-13 11:56:59.323  2666  2666 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 11:56:59.323  2666  2666 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 11:56:59.323  2666  2820 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 11:56:59.323  2666  2808 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 11:56:59.323  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:59.323  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:56:59.324  2666  2821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 11:56:59.324  2666  2666 I BtOppRfcommListener: stopping Accept Thread
09-13 11:56:59.324  2666  3438 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:56:59.324  2666  3438 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 11:56:59.325  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:56:59.325  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.325  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:56:59.327  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.329  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.332  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:56:59.332  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:56:59.332  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:56:59.332  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:56:59.333   874   887 I ActivityManager: Start proc 3875:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-13 11:56:59.334  2666  2698 D BluetoothAdapterProperties: Scan Mode:20
09-13 11:56:59.334  2666  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 11:56:59.334  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.336  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.339  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 11:56:59.339  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.339  2666  2666 D HeadsetService: Received stop request...Stopping profile...
09-13 11:56:59.344   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 11:56:59.344   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 11:56:59.344   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:56:59.344   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:56:59.344   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 11:56:59.344   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 11:56:59.345  1376  3611 D BluetoothHeadset: Proxy object disconnected
09-13 11:56:59.345   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 11:56:59.346  1935  1949 D BluetoothHeadset: Proxy object disconnected
,09-13 11:56:59.346  2666  2666 D A2dpService: Received stop request...Stopping profile...
09-13 11:56:59.346  1376  1376 D HeadsetProfile: Bluetooth service disconnected
09-13 11:56:59.347  2666  2814 D A2dpStateMachine: Exit Disconnected: -1
09-13 11:56:59.350   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 11:56:59.350  1376  1376 D BluetoothA2dp: Proxy object disconnected
09-13 11:56:59.350  2666  2666 D HidService: Received stop request...Stopping profile...
09-13 11:56:59.350  2666  2666 D HidService: Stopping Bluetooth HidService
,09-13 11:56:59.351  1376  1376 D BluetoothInputDevice: Proxy object disconnected
,09-13 11:56:59.351  1376  1376 D HidProfile: Bluetooth service disconnected
,09-13 11:56:59.352  2666  2666 D HealthService: Received stop request...Stopping profile...
09-13 11:56:59.352   874  1878 D DhcpClient: Clearing IP address
09-13 11:56:59.353  2666  2666 D PanService: Received stop request...Stopping profile...
09-13 11:56:59.353   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 11:56:59.354  1376  1376 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 11:56:59.354  1376  1376 D PanProfile: Bluetooth service disconnected
,09-13 11:56:59.354  2666  2666 D BluetoothMapService: Received stop request...Stopping profile...
09-13 11:56:59.355  2666  2666 D BluetoothMapService: stop()
09-13 11:56:59.355  2666  2666 D BluetoothMapAppObserver: deinitObservers()
,09-13 11:56:59.355  2666  2666 D BluetoothMapAppObserver: removeReceiver()
09-13 11:56:59.356  1376  1376 D BluetoothMap: Proxy object disconnected
,09-13 11:56:59.357  1376  1376 D MapProfile: Bluetooth service disconnected
,09-13 11:56:59.357  1550  2143 V NativeCrypto: Read error: ssl=0xaee3dc00: I/O error during system call, Connection timed out
09-13 11:56:59.357  2666  2666 V BluetoothAdapterState: isTurningOff()=true
09-13 11:56:59.357  2666  2666 V BluetoothAdapterState: isTurningOn()=false
09-13 11:56:59.357  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:56:59.357  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:56:59.358   373   872 D CommandListener: Setting iface cfg
09-13 11:56:59.358  1550  2143 V NativeCrypto: SSL shutdown failed: ssl=0xaee3dc00: I/O error during system call, Broken pipe
09-13 11:56:59.360   874  1684 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-13 11:56:59.361   874  1871 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-13 11:56:59.363   874  1890 D DhcpClient: Receive thread stopped
09-13 11:56:59.365   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
09-13 11:56:59.365   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 11:56:59.366   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-13 11:56:59.368   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 11:56:59.369   396   396 E Parcel  : Reading a NULL string not supported here.
09-13 11:56:59.370   874  1871 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-13 11:56:59.371  2666  2666 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 11:56:59.371  2666  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 11:56:59.371  2666  2666 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 11:56:59.371  2666  2666 V BluetoothAdapterState: isTurningOff()=true
09-13 11:56:59.371  2666  2666 V BluetoothAdapterState: isTurningOn()=false
09-13 11:56:59.371  2666  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:56:59.371  2666  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:56:59.371  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:56:59.371  2666  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:56:59.371  2666  2698 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 11:56:59.371  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:56:59.373  2666  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-13 11:56:59.373  2666  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:56:59.373  2666  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:56:59.373  2666  2792 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:56:59.373  2666  2792 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:56:59.373  2666  2792 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:56:59.373  2666  2792 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:56:59.374  2666  2666 V BluetoothAdapterState: isTurningOff()=true
,09-13 11:56:59.374  2666  2666 V BluetoothAdapterState: isTurningOn()=false
09-13 11:56:59.374  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:56:59.374  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:56:59.374  2666  2666 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 11:56:59.374  2666  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 11:56:59.374   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:56:59.375  2666  2666 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 11:56:59.375  2666  2666 V BluetoothAdapterState: isTurningOff()=true
09-13 11:56:59.375  2666  2666 V BluetoothAdapterState: isTurningOn()=false
09-13 11:56:59.375  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:56:59.375  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:56:59.376  2666  2666 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 11:56:59.376  2666  2698 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 11:56:59.376  2666  2666 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 11:56:59.376  2666  2666 V BluetoothAdapterState: isTurningOff()=true
09-13 11:56:59.376  2666  2666 V BluetoothAdapterState: isTurningOn()=false
09-13 11:56:59.376  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:56:59.376  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:56:59.376  2666  2666 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 11:56:59.377  2666  2666 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 11:56:59.377  2666  2666 D BluetoothMapService: MAP Service closeService in
09-13 11:56:59.377  2666  2666 V BluetoothAdapterState: isTurningOff()=true
09-13 11:56:59.378  2666  2666 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:56:59.378  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:56:59.378  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:56:59.378  2666  2666 D BluetoothMapService: cleanup()
09-13 11:56:59.378  2666  2666 D BluetoothMapService: MAP Service closeService in
09-13 11:56:59.379  2666  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-13 11:56:59.379  2666  2693 D BluetoothAdapterProperties: Setting state to 15
09-13 11:56:59.379  2666  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 11:56:59.379  2666  2693 I BluetoothAdapterState: Entering BleOnState
09-13 11:56:59.379   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 11:56:59.379  1376  3611 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 11:56:59.380  1376  1394 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:56:59.380   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:56:59.380   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:56:59.380  1935  2108 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:56:59.381  1376  3611 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 11:56:59.382  1376  1388 D BluetoothMap: onBluetoothStateChange: up=false
09-13 11:56:59.383  1376  2213 D BluetoothPan: onBluetoothStateChange on: false
,09-13 11:56:59.383  1376  1394 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:56:59.384   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:56:59.384   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:56:59.384  2666  2693 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 11:56:59.384  2666  2693 D BluetoothAdapterProperties: Setting state to 16
09-13 11:56:59.384  2666  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-13 11:56:59.385  2666  2693 D BluetoothAdapterProperties: onBleDisable
09-13 11:56:59.385  2666  2693 I BluetoothAdapterState: Entering PendingCommandState
09-13 11:56:59.385  2666  2694 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 11:56:59.384   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 11:56:59.387  2666  2792 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 11:56:59.387  2666  2792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:56:59.388  2666  2698 D BluetoothAdapterProperties: Scan Mode:20
09-13 11:56:59.388  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:56:59.388  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:56:59.389  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:56:59.389  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:56:59.390   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 11:56:59.391  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:56:59.391  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:56:59.392  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:56:59.392  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:56:59.394  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.395  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.396  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.397  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.397  2148  2348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 11:56:59.409  3875  3875 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-13 11:56:59.416   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:56:59.429  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 11:56:59.433   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e5380d0:true
,09-13 11:56:59.434  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:56:59.439   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:56:59.440   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 11:56:59.440   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:56:59.446   874  2033 I ActivityManager: Start proc 3892:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 11:56:59.449   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 11:56:59.452  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.455  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:56:59.455  3406  3406 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@248cab7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-13 11:56:59.463  3875  3875 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 11:56:59.465  3875  3875 D BluetoothMap: Create BluetoothMap proxy object
,09-13 11:56:59.476  3875  3875 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 11:56:59.483  3892  3892 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 11:56:59.491  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:56:59.495   874  2006 I ActivityManager: Killing 3053:com.google.android.talk/u0a61 (adj 15): empty #17
,09-13 11:56:59.496   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 11:56:59.497   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 11:56:59.592  2666  2698 I bt_hci  : shut_down
,09-13 11:56:59.594  2666  2702 D bt_hwcfg: hw_epilog_process
,09-13 11:56:59.595  2666  2702 I bt_vendor: low_power_mode_cb
,09-13 11:56:59.617  2666  2702 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 11:56:59.617  2666  2702 I bt_vendor: epilog_cb
,09-13 11:56:59.617  2666  2702 I bt_hci  : epilog_finished_callback
,09-13 11:56:59.621  2666  2698 I bt_hci_h4: hal_close
,09-13 11:56:59.622  2666  2698 I bt_userial_vendor: device fd = 51 close
,09-13 11:56:59.641  3892  3892 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.641  3892  3892 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.641  3892  3892 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.641  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.642  3892  3892 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.642  3892  3892 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.642  3892  3892 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.642  3892  3892 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.642  3892  3892 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:56:59.642  3892  3892 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:56:59.661   874  2000 I ActivityManager: Start proc 3925:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-13 11:56:59.661   874  2000 I ActivityManager: Killing 3567:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-13 11:56:59.735  3925  3925 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-13 11:56:59.740  2666  2694 D bt_stack_manager: event_shut_down_stack finished.
,09-13 11:56:59.741  2666  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 11:56:59.745  2666  2666 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 11:56:59.745  2666  2693 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 11:56:59.746  2666  2666 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 11:56:59.746  2666  2666 D BtGatt.GattService: stop()
09-13 11:56:59.746  2666  2666 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 11:56:59.750  2666  2666 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:56:59.750  2666  2666 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:56:59.751  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:56:59.751  2666  2666 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 11:56:59.751  2666  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 11:56:59.752  2666  2693 D BluetoothAdapterProperties: Setting state to 10
09-13 11:56:59.752  2666  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 11:56:59.753  2666  2693 I BluetoothAdapterState: Entering OffState
,09-13 11:56:59.755   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-13 11:56:59.777  2666  2666 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 11:56:59.778  2666  2666 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 11:56:59.778  2666  2694 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 11:56:59.780  2666  2694 D bt_stack_manager: event_clean_up_stack finished.
,09-13 11:56:59.780  2666  2666 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 11:56:59.783  2666  2666 I art     : System.exit called, status: 0
,09-13 11:56:59.783  2666  2666 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 11:56:59.787  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:56:59.850   874  2006 I ActivityManager: Process com.android.bluetooth (pid 2666) has died
,09-13 11:56:59.977  3925  3944 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-13 11:56:59.977  3925  3944 I Babel_SMS: MmsConfig.loadMmsSettings
,09-13 11:56:59.978  3925  3944 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-13 11:56:59.978  3925  3944 I Babel_SMS: MmsConfig.loadFromDatabase
,09-13 11:57:00.026  3925  3944 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-13 11:57:00.027  3925  3944 I Babel_SMS: MmsConfig.loadFromResources
,09-13 11:57:00.031  3925  3944 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-13 11:57:00.032  3925  3944 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-13 11:57:00.072  3925  3925 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 11:57:00.075  3925  3925 I Babel_Crash: startup - clean
,09-13 11:57:00.102  3925  3925 I Babel_telephony: TeleModule.launchCompleted
,09-13 11:57:00.110   874   885 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-13 11:57:00.120  3925  3925 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-13 11:57:00.126  3925  3925 W Babel   : BAM#gBA: invalid account id: -1
,09-13 11:57:00.126  3925  3925 W Babel   : BAM#gBA: invalid account id: -1
,09-13 11:57:00.127  3925  3925 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-13 11:57:00.131  3925  3950 I Babel   : deleted: false for 0
,09-13 11:57:00.138   874  2004 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-13 11:57:00.194   874   885 I ActivityManager: Start proc 3953:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 11:57:00.246  3925  3925 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 11:57:00.270  3953  3953 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 11:57:00.348  3925  3925 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 11:57:00.363  3925  3925 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 11:57:00.377  3925  3925 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 11:57:00.384  3925  3925 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 11:57:00.401  3925  3925 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 11:57:00.411  3953  3953 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 11:57:00.422  3925  3925 I vclib   : onServiceConnected,
,09-13 11:57:00.439  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 11:57:00.464   874   884 I ActivityManager: Start proc 3978:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-13 11:57:00.484  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:57:00.486   874  2034 I ActivityManager: Killing 3406:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 11:57:00.523  3892  3919 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 11:57:00.557   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d52c48:true
,09-13 11:57:00.655  3978  3978 D AdapterServiceConfig: Adding HeadsetService
,09-13 11:57:00.655  3978  3978 D AdapterServiceConfig: Adding A2dpService
,09-13 11:57:00.655  3978  3978 D AdapterServiceConfig: Adding HidService
09-13 11:57:00.655  3978  3978 D AdapterServiceConfig: Adding HealthService
09-13 11:57:00.655  3978  3978 D AdapterServiceConfig: Adding PanService
09-13 11:57:00.656  3978  3978 D AdapterServiceConfig: Adding GattService
,09-13 11:57:00.656  3978  3978 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 11:57:00.659   874   884 I ActivityManager: Killing 3615:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-13 11:57:00.708  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:57:00.728  1755  1755 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:57:00.732  1755  1755 D SystemUpdateService: onCreate
,09-13 11:57:00.738  1755  1755 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:57:00.749  1755  3992 I SystemUpdateService: active receiver: enabled
,09-13 11:57:00.757  1755  3992 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 11:57:00.760  1755  1755 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 11:57:00.763  1755  3992 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 11:57:00.763  1755  3992 I SystemUpdateService: now status is 0 (complete)
,09-13 11:57:00.764  1755  3992 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 11:57:00.764  1755  3992 I SystemUpdateService: file has been verified
,09-13 11:57:00.766  1755  3992 I SystemUpdateService: OTA package size = 12249756
,09-13 11:57:00.767  1755  2429 I iu.UploadsManager: num queued entries: 0
,09-13 11:57:00.768  1755  2429 I iu.UploadsManager: num updated entries: 0
,09-13 11:57:00.771  1755  1755 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 11:57:00.775  1755  2429 I iu.SyncManager: NEXT; no task
,09-13 11:57:00.779  1755  1755 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 11:57:00.783  1755  3992 I SystemUpdateService: showing system update notification
,09-13 11:57:00.817   874   884 I ActivityManager: Start proc 3994:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver,
,09-13 11:57:00.830  1755  1755 D SystemUpdateService: onDestroy
,09-13 11:57:00.864  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 11:57:00.866  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:57:00.877  3994  3994 D SprintDMHelper: simOperator: 
,09-13 11:57:00.877  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 11:57:00.899   874  3991 I ActivityManager: Start proc 4006:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 11:57:00.900   874  3991 I ActivityManager: Killing 3462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 11:57:01.061   874  2034 I ActivityManager: Start proc 4021:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
09-13 11:57:01.064  3925  4020 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 11:57:01.086   874   884 I ActivityManager: Killing 3498:android.process.acore/u0a5 (adj 15): empty #17
,09-13 11:57:01.112  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 11:57:01.170  4021  4021 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 11:57:01.170  4021  4021 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 11:57:01.170  4021  4021 I GAv4    :   adb logcat -s GAv4
,09-13 11:57:01.186  4021  4021 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:57:01.192  4021  4021 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:57:01.219  4021  4038 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 11:57:01.332  4021  4021 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 11:57:01.371  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 11:57:01.381  4021  4021 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9768-9771)
,09-13 11:57:01.381  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 11:57:01.394  4021  4021 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {46bcfa7}
,09-13 11:57:01.395  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 11:57:01.395  4021  4021 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 11:57:01.404  4021  4021 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 11:57:01.406  4021  4021 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 11:57:01.424  4021  4021 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 11:57:01.438  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 11:57:01.438  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 11:57:01.438  4021  4021 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 11:57:01.438  4021  4021 I Adreno  : Build Date                       : 10/20/15
09-13 11:57:01.438  4021  4021 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 11:57:01.438  4021  4021 I Adreno  : Local Branch                     : M14
09-13 11:57:01.438  4021  4021 I Adreno  : Remote Branch                    : 
09-13 11:57:01.438  4021  4021 I Adreno  : Remote Branch                    : 
09-13 11:57:01.438  4021  4021 I Adreno  : Reconstruct Branch               : 
,09-13 11:57:01.501  4021  4021 I NSApplication: Starting up...
,09-13 11:57:01.506  4021  4067 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 11:57:01.523   874  1382 I ActivityManager: Start proc 4072:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-13 11:57:01.524   874  1382 I ActivityManager: Killing 3690:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 11:57:01.588  4072  4072 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 11:57:01.775   874  2006 I ActivityManager: Killing 3706:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 11:57:02.328   874  2033 D WifiService: setWifiEnabled: true pid=3806, uid=10000
,09-13 11:57:02.329   874  2033 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:57:02.346   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-13 11:57:02.357  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:02.358  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:57:02.358  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:02.358  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:02.361  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:02.362  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:57:02.362  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:02.363  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:02.378   874  1316 D WifiConfigStore: loaded 0 passpoint configs
09-13 11:57:02.380   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 11:57:02.380   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 11:57:02.381   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 11:57:02.382   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 11:57:02.382   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 11:57:02.382   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 11:57:02.402   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 11:57:02.402   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.50 rxSuccessRate=10.62 delta 1000 -> 994
,09-13 11:57:02.404   373   872 D CommandListener: Setting iface cfg
09-13 11:57:02.405   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-13 11:57:02.405   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 11:57:02.411   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-13 11:57:02.411   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:57:02.422   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 11:57:02.454   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 11:57:02.456   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 11:57:02.500   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 11:57:02.502  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 11:57:02.929  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 11:57:02.976  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 11:57:02.977  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 11:57:02.985   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:57:02.998   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 11:57:02.999   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:57:03.000   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 11:57:03.023   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:57:03.034   373   872 D CommandListener: Setting iface cfg
,09-13 11:57:03.034   874  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 11:57:03.048   874  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-13 11:57:03.051   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 11:57:03.065   874  4095 D DhcpClient: Receive thread started
,09-13 11:57:03.148   874  1316 E native  : do suspend false
,09-13 11:57:03.168   874  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 11:57:03.187   874  4095 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172691, domain null
,09-13 11:57:03.189   874  1878 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172691 seconds
,09-13 11:57:03.192   874  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 11:57:03.207   874  4095 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 11:57:03.208   874  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 11:57:03.213   373   872 D CommandListener: Setting iface cfg
,09-13 11:57:03.224   874  1878 D DhcpClient: Scheduling renewal in 86399s
,09-13 11:57:03.224   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 11:57:03.241   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 11:57:03.242   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 11:57:03.243   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 11:57:03.243   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 11:57:03.246   874  1318 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 11:57:03.254   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 11:57:03.303   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 11:57:03.303   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 11:57:03.305   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 11:57:03.306   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-13 11:57:03.307   874  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 11:57:03.323   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 11:57:03.328   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 11:57:03.328   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101],
09-13 11:57:03.328   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101],
,09-13 11:57:03.328   874  1318 D ConnectivityService:    accepting network in place of null
,09-13 11:57:03.328   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-13 11:57:03.329   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 11:57:03.331   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 11:57:03.367   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:57:03.411   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:57:03.419   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 11:57:03.420   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:57:03.429   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-13 11:57:03.433   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 11:57:03.441  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:03.444  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:57:03.444  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:03.444  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:57:03.450  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:03.450  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 11:57:03.450  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:03.450  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:57:03.457  1755  1755 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:57:03.461  1755  1755 D SystemUpdateService: onCreate
,09-13 11:57:03.465  1755  1755 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:57:03.467  1755  4106 I SystemUpdateService: active receiver: enabled
,09-13 11:57:03.470  1755  4106 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 11:57:03.474  1755  4106 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 11:57:03.474  1755  4106 I SystemUpdateService: now status is 0 (complete)
,09-13 11:57:03.474  1755  4106 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 11:57:03.474  1755  4106 I SystemUpdateService: file has been verified
09-13 11:57:03.474  1755  4106 I SystemUpdateService: OTA package size = 12249756
,09-13 11:57:03.480  1755  4106 I SystemUpdateService: showing system update notification
,09-13 11:57:03.488  1755  1755 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 11:57:03.493  1755  2429 I iu.UploadsManager: num queued entries: 0
,09-13 11:57:03.494  1755  1755 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 11:57:03.493  1755  2429 I iu.UploadsManager: num updated entries: 0
,09-13 11:57:03.496  1755  1755 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 11:57:03.498  1755  4110 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 11:57:03.498  1755  4110 W BaseAppContext: Using Auth Proxy for data requests.
09-13 11:57:03.498  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-13 11:57:03.499  1755  4110 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 11:57:03.501  1755  2429 I iu.SyncManager: NEXT; no task
09-13 11:57:03.505  1755  1755 D SystemUpdateService: onDestroy
09-13 11:57:03.505  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 11:57:03.507  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 11:57:03.507  3994  3994 D SprintDMHelper: simOperator: 
09-13 11:57:03.507  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 11:57:03.534   874   886 I ActivityManager: Start proc 4114:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-13 11:57:03.554  1550  1565 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 11:57:03.555  1550  1565 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-13 11:57:03.555  1550  1565 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:57:03.555  1550  1565 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:03.569  4114  4114 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-13 11:57:03.571  1755  4110 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-13 11:57:03.636  4114  4114 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-13 11:57:03.648  4114  4114 I BooksApp: Created application version: 3.6.9 (30609)
,09-13 11:57:03.688  1550  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 11:57:03.688  1550  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 11:57:03.688  1550  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:03.688  1550  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:03.706  3553  4128 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 11:57:03.706  3553  4128 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at blb.a(PG:3937)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at czp.a(PG:18188)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:57:03.706  3553  4128 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	... 12 more
09-13 11:57:03.706  3553  4128 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at fal.a(PG:38)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:57:03.706  3553  4128 E HttpOperation: 	... 14 more,
,09-13 11:57:03.772  1550  2428 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 11:57:03.772  1550  2428 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 11:57:03.772  1550  2428 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:03.773  1550  2428 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:03.790  4114  4135 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 11:57:03.792  3553  4128 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 11:57:03.792  3553  4128 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jdm.a(PG:82)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jcs.o(PG:406)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jcn.a(PG:1379)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jcs.i(PG:143)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at hec.a(PG:42)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at hee.a(PG:102)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at czr.a(PG:65)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at kka.a(PG:108)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at czp.a(PG:19176)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at czp.a(PG:9081)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at czq.run(PG:1686)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:57:03.792  3553  4128 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jdj.a(PG:4091)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jdj.a(PG:1125)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jdm.a(PG:77)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	... 15 more
09-13 11:57:03.792  3553  4128 E HttpOperation: Caused by: faj: BadAuthentication
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at fal.a(PG:38)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	at jdj.a(PG:4089)
09-13 11:57:03.792  3553  4128 E HttpOperation: 	... 17 more
,09-13 11:57:03.793  3553  4128 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 11:57:03.793  3553  4128 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at hec.a(PG:42)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at hee.a(PG:102)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at czr.a(PG:65)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at kka.a(PG:108)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	... 15 more
09-13 11:57:03.793  3553  4128 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at fal.a(PG:38)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 11:57:03.793  3553  4128 E ExperimentLoader: 	... 17 more
,09-13 11:57:03.878   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127868, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:57:03.955  4114  4143 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 11:57:03.984  3037  4140 V KeepSync: Connecting to GoogleApiClient
,09-13 11:57:03.986   874  2000 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 11:57:04.055  1550  1565 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:57:04.056  1550  1565 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 11:57:04.056  1550  1565 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 11:57:04.057  1550  1565 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:04.088  1550  1568 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 11:57:04.089  1550  1568 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 11:57:04.089  1550  1568 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:04.089  1550  1568 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:04.104  1755  4144 V BaseAuthAsyncOperation: access token request failed
,09-13 11:57:04.105  3037  4140 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 11:57:04.111  1550  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 11:57:04.111  1550  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 11:57:04.111  1550  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:04.112  1550  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:04.132  4114  4143 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 11:57:04.134  4114  4135 E BooksSync: Soft error
09-13 11:57:04.134  4114  4135 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:57:04.134  4114  4135 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 11:57:04.134  4114  4135 E BooksSync: Sync error
09-13 11:57:04.134  4114  4135 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 11:57:04.134  4114  4135 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 11:57:04.135  4114  4135 I BooksSync: Finished books sync
,09-13 11:57:04.139   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127821, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:57:04.165  1550  2162 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 11:57:04.165  1550  2162 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 11:57:04.165  1550  2162 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:04.165  1550  2162 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:04.180  3037  4140 E KeepSync: IOException
09-13 11:57:04.180  3037  4140 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 11:57:04.180  3037  4140 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 11:57:04.180  3037  4140 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 11:57:04.180  3037  4140 E KeepSync: 	... 10 more
,09-13 11:57:04.180  3037  4140 W KeepSync: Sync result 2
,09-13 11:57:04.186   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 131056, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 11:57:04.419   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 11:57:04.692   874  4094 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133083, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:57:05.336   874  2032 D WifiService: setWifiEnabled: false pid=3806, uid=10000
09-13 11:57:05.337   874  2032 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:57:05.366  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 11:57:05.368   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 11:57:05.368   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-13 11:57:05.368   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:57:05.369   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:57:05.381   874  1878 D DhcpClient: Clearing IP address
,09-13 11:57:05.381   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:57:05.385   373   872 D CommandListener: Setting iface cfg
,09-13 11:57:05.391   874  4095 D DhcpClient: Receive thread stopped
,09-13 11:57:05.397   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 11:57:05.397   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-13 11:57:05.398   396   396 E Parcel  : Reading a NULL string not supported here.
,09-13 11:57:05.405   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-13 11:57:05.406   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-13 11:57:05.407   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:57:05.408   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 11:57:05.419  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:05.420  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:57:05.420  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:05.420  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:05.420   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 11:57:05.421  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:05.421  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:57:05.421  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:05.421  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:57:05.427  3925  4112 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-13 11:57:05.428   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 11:57:05.428  2148  2348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	,at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
09-13 11:57:05.432  3925  4112 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-13 11:57:05.432  3925  4112 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 11:57:05.443   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:57:05.471   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 11:57:05.471   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 11:57:05.471   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:57:05.475   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 11:57:05.476  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:05.476  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:05.483  1755  1755 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:57:05.489  1755  1755 D SystemUpdateService: onCreate
,09-13 11:57:05.492  1755  1755 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:57:05.502  1755  1755 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 11:57:05.507  1755  4153 I SystemUpdateService: active receiver: enabled
,09-13 11:57:05.508  1755  1755 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-13 11:57:05.510  1755  1755 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 11:57:05.513  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:57:05.516  1755  2429 I iu.UploadsManager: num queued entries: 0
09-13 11:57:05.516  1755  2429 I iu.UploadsManager: num updated entries: 0
,09-13 11:57:05.517  1755  2429 I iu.SyncManager: NEXT; no task
09-13 11:57:05.517  3994  3994 D SprintDMHelper: simOperator: 
09-13 11:57:05.517  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 11:57:05.527  1755  4153 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-13 11:57:05.530  1755  4153 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-13 11:57:05.530  1755  4153 I SystemUpdateService: now status is 0 (complete)
09-13 11:57:05.530  1755  4153 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 11:57:05.530  1755  4153 I SystemUpdateService: file has been verified
09-13 11:57:05.530  1755  4153 I SystemUpdateService: OTA package size = 12249756
09-13 11:57:05.537  1755  4153 I SystemUpdateService: showing system update notification
,09-13 11:57:05.548  3925  4157 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 11:57:05.551   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 11:57:05.552   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 11:57:05.552  1755  1755 D SystemUpdateService: onDestroy
,09-13 11:57:05.586  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:57:05.608  1550  1565 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 11:57:05.608  1550  1565 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 11:57:05.608  1550  1565 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:05.608  1550  1565 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:05.621  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 11:57:05.621  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 11:57:05.621  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 11:57:05.631   874  2034 I ActivityManager: Killing 2252:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 11:57:05.701   874  2034 I ActivityManager: Killing 3734:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 11:57:08.390  3978  3978 D BluetoothAdapterState: make() - Creating AdapterState
09-13 11:57:08.389   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d95a62b:true
,09-13 11:57:08.395  3978  3978 I bt_bluedroid: init
,09-13 11:57:08.396  3978  4161 I BluetoothAdapterState: Entering OffState
,09-13 11:57:08.398  3978  4162 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 11:57:08.398  3978  4162 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 11:57:08.398  3978  4162 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 11:57:08.398  3978  4162 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 11:57:08.399  3978  3978 I bt_bluedroid: get_profile_interface socket
,09-13 11:57:08.402  3978  4165 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:57:08.403  3978  3978 I bt_bluedroid: get_profile_interface sdp
,09-13 11:57:08.403  3978  4165 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:57:08.408  3978  3988 I bt_bluedroid: config_hci_snoop_log
,09-13 11:57:08.410   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 11:57:08.416  3978  4161 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 11:57:08.417  3978  4161 D BluetoothAdapterProperties: Setting state to 14
,09-13 11:57:08.417  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 11:57:08.420  3978  4161 D BluetoothBondStateMachine: make
,09-13 11:57:08.422  3978  4166 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 11:57:08.425  3978  4161 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:57:08.427  3978  3978 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 11:57:08.429  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:57:08.431  3978  3978 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 11:57:08.432  3978  3978 D BtGatt.GattService: Received start request. Starting profile...
09-13 11:57:08.432  3978  3978 D BtGatt.GattService: start()
09-13 11:57:08.432  3978  3978 I bt_bluedroid: get_profile_interface gatt
09-13 11:57:08.433  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:57:08.433  3978  3978 D BtGatt.AdvertiseManager: advertise manager created
,09-13 11:57:08.442  3978  3978 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:08.442  3978  3978 V BluetoothAdapterState: isTurningOn()=false
09-13 11:57:08.442  3978  3978 V BluetoothAdapterState: isBleTurningOn()=true
,09-13 11:57:08.443  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:08.443  3978  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 11:57:08.443  3978  4161 I bt_bluedroid: enable
,09-13 11:57:08.444  3978  4162 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 11:57:08.444  3978  4162 I bt_hci  : start_up
,09-13 11:57:08.460  3978  4162 I bt_vendor: alloc value 0xb39b9189
,09-13 11:57:08.461  3978  4162 I bt_vendor: init
,09-13 11:57:08.461  3978  4162 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 11:57:08.461  3978  4162 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 11:57:08.568  3978  4162 D bt_hci  : start_up starting async portion
,09-13 11:57:08.568  3978  4169 I bt_hci  : event_finish_startup
,09-13 11:57:08.569  3978  4169 I bt_hci_h4: hal_open
09-13 11:57:08.569  3978  4169 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 11:57:08.575  3978  4169 I bt_userial_vendor: device fd = 51 open
,09-13 11:57:08.609  3978  4169 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:57:08.640  4114  4133 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-13 11:57:08.641  3978  4169 D bt_hwcfg: Chipset BCM4354A2
,09-13 11:57:08.641  3978  4169 D bt_hwcfg: Target name = [BCM4354A2]
09-13 11:57:08.642  3978  4169 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 11:57:09.289  3978  4169 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-13 11:57:09.290  3978  4169 D bt_hwcfg: Settlement delay -- 100 ms
09-13 11:57:09.291  3978  4169 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 11:57:09.407  3978  4169 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:57:09.409  3978  4169 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 11:57:09.438  3978  4169 I bt_hwcfg: vendor lib fwcfg completed
,09-13 11:57:09.438  3978  4169 I bt_vendor: firmware callback
09-13 11:57:09.438  3978  4169 I bt_hci  : firmware_config_callback
,09-13 11:57:09.451  3978  4173 I bt_btu  : btu_task pending for preload complete event
,09-13 11:57:09.451  3978  4173 I bt_btu_task: Bluetooth chip preload is complete
09-13 11:57:09.452  3978  4173 I bt_btu  : btu_task received preload complete event
,09-13 11:57:09.461  3978  4173 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 11:57:09.462  3978  4173 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 11:57:09.462  3978  4173 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 11:57:09.462  3978  4173 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 11:57:09.463  3978  4173 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 11:57:09.463  3978  4173 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 11:57:09.463  3978  4173 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 11:57:09.463  3978  4173 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 11:57:09.463  3978  4173 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 11:57:09.464  3978  4173 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 11:57:09.464  3978  4173 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 11:57:09.464  3978  4173 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 11:57:09.464  3978  4173 I         : BTE_InitTraceLevels -- TRC_SMP
,09-13 11:57:09.465  3978  4173 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 11:57:09.465  3978  4173 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 11:57:09.592  3978  4173 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,09-13 11:57:09.592  3978  4173 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,09-13 11:57:09.632  3978  4165 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 11:57:09.634  3978  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 11:57:09.634  3978  4165 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:57:09.637  3978  4165 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:57:09.640  3978  4165 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:57:09.641  3978  4165 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 11:57:09.642  3978  4165 D bt_hci  : do_postload posting postload work item
,09-13 11:57:09.642  3978  4169 I bt_hci  : event_postload
,09-13 11:57:09.642  3978  4169 I bt_vendor: sco_config_cb
09-13 11:57:09.643  3978  4169 I bt_hci  : sco_config_callback postload finished.
,09-13 11:57:09.644  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:09.646  3978  4165 D bt_bte_conf: Device ID record 1 : primary
09-13 11:57:09.647  3978  4165 D bt_bte_conf:   vendorId            = 000f
09-13 11:57:09.647  3978  4165 D bt_bte_conf:   vendorIdSource      = 0001
09-13 11:57:09.647  3978  4165 D bt_bte_conf:   product             = 1200
,09-13 11:57:09.647  3978  4165 D bt_bte_conf:   version             = 1436
09-13 11:57:09.647  3978  4165 D bt_bte_conf:   clientExecutableURL = 
09-13 11:57:09.648  3978  4165 D bt_bte_conf:   serviceDescription  = 
,09-13 11:57:09.648  3978  4165 D bt_bte_conf:   documentationURL    = 
,09-13 11:57:09.648  3978  4165 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 11:57:09.648  3978  4162 D bt_stack_manager: event_start_up_stack finished
,09-13 11:57:09.650  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:09.651  3978  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 11:57:09.652  3978  4161 D BluetoothAdapterProperties: Setting state to 15
09-13 11:57:09.652  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 11:57:09.653  3978  4161 I BluetoothAdapterState: Entering BleOnState
09-13 11:57:09.653  3978  4169 I bt_vendor: low_power_mode_cb
,09-13 11:57:09.657  3978  4161 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 11:57:09.657  3978  4161 D BluetoothAdapterProperties: Setting state to 11
09-13 11:57:09.657  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 11:57:09.663  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:57:09.667  3978  3978 D HeadsetService: Received start request. Starting profile...
09-13 11:57:09.668  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:09.670  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:09.678  3978  3978 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 11:57:09.678  3978  3978 D HeadsetStateMachine: make
09-13 11:57:09.681  3978  4161 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:57:09.687  3978  3978 D HeadsetStateMachine: max_hf_connections = 1
,09-13 11:57:09.687  3978  3978 I bt_bluedroid: get_profile_interface handsfree
09-13 11:57:09.687  3978  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 11:57:09.688  3978  4165 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 11:57:09.693  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:09.696  3978  3978 D A2dpService: Received start request. Starting profile...
09-13 11:57:09.697  3978  3978 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 11:57:09.697  3978  3978 I bt_bluedroid: get_profile_interface avrcp
,09-13 11:57:09.703  3978  3978 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 11:57:09.703  3978  3978 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:57:09.703  3978  3978 D A2dpStateMachine: make
,09-13 11:57:09.704  3978  3978 I bt_bluedroid: get_profile_interface a2dp
,09-13 11:57:09.704  3978  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 11:57:09.707  3978  3978 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 11:57:09.707  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:09.708  3978  4182 D A2dpStateMachine: Enter Disconnected: -2
09-13 11:57:09.708  3978  3978 D HidService: Received start request. Starting profile...
,09-13 11:57:09.708  3875  3875 D BluetoothInputDevice: Proxy object connected
09-13 11:57:09.709  3978  3978 I bt_bluedroid: get_profile_interface hidhost
09-13 11:57:09.709  3978  4165 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
09-13 11:57:09.709  3978  3978 D HidService: setHidService(): set to: null
09-13 11:57:09.709  3978  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 11:57:09.709  3978  3978 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 11:57:09.710  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:57:09.710  3875  3875 D HidProfile: Bluetooth service connected
09-13 11:57:09.710  3978  3978 D HealthService: Received start request. Starting profile...
09-13 11:57:09.712  3978  3978 I bt_bluedroid: get_profile_interface health
,09-13 11:57:09.713  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:57:09.713  3978  3978 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 11:57:09.714  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:09.715  3978  3978 D PanService: Received start request. Starting profile...
,09-13 11:57:09.715  3978  3978 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 11:57:09.715  3978  3978 I bt_bluedroid: get_profile_interface pan
09-13 11:57:09.715  3875  3875 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:57:09.716  3978  4165 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 11:57:09.716  3875  3875 D PanProfile: Bluetooth service connected
09-13 11:57:09.717  3978  3978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:09.718  3978  3978 D BluetoothMapService: Received start request. Starting profile...
,09-13 11:57:09.718  3875  3875 D BluetoothMap: Proxy object connected
,09-13 11:57:09.718  3978  3978 D BluetoothMapService: start()
09-13 11:57:09.719  3875  3875 D MapProfile: Bluetooth service connected
09-13 11:57:09.719  3875  3875 D BluetoothMap: getConnectedDevices()
09-13 11:57:09.720  3875  3875 D BluetoothMap: Bluetooth is Not enabled
09-13 11:57:09.720  3978  3978 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-13 11:57:09.721  3978  3978 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 11:57:09.721  3978  3978 D BluetoothMapAppObserver: createReceiver()
09-13 11:57:09.722  3978  3978 D BluetoothMapAppObserver: initObservers()
09-13 11:57:09.723  3978  3978 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 11:57:09.730  3978  3978 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:09.730  3978  3978 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:09.730  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:09.730  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:09.731  3978  3978 V BluetoothAdapterState: isTurningOff()=false
09-13 11:57:09.731  3978  3978 V BluetoothAdapterState: isTurningOn()=true
,09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:09.732  3978  4180 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isTurningOff()=false
09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:09.732  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:09.734  3978  3978 V BluetoothAdapterState: isTurningOff()=false
09-13 11:57:09.734  3978  3978 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:09.734  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:09.734  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:09.735  3978  3978 V BluetoothAdapterState: isTurningOff()=false
09-13 11:57:09.735  3978  3978 V BluetoothAdapterState: isTurningOn()=true
,09-13 11:57:09.735  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:57:09.735  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:09.735  3978  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 11:57:09.735  3978  4161 D BluetoothAdapterProperties: ScanMode =  20
09-13 11:57:09.735  3978  4161 D BluetoothAdapterProperties: State =  11
,09-13 11:57:09.736  3978  4161 D BluetoothAdapterProperties: Setting state to 12
09-13 11:57:09.736  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 11:57:09.736  3978  4161 I BluetoothAdapterState: Entering OnState
09-13 11:57:09.737  1376  1388 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 11:57:09.737  3978  4165 D BluetoothAdapterProperties: Scan Mode:21
09-13 11:57:09.738  3978  4165 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 11:57:09.739  1376  1394 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:09.739  1376  1376 D BluetoothInputDevice: Proxy object connected
,09-13 11:57:09.739  1376  1376 D HidProfile: Bluetooth service connected
09-13 11:57:09.739   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:09.740  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:57:09.740   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:09.740  3875  3885 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:57:09.741   874   874 D BluetoothA2dp: Proxy object connected
09-13 11:57:09.741  3875  3887 D BluetoothPan: onBluetoothStateChange on: true
,09-13 11:57:09.742  1935  1949 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:09.742  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:09.742  1376  2213 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:57:09.743  3875  3885 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:57:09.744  1376  1388 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:57:09.745  1376  1376 D BluetoothMap: Proxy object connected
,09-13 11:57:09.745  1376  1376 D MapProfile: Bluetooth service connected
09-13 11:57:09.745  1376  1376 D BluetoothMap: getConnectedDevices()
09-13 11:57:09.745  3875  3887 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:09.745  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:57:09.745  1376  1394 D BluetoothPan: onBluetoothStateChange on: true
,09-13 11:57:09.746  1376  3611 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:57:09.747  1376  1376 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:57:09.747  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:09.747  1376  1376 D PanProfile: Bluetooth service connected
09-13 11:57:09.747  1376  1376 D BluetoothA2dp: Proxy object connected
,09-13 11:57:09.747   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:09.747   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:09.748   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 11:57:09.751  3875  3875 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 11:57:09.751  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:09.751  3978  3978 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 11:57:09.752  3978  3978 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 11:57:09.753  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:09.753  3875  3875 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-13 11:57:09.754  3978  3978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:57:09.756  3978  3978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:57:09.757  3978  3978 D ObexServerSockets: Succeed to create listening sockets 
,09-13 11:57:09.757  3978  3978 D ObexServerSockets0: startAccept()
09-13 11:57:09.757  3978  3978 D ObexServerSockets0: prepareForNewConnect()
,09-13 11:57:09.760  3978  3978 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 11:57:09.760  3978  4190 D ObexServerSockets0: Accepting socket connection...
09-13 11:57:09.760  3978  3978 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 11:57:09.760  3978  3978 D BluetoothMapService: onReceive
09-13 11:57:09.760  3978  3978 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:57:09.760  3978  3978 D BluetoothMapService: STATE_ON
09-13 11:57:09.761  3978  4191 D ObexServerSockets0: Accepting socket connection...
09-13 11:57:09.761  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 11:57:09.764  3875  3875 D BluetoothA2dp: Proxy object connected
09-13 11:57:09.768  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:57:09.776  1376  1376 D BluetoothPbap: Proxy object connected
09-13 11:57:09.776  1376  1376 D PbapServerProfile: Bluetooth service connected
,09-13 11:57:09.777  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:57:09.778  3875  3875 D BluetoothPbap: Proxy object connected
,09-13 11:57:09.778  3875  3875 D PbapServerProfile: Bluetooth service connected
,09-13 11:57:09.783  3978  4195 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:57:09.795  3978  3978 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 11:57:09.795  3978  3978 D ObexServerSockets0: prepareForNewConnect()
,09-13 11:57:09.799  3978  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:57:09.800  3978  4199 I BtOppRfcommListener: Accept thread started.
,09-13 11:57:09.841   874   874 D BluetoothHeadset: Proxy object connected
,09-13 11:57:09.842   874   874 D BluetoothHeadset: Proxy object connected
,09-13 11:57:09.842  1376  2213 D BluetoothHeadset: Proxy object connected
09-13 11:57:09.843  1376  1376 D HeadsetProfile: Bluetooth service connected
,09-13 11:57:09.843  1935  1950 D BluetoothHeadset: Proxy object connected
09-13 11:57:09.843   874   874 D BluetoothHeadset: Proxy object connected
,09-13 11:57:09.843  1935  2121 D BluetoothHeadset: Proxy object connected
,09-13 11:57:09.847   874   891 D BluetoothHeadset: Proxy object connected
,09-13 11:57:09.847   874   891 D BluetoothHeadset: Proxy object connected
,09-13 11:57:09.856  3875  3887 D BluetoothHeadset: Proxy object connected
09-13 11:57:09.857  3875  3875 D HeadsetProfile: Bluetooth service connected
,09-13 11:57:10.013   874  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=2a00:1450:4001:816::200e
,09-13 11:57:10.019   874  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: ENONET (Machine is not on the network)
,09-13 11:57:10.020   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 11:57:11.329   874  1318 D ConnectivityService: handlePromptUnvalidated 101
,09-13 11:57:11.360  3978  4161 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 11:57:11.361  3978  4161 D BluetoothAdapterProperties: Setting state to 13
,09-13 11:57:11.361  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 11:57:11.363  3978  4161 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 11:57:11.365  3978  4161 I BluetoothAdapterState: Entering PendingCommandState
09-13 11:57:11.369  3978  4165 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:57:11.370  3978  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 11:57:11.376  3978  3978 D BluetoothMapService: onReceive
09-13 11:57:11.376  3978  3978 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:57:11.376  3978  3978 D BluetoothMapService: STATE_TURNING_OFF
,09-13 11:57:11.376  3978  3978 D BluetoothMapService: MAP Service closeService in
,09-13 11:57:11.376  3978  3978 D BluetoothMapMasInstance0: MAP Service shutdown
,09-13 11:57:11.376  3978  3978 D ObexServerSockets0: shutdown(block = true)
,09-13 11:57:11.377  3978  3978 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 11:57:11.377  3978  4190 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 11:57:11.377  3978  3978 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 11:57:11.378  3978  4191 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 11:57:11.378  3978  4175 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-13 11:57:11.379  3978  3978 I BtOppRfcommListener: stopping Accept Thread
09-13 11:57:11.380  3978  4199 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 11:57:11.381  3978  4199 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 11:57:11.384  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:11.384  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:57:11.385  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 11:57:11.387  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:11.387  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:11.390  3978  3978 D HeadsetService: Received stop request...Stopping profile...
09-13 11:57:11.392  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:11.392  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:57:11.393  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 11:57:11.393  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:11.395  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:11.397  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:57:11.398  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:11.398   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 11:57:11.398   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 11:57:11.399  3875  3885 D BluetoothHeadset: Proxy object disconnected
09-13 11:57:11.400  1376  2213 D BluetoothHeadset: Proxy object disconnected
09-13 11:57:11.401   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 11:57:11.401  3875  3875 D HeadsetProfile: Bluetooth service disconnected
09-13 11:57:11.402  1935  2108 D BluetoothHeadset: Proxy object disconnected
09-13 11:57:11.403  1376  1376 D HeadsetProfile: Bluetooth service disconnected
,09-13 11:57:11.403  3978  3978 D A2dpService: Received stop request...Stopping profile...
09-13 11:57:11.405  3978  4182 D A2dpStateMachine: Exit Disconnected: -1
09-13 11:57:11.407   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 11:57:11.407  1376  1376 D BluetoothA2dp: Proxy object disconnected
,09-13 11:57:11.409  3978  3978 D HidService: Received stop request...Stopping profile...
,09-13 11:57:11.409  3978  3978 D HidService: Stopping Bluetooth HidService
,09-13 11:57:11.410  1376  1376 D BluetoothInputDevice: Proxy object disconnected
,09-13 11:57:11.410  1376  1376 D HidProfile: Bluetooth service disconnected
09-13 11:57:11.411  3875  3875 D BluetoothA2dp: Proxy object disconnected
09-13 11:57:11.411  3875  3875 D BluetoothInputDevice: Proxy object disconnected
09-13 11:57:11.411  3875  3875 D HidProfile: Bluetooth service disconnected
09-13 11:57:11.411  3978  3978 D HealthService: Received stop request...Stopping profile...
,09-13 11:57:11.414  3978  3978 D PanService: Received stop request...Stopping profile...
,09-13 11:57:11.416  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:57:11.416  1376  1376 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 11:57:11.416  1376  1376 D PanProfile: Bluetooth service disconnected
09-13 11:57:11.417  3978  3978 D BluetoothMapService: Received stop request...Stopping profile...
09-13 11:57:11.417  3978  3978 D BluetoothMapService: stop()
09-13 11:57:11.418  3978  3978 D BluetoothMapAppObserver: deinitObservers()
,09-13 11:57:11.418  3978  3978 D BluetoothMapAppObserver: removeReceiver()
,09-13 11:57:11.419  3978  3978 V BluetoothAdapterState: isTurningOff()=true
09-13 11:57:11.419  3978  3978 V BluetoothAdapterState: isTurningOn()=false
09-13 11:57:11.419  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:11.419  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:11.419  3875  3875 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 11:57:11.419  3875  3875 D PanProfile: Bluetooth service disconnected
09-13 11:57:11.420  3875  3875 D BluetoothMap: Proxy object disconnected
09-13 11:57:11.420  1376  1376 D BluetoothMap: Proxy object disconnected
09-13 11:57:11.420  3875  3875 D MapProfile: Bluetooth service disconnected
09-13 11:57:11.420  1376  1376 D MapProfile: Bluetooth service disconnected
09-13 11:57:11.420  3978  3978 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 11:57:11.420  3978  3978 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 11:57:11.420  3978  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:57:11.420  3978  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:57:11.421  3978  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 11:57:11.421  3978  3978 V BluetoothAdapterState: isTurningOff()=true
09-13 11:57:11.421  3978  3978 V BluetoothAdapterState: isTurningOn()=false
09-13 11:57:11.421  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:11.421  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:11.420  3978  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 11:57:11.422  3978  4165 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-13 11:57:11.422  3978  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 11:57:11.422  3978  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:57:11.422  3978  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:57:11.423  3978  4173 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:57:11.423  3978  4173 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 11:57:11.423  3978  4173 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 11:57:11.423  3978  4173 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 11:57:11.423  3978  3978 V BluetoothAdapterState: isTurningOff()=true
09-13 11:57:11.423  3978  3978 V BluetoothAdapterState: isTurningOn()=false
09-13 11:57:11.423  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:11.423  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:11.424  3978  3978 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 11:57:11.424  3978  4165 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 11:57:11.424  3978  3978 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 11:57:11.424  3978  3978 V BluetoothAdapterState: isTurningOff()=true
09-13 11:57:11.424  3978  3978 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:57:11.424  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:11.425  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:11.425  3978  3978 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 11:57:11.425  3978  4165 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 11:57:11.425  3978  3978 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 11:57:11.427  3978  3978 V BluetoothAdapterState: isTurningOff()=true
09-13 11:57:11.427  3978  3978 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:57:11.427  1376  1376 D BluetoothPbap: Proxy object disconnected
09-13 11:57:11.427  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:11.427  1376  1376 D PbapServerProfile: Bluetooth service disconnected
09-13 11:57:11.427  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:11.427  3978  3978 D BluetoothMapService: MAP Service closeService in
09-13 11:57:11.428  3978  3978 V BluetoothAdapterState: isTurningOff()=true
09-13 11:57:11.428  3978  3978 V BluetoothAdapterState: isTurningOn()=false
09-13 11:57:11.428  3875  3875 D BluetoothPbap: Proxy object disconnected
09-13 11:57:11.428  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:11.428  3875  3875 D PbapServerProfile: Bluetooth service disconnected
,09-13 11:57:11.428  3978  3978 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:11.428  3978  3978 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 11:57:11.428  3978  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 11:57:11.428  3978  4161 D BluetoothAdapterProperties: Setting state to 15
09-13 11:57:11.428  3978  3978 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 11:57:11.428  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 11:57:11.429  3978  4161 I BluetoothAdapterState: Entering BleOnState
,09-13 11:57:11.429  1376  2213 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 11:57:11.430  1376  1394 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:57:11.430   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:57:11.431  3978  3978 D BluetoothMapService: cleanup()
09-13 11:57:11.431  3978  3978 D BluetoothMapService: MAP Service closeService in
09-13 11:57:11.431  3875  3885 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 11:57:11.432   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:57:11.432  3875  4204 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 11:57:11.433  3875  3887 D BluetoothPan: onBluetoothStateChange on: false
09-13 11:57:11.434  1935  2142 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:57:11.435  1376  3611 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 11:57:11.435  3875  3885 D BluetoothMap: onBluetoothStateChange: up=false
09-13 11:57:11.436  1376  2213 D BluetoothMap: onBluetoothStateChange: up=false
,09-13 11:57:11.438  3875  4204 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 11:57:11.439  3875  3887 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:57:11.439  1376  1394 D BluetoothPan: onBluetoothStateChange on: false
,09-13 11:57:11.440  1376  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 11:57:11.440   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 11:57:11.440   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 11:57:11.440  3978  4161 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-13 11:57:11.441  3978  4161 D BluetoothAdapterProperties: Setting state to 16
09-13 11:57:11.441  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 11:57:11.442  3978  4161 D BluetoothAdapterProperties: onBleDisable
09-13 11:57:11.442  3978  4161 I BluetoothAdapterState: Entering PendingCommandState
09-13 11:57:11.443  3978  4162 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 11:57:11.443  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:11.444  3978  4173 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 11:57:11.444  3978  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 11:57:11.445  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:11.446  3978  4165 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:57:11.447  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:11.448  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 11:57:11.448  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:11.456  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:57:11.457  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:57:11.646  3978  4165 I bt_hci  : shut_down
,09-13 11:57:11.666  3978  4169 D bt_hwcfg: hw_epilog_process
,09-13 11:57:11.667  3978  4169 I bt_vendor: low_power_mode_cb
,09-13 11:57:11.681  3978  4169 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 11:57:11.681  3978  4169 I bt_vendor: epilog_cb
,09-13 11:57:11.682  3978  4169 I bt_hci  : epilog_finished_callback
,09-13 11:57:11.690  3978  4165 I bt_hci_h4: hal_close
,09-13 11:57:11.691  3978  4165 I bt_userial_vendor: device fd = 51 close
,09-13 11:57:11.806  3978  4162 D bt_stack_manager: event_shut_down_stack finished.
,09-13 11:57:11.807  3978  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 11:57:11.812  3978  4161 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 11:57:11.813  3978  3978 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 11:57:11.814  3978  3978 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 11:57:11.815  3978  3978 D BtGatt.GattService: stop()
,09-13 11:57:11.815  3978  3978 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 11:57:11.821  3978  3978 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:11.822  3978  3978 V BluetoothAdapterState: isTurningOn()=false
,09-13 11:57:11.822  3978  3978 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:57:11.823  3978  3978 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 11:57:11.823  3978  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 11:57:11.824  3978  4161 D BluetoothAdapterProperties: Setting state to 10
,09-13 11:57:11.825  3978  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 11:57:11.826  3978  4161 I BluetoothAdapterState: Entering OffState
09-13 11:57:11.828   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 11:57:11.863  3978  3978 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 11:57:11.863  3978  3978 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-13 11:57:11.864  3978  4162 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 11:57:11.873  3978  3978 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 11:57:11.874  3978  4162 D bt_stack_manager: event_clean_up_stack finished.
,09-13 11:57:11.878  3978  3978 I art     : System.exit called, status: 0
,09-13 11:57:11.878  3978  3978 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 11:57:11.936   874  2000 I ActivityManager: Process com.android.bluetooth (pid 3978) has died
,09-13 11:57:13.738  3515  3525 D Finsky  : [268] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-13 11:57:13.757  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:57:13.771  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:57:13.777  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:57:13.847  1550  1568 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-13 11:57:13.847  1550  1568 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-13 11:57:13.847  1550  1568 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:13.848  1550  1568 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:13.908  3515  3525 D Finsky  : [268] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-13 11:57:14.357  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:57:14.358  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:17.365  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:17.366  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3237d89 added. We now have 6 listener(s)
09-13 11:57:17.366  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:17.370  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:17.371  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@752618e added. We now have 7 listener(s)
,09-13 11:57:17.371  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:17.373  3806  3857 I System.out: IsBluetoothEnabled
,09-13 11:57:17.386  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:17.434   874   891 I ActivityManager: Start proc 4212:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 11:57:17.541  4212  4212 D AdapterServiceConfig: Adding HeadsetService
,09-13 11:57:17.541  4212  4212 D AdapterServiceConfig: Adding A2dpService
,09-13 11:57:17.541  4212  4212 D AdapterServiceConfig: Adding HidService
09-13 11:57:17.542  4212  4212 D AdapterServiceConfig: Adding HealthService
,09-13 11:57:17.542  4212  4212 D AdapterServiceConfig: Adding PanService
09-13 11:57:17.542  4212  4212 D AdapterServiceConfig: Adding GattService
,09-13 11:57:17.542  4212  4212 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 11:57:17.556  4212  4212 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 11:57:17.556   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b8ed1b6:true
,09-13 11:57:17.561  4212  4212 I bt_bluedroid: init
,09-13 11:57:17.562  4212  4224 I BluetoothAdapterState: Entering OffState
,09-13 11:57:17.568  4212  4225 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 11:57:17.569  4212  4225 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 11:57:17.569  4212  4225 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 11:57:17.570  4212  4225 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 11:57:17.572  4212  4212 I bt_bluedroid: get_profile_interface socket
,09-13 11:57:17.574  4212  4212 I bt_bluedroid: get_profile_interface sdp
,09-13 11:57:17.581  4212  4223 I bt_bluedroid: config_hci_snoop_log
,09-13 11:57:17.581  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:57:17.584   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 11:57:17.584  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:57:17.595  4212  4224 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 11:57:17.596  4212  4224 D BluetoothAdapterProperties: Setting state to 14
,09-13 11:57:17.596  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 11:57:17.601  4212  4224 D BluetoothBondStateMachine: make
,09-13 11:57:17.606  4212  4229 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 11:57:17.615  4212  4224 I BluetoothAdapterState: Entering PendingCommandState,
,09-13 11:57:17.618  4212  4212 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 11:57:17.626  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:17.628  4212  4212 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 11:57:17.629  4212  4212 D BtGatt.GattService: Received start request. Starting profile...
,09-13 11:57:17.630  4212  4212 D BtGatt.GattService: start()
09-13 11:57:17.630  4212  4212 I bt_bluedroid: get_profile_interface gatt
,09-13 11:57:17.632  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:17.633  4212  4212 D BtGatt.AdvertiseManager: advertise manager created
,09-13 11:57:17.643  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:17.644  4212  4212 V BluetoothAdapterState: isTurningOn()=false
09-13 11:57:17.644  4212  4212 V BluetoothAdapterState: isBleTurningOn()=true
09-13 11:57:17.644  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:17.644  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 11:57:17.644  4212  4224 I bt_bluedroid: enable
,09-13 11:57:17.645  4212  4225 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 11:57:17.646  4212  4225 I bt_hci  : start_up
,09-13 11:57:17.665  4212  4225 I bt_vendor: alloc value 0xb3a1d189
,09-13 11:57:17.665  4212  4225 I bt_vendor: init
09-13 11:57:17.665  4212  4225 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 11:57:17.666  4212  4225 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 11:57:17.777  4212  4225 D bt_hci  : start_up starting async portion
,09-13 11:57:17.778  4212  4232 I bt_hci  : event_finish_startup
,09-13 11:57:17.778  4212  4232 I bt_hci_h4: hal_open
09-13 11:57:17.779  4212  4232 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 11:57:17.787  4212  4232 I bt_userial_vendor: device fd = 51 open
,09-13 11:57:17.820  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:57:17.851  4212  4232 D bt_hwcfg: Chipset BCM4354A2
,09-13 11:57:17.852  4212  4232 D bt_hwcfg: Target name = [BCM4354A2]
09-13 11:57:17.853  4212  4232 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 11:57:18.523  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 11:57:18.524  4212  4232 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 11:57:18.526  4212  4232 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 11:57:18.643  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 11:57:18.644  4212  4232 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 11:57:18.672  4212  4232 I bt_hwcfg: vendor lib fwcfg completed
,09-13 11:57:18.672  4212  4232 I bt_vendor: firmware callback
,09-13 11:57:18.673  4212  4232 I bt_hci  : firmware_config_callback
,09-13 11:57:18.686  4212  4234 I bt_btu  : btu_task pending for preload complete event
,09-13 11:57:18.686  4212  4234 I bt_btu_task: Bluetooth chip preload is complete
,09-13 11:57:18.687  4212  4234 I bt_btu  : btu_task received preload complete event
,09-13 11:57:18.696  4212  4234 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 11:57:18.697  4212  4234 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 11:57:18.697  4212  4234 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 11:57:18.697  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 11:57:18.698  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 11:57:18.698  4212  4234 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 11:57:18.698  4212  4234 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 11:57:18.698  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 11:57:18.699  4212  4234 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 11:57:18.699  4212  4234 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 11:57:18.699  4212  4234 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 11:57:18.700  4212  4234 I         : BTE_InitTraceLevels -- TRC_GATT
,09-13 11:57:18.700  4212  4234 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 11:57:18.700  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 11:57:18.700  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 11:57:18.831  4212  4234 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb399ad9d
09-13 11:57:18.831  4212  4234 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb399ad9d 
,09-13 11:57:18.842  4212  4228 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 11:57:18.845  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 11:57:18.846  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 11:57:18.849  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 11:57:18.852  4212  4228 D BluetoothAdapterProperties: Scan Mode:20
,09-13 11:57:18.853  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 11:57:18.853  4212  4228 D bt_hci  : do_postload posting postload work item
09-13 11:57:18.853  4212  4232 I bt_hci  : event_postload
,09-13 11:57:18.854  4212  4232 I bt_vendor: sco_config_cb
,09-13 11:57:18.854  4212  4232 I bt_hci  : sco_config_callback postload finished.
09-13 11:57:18.856  4212  4228 D bt_bte_conf: Device ID record 1 : primary
09-13 11:57:18.856  4212  4228 D bt_bte_conf:   vendorId            = 000f
09-13 11:57:18.857  4212  4228 D bt_bte_conf:   vendorIdSource      = 0001
09-13 11:57:18.857  4212  4228 D bt_bte_conf:   product             = 1200
09-13 11:57:18.857  4212  4228 D bt_bte_conf:   version             = 1436
,09-13 11:57:18.858  4212  4228 D bt_bte_conf:   clientExecutableURL = 
09-13 11:57:18.858  4212  4228 D bt_bte_conf:   serviceDescription  = 
09-13 11:57:18.858  4212  4228 D bt_bte_conf:   documentationURL    = 
09-13 11:57:18.859  4212  4228 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 11:57:18.859  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:18.859  4212  4225 D bt_stack_manager: event_start_up_stack finished
09-13 11:57:18.862  4212  4232 I bt_vendor: low_power_mode_cb
,09-13 11:57:18.864  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 11:57:18.865  4212  4224 D BluetoothAdapterProperties: Setting state to 15
09-13 11:57:18.866  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 11:57:18.869  4212  4224 I BluetoothAdapterState: Entering BleOnState
,09-13 11:57:18.873  4212  4224 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 11:57:18.873  4212  4224 D BluetoothAdapterProperties: Setting state to 11
,09-13 11:57:18.873  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 11:57:18.878  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:18.886  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:18.887  4212  4212 D HeadsetService: Received start request. Starting profile...
,09-13 11:57:18.891  4212  4212 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 11:57:18.891  4212  4212 D HeadsetStateMachine: make
,09-13 11:57:18.897  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
,09-13 11:57:18.900  4212  4212 D HeadsetStateMachine: max_hf_connections = 1
,09-13 11:57:18.901  4212  4212 I bt_bluedroid: get_profile_interface handsfree
09-13 11:57:18.901  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 11:57:18.901  4212  4228 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-13 11:57:18.904  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:18.905  4212  4212 D A2dpService: Received start request. Starting profile...
09-13 11:57:18.906  4212  4212 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 11:57:18.906  4212  4212 I bt_bluedroid: get_profile_interface avrcp
,09-13 11:57:18.912  4212  4212 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 11:57:18.912  4212  4212 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 11:57:18.912  4212  4212 D A2dpStateMachine: make
,09-13 11:57:18.914  4212  4212 I bt_bluedroid: get_profile_interface a2dp
09-13 11:57:18.914  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 11:57:18.918  4212  4242 D A2dpStateMachine: Enter Disconnected: -2
09-13 11:57:18.918  4212  4212 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 11:57:18.919  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:57:18.919  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:57:18.919  4212  4212 D HidService: Received start request. Starting profile...
09-13 11:57:18.920  4212  4212 I bt_bluedroid: get_profile_interface hidhost
09-13 11:57:18.920  4212  4228 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397c3e5
09-13 11:57:18.920  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 11:57:18.920  4212  4212 D HidService: setHidService(): set to: null
09-13 11:57:18.921  4212  4212 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 11:57:18.921  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:57:18.922  4212  4212 D HealthService: Received start request. Starting profile...
,09-13 11:57:18.923  4212  4212 I bt_bluedroid: get_profile_interface health
,09-13 11:57:18.924  4212  4212 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 11:57:18.925  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:18.925  4212  4212 D PanService: Received start request. Starting profile...
09-13 11:57:18.926  4212  4212 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 11:57:18.926  4212  4212 I bt_bluedroid: get_profile_interface pan
,09-13 11:57:18.926  4212  4228 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 11:57:18.929  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
,09-13 11:57:18.930  4212  4212 D BluetoothMapService: Received start request. Starting profile...
09-13 11:57:18.930  4212  4212 D BluetoothMapService: start()
,09-13 11:57:18.933  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 11:57:18.934  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 11:57:18.935  4212  4212 D BluetoothMapAppObserver: createReceiver()
,09-13 11:57:18.937  4212  4212 D BluetoothMapAppObserver: initObservers()
,09-13 11:57:18.937  4212  4212 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 11:57:18.946  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:18.946  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:18.946  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:18.946  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:18.948  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:18.948  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:18.948  4212  4240 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 11:57:18.948  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:18.948  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:18.949  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-13 11:57:18.949  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:18.949  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:18.949  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 11:57:18.950  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-13 11:57:18.951  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-13 11:57:18.951  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-13 11:57:18.951  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-13 11:57:18.951  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 11:57:18.952  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 11:57:18.952  4212  4224 D BluetoothAdapterProperties: ScanMode =  20
09-13 11:57:18.952  4212  4224 D BluetoothAdapterProperties: State =  11
,09-13 11:57:18.954  4212  4228 D BluetoothAdapterProperties: Scan Mode:21
09-13 11:57:18.954  4212  4224 D BluetoothAdapterProperties: Setting state to 12
09-13 11:57:18.954  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 11:57:18.955  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 11:57:18.955  4212  4224 I BluetoothAdapterState: Entering OnState
09-13 11:57:18.955  1376  3611 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 11:57:18.957  1376  1394 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 11:57:18.957  1376  1376 D BluetoothInputDevice: Proxy object connected
,09-13 11:57:18.957  1376  1376 D HidProfile: Bluetooth service connected
09-13 11:57:18.957   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:18.958  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 11:57:18.958  3875  3887 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:57:18.960   874   874 D BluetoothA2dp: Proxy object connected
09-13 11:57:18.960  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 11:57:18.963   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:18.963  3875  3875 D BluetoothA2dp: Proxy object connected
09-13 11:57:18.964  3875  4204 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:57:18.965  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 11:57:18.965  3875  3885 D BluetoothPan: onBluetoothStateChange on: true
09-13 11:57:18.965  4212  4212 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 11:57:18.968  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 11:57:18.968  1935  2121 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:18.969  1376  3611 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 11:57:18.970  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:57:18.971  3875  3887 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:57:18.971  4212  4212 D ObexServerSockets: Succeed to create listening sockets 
09-13 11:57:18.972  4212  4212 D ObexServerSockets0: startAccept()
09-13 11:57:18.972  1376  2213 D BluetoothMap: onBluetoothStateChange: up=true
09-13 11:57:18.972  4212  4212 D ObexServerSockets0: prepareForNewConnect()
,09-13 11:57:18.975  3875  4204 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 11:57:18.975  4212  4212 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 11:57:18.976  4212  4212 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 11:57:18.977  4212  4249 D ObexServerSockets0: Accepting socket connection...
09-13 11:57:18.978  3875  3885 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:18.979  1376  1376 D BluetoothMap: Proxy object connected
09-13 11:57:18.979  1376  1376 D MapProfile: Bluetooth service connected
09-13 11:57:18.979  1376  1376 D BluetoothMap: getConnectedDevices()
09-13 11:57:18.979  1376  1394 D BluetoothPan: onBluetoothStateChange on: true
,09-13 11:57:18.979  4212  4250 D ObexServerSockets0: Accepting socket connection...
09-13 11:57:18.981  1376  1376 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:57:18.981  1376  2213 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 11:57:18.981  1376  1376 D PanProfile: Bluetooth service connected
09-13 11:57:18.983   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 11:57:18.983   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 11:57:18.983  1376  1376 D BluetoothA2dp: Proxy object connected
09-13 11:57:18.984   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 11:57:18.983  3875  3875 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 11:57:18.984  3875  3875 D PanProfile: Bluetooth service connected
09-13 11:57:18.984  3875  3875 D BluetoothInputDevice: Proxy object connected
,09-13 11:57:18.984  3875  3875 D HidProfile: Bluetooth service connected
09-13 11:57:18.985  4212  4212 D BluetoothMapService: onReceive
09-13 11:57:18.985  4212  4212 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 11:57:18.985  4212  4212 D BluetoothMapService: STATE_ON
,09-13 11:57:18.986  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:18.988  3875  3875 D BluetoothMap: Proxy object connected
09-13 11:57:18.989  3875  3875 D MapProfile: Bluetooth service connected
09-13 11:57:18.989  3875  3875 D BluetoothMap: getConnectedDevices()
,09-13 11:57:18.996  3875  3875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 11:57:19.003  1550  1550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 11:57:19.008  3875  3875 D DockEventReceiver: finishStartingService: stopping service
,09-13 11:57:19.014  1376  1376 D BluetoothPbap: Proxy object connected
,09-13 11:57:19.014  1376  1376 D PbapServerProfile: Bluetooth service connected
09-13 11:57:19.015  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 11:57:19.015  4212  4212 D ObexServerSockets0: prepareForNewConnect()
09-13 11:57:19.014  3875  3875 D BluetoothPbap: Proxy object connected
09-13 11:57:19.015  3875  3875 D PbapServerProfile: Bluetooth service connected
,09-13 11:57:19.022  4212  4256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:57:19.045  4212  4260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 11:57:19.046  4212  4260 I BtOppRfcommListener: Accept thread started.
,09-13 11:57:19.059   874   874 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.060   874   874 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.060  3875  3887 D BluetoothHeadset: Proxy object connected
09-13 11:57:19.060  3875  3875 D HeadsetProfile: Bluetooth service connected
09-13 11:57:19.060  1376  1394 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.061  1376  1376 D HeadsetProfile: Bluetooth service connected
,09-13 11:57:19.061   874   874 D BluetoothHeadset: Proxy object connected
09-13 11:57:19.061  1935  2108 D BluetoothHeadset: Proxy object connected
09-13 11:57:19.063   874   891 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.076  1935  2142 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.080  3875  4204 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.080  3875  3875 D HeadsetProfile: Bluetooth service connected
,09-13 11:57:19.083   874   891 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.083   874   891 D BluetoothHeadset: Proxy object connected
,09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:19.409  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:57:19.416  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:57:19.420  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:19.420  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a0fdaf added. We now have 8 listener(s)
09-13 11:57:19.421  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:19.427   874  2000 D WifiService: setWifiEnabled: false pid=3806, uid=10000
09-13 11:57:19.427   874  2000 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:57:19.440  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:19.441   874  1382 D WifiService: setWifiEnabled: true pid=3806, uid=10000
09-13 11:57:19.441   874  1382 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 11:57:19.456   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:19.475  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:57:19.480  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:57:19.488   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-13 11:57:19.488   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 11:57:19.490   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 11:57:19.491   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 11:57:19.492   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 11:57:19.492   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 11:57:19.492   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 11:57:19.507   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 11:57:19.507   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.53 rxSuccessRate=0.73 delta 1000 -> 1000
,09-13 11:57:19.509   373   872 D CommandListener: Setting iface cfg
,09-13 11:57:19.511   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-13 11:57:19.511   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 11:57:19.516   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 11:57:19.517   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:57:19.524   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 11:57:19.560   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 11:57:19.562   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 11:57:19.582   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 11:57:19.586  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 11:57:20.067  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 11:57:20.120  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 11:57:20.121  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 11:57:20.125   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:57:20.137   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 11:57:20.138   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 11:57:20.138   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 11:57:20.170   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 11:57:20.183   373   872 D CommandListener: Setting iface cfg
,09-13 11:57:20.185   874  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 11:57:20.203   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 11:57:20.204   874  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-13 11:57:20.211   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 11:57:20.261   874  4269 D DhcpClient: Receive thread started
,09-13 11:57:20.346   874  1316 E native  : do suspend false
,09-13 11:57:20.365   874  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 11:57:20.379   874  4269 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null,
09-13 11:57:20.380   874  1878 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-13 11:57:20.383   874  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 11:57:20.397   874  4269 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 11:57:20.398   874  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 11:57:20.403   373   872 D CommandListener: Setting iface cfg
,09-13 11:57:20.416   874  1878 D DhcpClient: Scheduling renewal in 86399s
,09-13 11:57:20.417   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 11:57:20.430   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 11:57:20.434   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 11:57:20.436   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 11:57:20.438   874  1318 D ConnectivityService: Adding iface wlan0 to network 102
,09-13 11:57:20.451   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 11:57:20.459  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 11:57:20.462  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 11:57:20.466  3806  3857 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 11:57:20.466  3806  3857 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 11:57:20.468  3806  3857 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@761cb91 Bundle[{}]
,09-13 11:57:20.469  3806  3857 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 11:57:20.469  3806  3857 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 11:57:20.470  3806  3857 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 11:57:20.470  3806  3857 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 11:57:20.471  3806  3857 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 11:57:20.472  3806  3857 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 11:57:20.478  3806  3857 I System.out: Running OutgoingSocketThread
,09-13 11:57:20.479  3806  4272 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 425)
,09-13 11:57:20.480  3806  4272 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39013
09-13 11:57:20.480  3806  4272 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 11:57:20.490   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 11:57:20.490   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-13 11:57:20.491   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 11:57:20.492   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 11:57:20.493   874  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 11:57:20.502   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 11:57:20.508   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-13 11:57:20.508   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-13 11:57:20.508   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-13 11:57:20.508   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 11:57:20.508   874  1318 D ConnectivityService:    accepting network in place of null
09-13 11:57:20.509   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 11:57:20.509   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 11:57:20.535   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 11:57:20.561   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 11:57:20.566   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-13 11:57:20.566   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:57:20.573   874   891 D Tethering: MasterInitialState.processMessage what=3
09-13 11:57:20.576   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:20.583  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:57:20.586  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:20.591  1755  1755 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 11:57:20.597  1755  1755 D SystemUpdateService: onCreate
,09-13 11:57:20.600  1755  1755 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 11:57:20.620  1755  4280 I SystemUpdateService: active receiver: enabled
,09-13 11:57:20.623  1755  1755 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 11:57:20.634  1755  4280 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 11:57:20.635  1755  1755 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 11:57:20.636  1755  1755 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 11:57:20.638  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 11:57:20.642  1755  4283 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 11:57:20.642  1755  4283 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 11:57:20.644  1755  4283 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 11:57:20.644  3994  3994 D SprintDMHelper: simOperator: 
,09-13 11:57:20.645  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-13 11:57:20.632  1755  2429 I iu.UploadsManager: num queued entries: 0
09-13 11:57:20.648  1755  2429 I iu.UploadsManager: num updated entries: 0
,09-13 11:57:20.650  1755  4280 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 11:57:20.652  1755  4280 I SystemUpdateService: now status is 0 (complete)
09-13 11:57:20.652  1755  4280 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 11:57:20.652  1755  4280 I SystemUpdateService: file has been verified
09-13 11:57:20.653  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:57:20.655  1755  4280 I SystemUpdateService: OTA package size = 12249756
09-13 11:57:20.657  1550  1550 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 11:57:20.661  1755  2429 I iu.SyncManager: NEXT; no task
,09-13 11:57:20.672  1755  4280 I SystemUpdateService: showing system update notification
,09-13 11:57:20.694  1755  1755 D SystemUpdateService: onDestroy
,09-13 11:57:20.715  1550  2295 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-13 11:57:20.715  1550  2295 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-13 11:57:20.715  1550  2295 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 11:57:20.716  1550  2295 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 11:57:20.731  1755  4283 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-13 11:57:21.196   874  4268 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149586, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 11:57:21.481  3806  3857 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 426)
,09-13 11:57:21.481  3806  3857 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 426)
,09-13 11:57:21.491  3806  3857 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,09-13 11:57:21.493  3806  3857 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 11:57:21.494  3806  3857 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 432)
,09-13 11:57:21.501  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:57:21.501  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3185bc added. We now have 2 listener(s)
09-13 11:57:21.503  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:57:21.503  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:57:21.503  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:57:21.503  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:21.503  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63d6945 added. We now have 9 listener(s)
09-13 11:57:21.503  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:57:21.504  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:57:21.508  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:21.522  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:57:21.526  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:57:21.526  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:57:21.527  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:57:21.527  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c09c5cb added. We now have 3 listener(s)
,09-13 11:57:21.530  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:21.531  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:57:21.532  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:57:21.532  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:57:21.533  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:21.533  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:57:21.533  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f41a8 added. We now have 10 listener(s)
,09-13 11:57:21.533  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:21.535  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 11:57:21.535  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:57:21.535  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:57:21.536  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:57:21.536  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.536  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:57:21.537  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 11:57:21.538  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3185bc removed from the list
09-13 11:57:21.538  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:57:21.538  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63d6945 removed from the list
09-13 11:57:21.538  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:57:21.539  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.540  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.540  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.541  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:57:21.541  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.541  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.541  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63d6945 not in the list
,09-13 11:57:21.541  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.541  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:57:21.542  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.542  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:57:21.543  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.543  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f41a8 removed from the list
,09-13 11:57:21.543  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:57:21.543  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.543  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.543  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:57:21.543  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c09c5cb removed from the list
,09-13 11:57:21.544  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:57:21.544  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55054c1 added. We now have 2 listener(s)
,09-13 11:57:21.546  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:57:21.546  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:57:21.546  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:57:21.546  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:21.546  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4d1466 added. We now have 9 listener(s)
09-13 11:57:21.546  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:57:21.547  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:57:21.550  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:21.556  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:57:21.561  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:57:21.561  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:57:21.562  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:57:21.562  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94ad054 added. We now have 3 listener(s)
09-13 11:57:21.564  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:21.565  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:57:21.565  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:57:21.565  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:57:21.565  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:21.565  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54c7bfd added. We now have 10 listener(s)
09-13 11:57:21.566  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:21.566   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-13 11:57:21.566  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:57:21.566  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 11:57:21.566  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:21.566  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 11:57:21.566  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:57:21.566  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:57:21.571  3806  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 11:57:21.571  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:57:21.575  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 11:57:21.576  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 11:57:21.576  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:57:21.579  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 11:57:21.579  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:57:21.579  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 11:57:21.580  3806  3857 D BluetoothAdapter: STATE_ON
,09-13 11:57:21.583  4212  4251 D BtGatt.GattService: registerClient() - UUID=f88264cf-0e08-435d-8221-ee3fde9f6002
,09-13 11:57:21.584  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=f88264cf-0e08-435d-8221-ee3fde9f6002, clientIf=5
,09-13 11:57:21.584  3806  3818 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 11:57:21.585  4212  4252 D BtGatt.GattService: start scan with filters
,09-13 11:57:21.589  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 11:57:21.589  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 11:57:21.590  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 11:57:21.590  4212  4231 D BtGatt.ScanManager: handling starting scan
09-13 11:57:21.590  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 11:57:21.591  4212  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa61315
09-13 11:57:21.593  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:57:21.593  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 11:57:21.593  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:57:21.595  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:57:21.598  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 11:57:21.598  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.599  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 11:57:21.599  3806  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 11:57:21.599  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 11:57:21.599  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 11:57:21.599  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.599  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:57:21.599  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 11:57:21.599  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 11:57:21.599  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:57:21.599  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:57:21.600  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 11:57:21.600  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 11:57:21.601  3806  3857 D BluetoothAdapter: STATE_ON
09-13 11:57:21.601  4212  4251 D BtGatt.GattService: stopScan() - queue size =1
,09-13 11:57:21.602  4212  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 11:57:21.603  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:57:21.603  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:57:21.603  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:57:21.603  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:57:21.604  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 11:57:21.606  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:57:21.606  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.606  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:57:21.606  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 11:57:21.606  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 11:57:21.606  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:57:21.606  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 11:57:21.606  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:57:21.607  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:57:21.608  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:57:21.609  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:57:21.609  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:57:21.612  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:57:21.612  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:57:21.613  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 11:57:21.613  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:57:21.613  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.613  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:57:21.613  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:57:21.613  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55054c1 removed from the list
09-13 11:57:21.613  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.613  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4d1466 removed from the list
09-13 11:57:21.613  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:57:21.613  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:57:21.614  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.614  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.615  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:57:21.615  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.615  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.616  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4d1466 not in the list
09-13 11:57:21.616  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.616  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:57:21.617  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.617  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:57:21.617  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.617  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54c7bfd removed from the list
09-13 11:57:21.617  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:57:21.618  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.618  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:57:21.618  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:57:21.618  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94ad054 removed from the list
,09-13 11:57:21.619  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 11:57:21.619  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.619  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:57:21.619  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe9daf9 added. We now have 2 listener(s)
09-13 11:57:21.622  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:57:21.622  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:57:21.622  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:57:21.622  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:57:21.622  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce04a3e added. We now have 9 listener(s)
09-13 11:57:21.622  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:57:21.623  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 11:57:21.626  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 11:57:21.626  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.627  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:21.634  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:57:21.635  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 11:57:21.635  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.635  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
,09-13 11:57:21.636  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:21.637  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:57:21.637  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:57:21.637  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbfd5ec added. We now have 3 listener(s)
09-13 11:57:21.640  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 11:57:21.640  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:57:21.640  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:57:21.640  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:57:21.640  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8642db5 added. We now have 10 listener(s)
09-13 11:57:21.640  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:21.640  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:57:21.641  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:21.642  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 11:57:21.642  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 11:57:21.642  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 11:57:21.642  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:57:21.642  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 11:57:21.643  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 11:57:21.643  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.643  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:21.644  3806  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 11:57:21.644  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:57:21.644  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:57:21.648  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 11:57:21.649  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 11:57:21.649  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:57:21.652  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 11:57:21.653  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 11:57:21.653  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:57:21.653  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 11:57:21.653  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.655  3806  3857 D BluetoothAdapter: STATE_ON
,09-13 11:57:21.657  4212  4248 D BtGatt.GattService: registerClient() - UUID=680215bd-c23f-4e65-ab98-3044ac27876a
,09-13 11:57:21.657  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=680215bd-c23f-4e65-ab98-3044ac27876a, clientIf=5
09-13 11:57:21.658  3806  3818 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 11:57:21.658  4212  4247 D BtGatt.GattService: start scan with filters
,09-13 11:57:21.660  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 11:57:21.660  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 11:57:21.660  4212  4231 D BtGatt.ScanManager: handling starting scan
09-13 11:57:21.660  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 11:57:21.660  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 11:57:21.663  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:57:21.664  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 11:57:21.664  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 11:57:21.665  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:57:21.667  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 11:57:21.667  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.667  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 11:57:21.672  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:57:21.673  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.672  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 11:57:21.673  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:57:21.673  3806  3857 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 11:57:21.673  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 11:57:21.673  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:57:21.674  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:57:21.674  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:57:21.675  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:57:21.676  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.677  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 11:57:21.677  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 11:57:21.680  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe9daf9 removed from the list
,09-13 11:57:21.680  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:57:21.682  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce04a3e removed from the list
,09-13 11:57:21.683  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:57:21.683  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:57:21.683  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.683  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-13 11:57:21.683  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.683  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 11:57:21.684  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:57:21.684  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.684  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.685  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce04a3e not in the list
,09-13 11:57:21.685  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:57:21.685  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 11:57:21.685  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 11:57:21.685  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:57:21.685  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 11:57:21.685  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 11:57:21.685  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.686  3806  3857 D BluetoothAdapter: STATE_ON
09-13 11:57:21.687  4212  4247 D BtGatt.GattService: stopScan() - queue size =1
09-13 11:57:21.688  4212  4251 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 11:57:21.688  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:57:21.688  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:57:21.688  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 11:57:21.688  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:57:21.688  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 11:57:21.689  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:57:21.689  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 11:57:21.689  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:57:21.689  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:57:21.690  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.691  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.691  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:57:21.691  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.691  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:57:21.691  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8642db5 removed from the list
09-13 11:57:21.691  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:57:21.691  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:57:21.691  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.691  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 11:57:21.691  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.691  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:57:21.691  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbfd5ec removed from the list
,09-13 11:57:21.692  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 11:57:21.692  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.692  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:57:21.692  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6f031 added. We now have 2 listener(s)
09-13 11:57:21.694  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
09-13 11:57:21.694  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:57:21.694  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:57:21.694  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:21.694  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@396316 added. We now have 9 listener(s)
09-13 11:57:21.695  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:21.696  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:57:21.698  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:57:21.702  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 11:57:21.702  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.702  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
,09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:21.704  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:57:21.706  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:57:21.706  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 11:57:21.706  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 11:57:21.706  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecf684 added. We now have 3 listener(s)
,09-13 11:57:21.708  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:57:21.708  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:57:21.708  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:57:21.708  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:21.709  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6195e6d added. We now have 10 listener(s)
,09-13 11:57:21.709  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:21.709  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 11:57:21.709  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.709  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 11:57:21.709  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 11:57:21.710  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 11:57:21.710  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:21.710  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 11:57:21.710  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 11:57:21.710  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 11:57:21.712  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:21.713  3806  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 11:57:21.713  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 11:57:21.716  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 11:57:21.716  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.717  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 11:57:21.718  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-13 11:57:21.718  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 11:57:21.720  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 11:57:21.720  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 11:57:21.720  3806  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 11:57:21.721  3806  3857 D BluetoothAdapter: STATE_ON
,09-13 11:57:21.722  4212  4248 D BtGatt.GattService: registerClient() - UUID=ce7564fc-a51c-4dd3-996e-4456829091f4
,09-13 11:57:21.723  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=ce7564fc-a51c-4dd3-996e-4456829091f4, clientIf=5
,09-13 11:57:21.723  3806  3818 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 11:57:21.723  4212  4247 D BtGatt.GattService: start scan with filters
,09-13 11:57:21.725  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 11:57:21.725  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 11:57:21.726  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 11:57:21.726  4212  4231 D BtGatt.ScanManager: handling starting scan
09-13 11:57:21.726  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-13 11:57:21.728  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:57:21.728  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 11:57:21.728  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 11:57:21.730  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 11:57:21.732  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 11:57:21.732  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.733  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 11:57:21.736  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:57:21.736  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 11:57:21.736  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:57:21.736  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 11:57:21.736  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.736  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 11:57:21.736  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:57:21.736  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6f031 removed from the list
09-13 11:57:21.737  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.737  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@396316 removed from the list
,09-13 11:57:21.737  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 11:57:21.737  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:57:21.737  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.737  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-13 11:57:21.737  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.737  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:57:21.738  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 11:57:21.738  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:57:21.738  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.739  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
09-13 11:57:21.739  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-13 11:57:21.738  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.739  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.739  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@396316 not in the list
,09-13 11:57:21.739  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 11:57:21.739  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 11:57:21.739  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 11:57:21.739  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 11:57:21.739  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 11:57:21.741  3806  3857 D BluetoothAdapter: STATE_ON
09-13 11:57:21.742  4212  4252 D BtGatt.GattService: stopScan() - queue size =1
,09-13 11:57:21.743  4212  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 11:57:21.743  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 11:57:21.743  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 11:57:21.743  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 11:57:21.744  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 11:57:21.744  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 11:57:21.745  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 11:57:21.745  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 11:57:21.745  3806  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 11:57:21.745  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 11:57:21.745  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.747  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 11:57:21.747  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 11:57:21.747  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 11:57:21.747  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.747  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:57:21.747  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 11:57:21.747  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6195e6d removed from the list
,09-13 11:57:21.747  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:57:21.748  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.748  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.748  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 11:57:21.748  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecf684 removed from the list
,09-13 11:57:21.749  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 11:57:21.749  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a7469 added. We now have 2 listener(s)
09-13 11:57:21.750  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 11:57:21.750  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.751  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:57:21.752  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 11:57:21.752  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 11:57:21.752  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 11:57:21.752  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d1beee added. We now have 9 listener(s)
,09-13 11:57:21.752  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 11:57:21.753  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 11:57:21.755  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 11:57:21.757  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 11:57:21.757  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 11:57:21.759  3806  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 11:57:21.761  3806  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 11:57:21.761  3806  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 11:57:21.761  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-13 11:57:21.761  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a921c added. We now have 3 listener(s)
,09-13 11:57:21.763  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 11:57:21.763  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 11:57:21.764  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 11:57:21.764  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 11:57:21.764  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 11:57:21.764  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 11:57:21.764  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
09-13 11:57:21.764  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 11:57:21.764  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bcee25 added. We now have 10 listener(s)
,09-13 11:57:21.764  3806  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 11:57:21.765  3806  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 11:57:21.765  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 11:57:21.765  3806  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 11:57:21.765  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:57:21.765  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.765  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 11:57:21.765  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 11:57:21.765  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a7469 removed from the list
,09-13 11:57:21.765  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 11:57:21.766  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d1beee removed from the list
,09-13 11:57:21.766  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 11:57:21.766  3806  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 11:57:21.766  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 11:57:21.766  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.766  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.767  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 11:57:21.767  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 11:57:21.767  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 11:57:21.767  3806  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d1beee not in the list
,09-13 11:57:21.767  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 11:57:21.768  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 11:57:21.768  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 11:57:21.769  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 11:57:21.769  3806  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 11:57:21.769  3806  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bcee25 removed from the list
,09-13 11:57:21.769  3806  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 11:57:21.769  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 11:57:21.769  3806  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 11:57:21.769  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.769  3806  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 11:57:21.769  3806  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 11:57:21.769  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 11:57:21.769  3806  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a921c removed from the list
,09-13 11:57:21.770  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-13 11:57:21.770  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 11:57:21.770  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 11:57:21.771  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 11:57:21.771  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 11:57:21.771  3806  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 11:57:21.774  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 11:57:21.774  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 11:57:21.777  3806  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,09-13 11:57:21.777  3806  4290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
09-13 11:57:21.778  3806  4290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-13 11:57:21.779  3806  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
,09-13 11:57:21.786  3806  4291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: My test thread name)
09-13 11:57:21.786  3806  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 11:57:21.788  3806  3857 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-13 11:57:21.788  3806  3857 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-13 11:57:21.788  3806  3857 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 11:57:21.788  3806  3857 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 11:57:21.788  3806  3857 D com.test.thalitest.ThaliTestRunner: Total duration: 22785 ms
,09-13 11:57:21.790  3806  3857 I jxcore-log: *Native tests were executed*
09-13 11:57:21.790  3806  3857 I jxcore-log: 
,09-13 11:57:21.791  3806  3857 I jxcore-log: Total number of executed tests:  80
09-13 11:57:21.791  3806  3857 I jxcore-log: 
09-13 11:57:21.791  3806  3857 I jxcore-log: Number of passed tests:  80
09-13 11:57:21.791  3806  3857 I jxcore-log: 
09-13 11:57:21.791  3806  3857 I jxcore-log: Number of failed tests:  0
09-13 11:57:21.791  3806  3857 I jxcore-log: 
,09-13 11:57:21.791  3806  3857 I jxcore-log: Number of ignored tests:  0
09-13 11:57:21.791  3806  3857 I jxcore-log: 
,09-13 11:57:21.792  3806  3857 I jxcore-log: Total duration:  22785
09-13 11:57:21.792  3806  3857 I jxcore-log: 
09-13 11:57:21.792  3806  3857 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 11:57:21.792  3806  3857 I jxcore-log: 
,09-13 11:57:21.796  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.796  3806  3857 I jxcore-log: 
09-13 11:57:21.799  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.799  3806  3857 I jxcore-log: 
09-13 11:57:21.800  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.800  3806  3857 I jxcore-log: 
,09-13 11:57:21.801  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.801  3806  3857 I jxcore-log: 
09-13 11:57:21.802  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.802  3806  3857 I jxcore-log: 
09-13 11:57:21.803  3806  3806 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 11:57:21.804  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.804  3806  3857 I jxcore-log: 
,09-13 11:57:21.806  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.806  3806  3857 I jxcore-log: 
,09-13 11:57:21.808  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.808  3806  3857 I jxcore-log: 
09-13 11:57:21.808   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
09-13 11:57:21.808  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.808  3806  3857 I jxcore-log: 
,09-13 11:57:21.810  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:57:21.810  3806  3857 I jxcore-log: 
,09-13 11:57:21.811  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-13 11:57:21.812  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:57:21.812  3806  3857 I jxcore-log: 
,09-13 11:57:21.813  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 11:57:21.813  3806  3857 I jxcore-log: 
,09-13 11:57:21.814  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.814  3806  3857 I jxcore-log: 
,09-13 11:57:21.814  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.814  3806  3857 I jxcore-log: 
,09-13 11:57:21.815  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.815  3806  3857 I jxcore-log: 
,09-13 11:57:21.816  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.816  3806  3857 I jxcore-log: 
,09-13 11:57:21.817  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.817  3806  3857 I jxcore-log: 
,09-13 11:57:21.817  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.817  3806  3857 I jxcore-log: 
,09-13 11:57:21.818  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.818  3806  3857 I jxcore-log: 
,09-13 11:57:21.818  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.818  3806  3857 I jxcore-log: 
,09-13 11:57:21.819  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.819  3806  3857 I jxcore-log: 
,09-13 11:57:21.820  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 11:57:21.820  3806  3857 I jxcore-log: 
,09-13 11:57:21.820  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 11:57:21.820  3806  3857 I jxcore-log: 
,09-13 11:57:21.821  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 11:57:21.821  3806  3857 I jxcore-log: 
,09-13 11:57:21.822  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.822  3806  3857 I jxcore-log: 
,09-13 11:57:21.823   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 11:57:21.823   874   894 I Adreno  : Build Date                       : 10/20/15
09-13 11:57:21.823   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 11:57:21.823   874   894 I Adreno  : Local Branch                     : M14
09-13 11:57:21.823   874   894 I Adreno  : Remote Branch                    : 
09-13 11:57:21.823   874   894 I Adreno  : Remote Branch                    : 
09-13 11:57:21.823   874   894 I Adreno  : Reconstruct Branch               : 
09-13 11:57:21.827  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.827  3806  3857 I jxcore-log: 
09-13 11:57:21.828  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.828  3806  3857 I jxcore-log: 
09-13 11:57:21.828  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.828  3806  3857 I jxcore-log: 
09-13 11:57:21.829  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.829  3806  3857 I jxcore-log: 
09-13 11:57:21.830  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 11:57:21.830  3806  3857 I jxcore-log: 
,09-13 11:57:21.849   281  1330 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (225 us)
,09-13 11:57:21.960   874  4267 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 11:57:22.110  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:57:22.112  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:57:22.112  3806  3857 I jxcore-log: 
,09-13 11:57:22.192  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:57:22.194  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:57:22.194  3806  3857 I jxcore-log: 
,09-13 11:57:22.247  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 11:57:22.248  3806  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 11:57:22.248  3806  3857 I jxcore-log: 
,09-13 11:57:22.410  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 11:57:22.410  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 11:57:22.433   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 11:57:22.434  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@761cb91 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@49edbfa, 16908290=android.view.AbsSavedState$1@49edbfa}, android:focusedViewId=100}]}]
09-13 11:57:22.434  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-13 11:57:22.434  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 11:57:22.436  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-13 11:57:22.442   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 11:57:22.449   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 11:57:22.456   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-13 11:57:22.456   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 11:57:22.539  4292  4292 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 11:57:22.543  4292  4292 D AndroidRuntime: CheckJNI is OFF
,09-13 11:57:22.584  4292  4292 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 11:57:22.630  4292  4292 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 11:57:22.652  4292  4292 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 11:57:22.663   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 11:57:22.664   874   887 I ActivityManager: Killing 3806:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 11:57:22.686   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 11:57:22.690   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 11:57:22.690   874  1345 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,09-13 11:57:22.768   874   897 W PackageSettings: Skipping PackageSetting{9e0b9ee com.example.hello/10273} due to missing metadata
,09-13 11:57:22.792   874  1317 D WifiService: Client connection lost with reason: 4
,09-13 11:57:22.794   874  2006 D GraphicsStats: Buffer count: 2
,09-13 11:57:22.794   874  2033 I WindowState: WIN DEATH: Window{fd61a1f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 11:57:22.800   874   897 I art     : Starting a blocking GC Explicit
,09-13 11:57:22.810   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-13 11:57:22.811   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-13 11:57:22.812   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-13 11:57:22.812   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 11:57:22.812   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:22.812   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:22.812   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 11:57:22.812   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 11:57:22.815   874   887 I ActivityManager:   Force finishing activity ActivityRecord{d658374 u0 com.test.thalitest/.MainActivity t4}
,09-13 11:57:22.822   874  2032 W ActivityManager: Spurious death for ProcessRecord{35bf799 0:com.test.thalitest/u0a0}, curProc for 3806: null
09-13 11:57:22.822   874   894 I DreamManagerService: Entering dreamland.
09-13 11:57:22.822   874   894 I PowerManagerService: Dozing...
,09-13 11:57:22.822   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 11:57:22.860   377  1289 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-13 11:57:22.861   377  1289 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 11:57:22.868  1921  4305 D NfcService: Discovery configuration equal, not updating.
,09-13 11:57:22.870   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:57:22.878   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 11:57:22.880   874  1316 E native  : do suspend false
,09-13 11:57:22.885   874   897 I art     : Explicit concurrent mark sweep GC freed 14891(1010KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.673ms total 84.507ms
,09-13 11:57:22.896   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 11:57:22.901   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 11:57:22.903   874  1316 E native  : do suspend true,
,09-13 11:57:22.920   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 11:57:22.923  4292  4292 I art     : System.exit called, status: 0
09-13 11:57:22.923  4292  4292 I AndroidRuntime: VM exiting with result code 0.
,09-13 11:57:22.929   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 11:57:22.947   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 11:57:22.953   874  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 11:57:22.953  1881  1881 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-13 11:57:22.955  4212  4212 D BluetoothMapAppObserver: onReceive
,09-13 11:57:22.955  4212  4212 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-13 11:57:22.958  2148  2311 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 11:57:22.962  3676  3676 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 11:57:22.980  1881  4309 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 11:57:22.990  1935  1935 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 11:57:23.003   874  2000 I ActivityManager: Start proc 4311:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 11:57:23.004   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-13 11:57:23.004   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 11:57:23.005  1881  4309 I Decoder : createOrResetDecoder
,09-13 11:57:23.035  1550  1550 I ConfigService: onCreate
,09-13 11:57:23.048  1881  4309 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 11:57:23.057  4311  4311 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 11:57:23.074   874   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3806 uid 10000
,09-13 11:57:23.076  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-13 11:57:23.100  1881  4309 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-13 11:57:23.101   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 11:57:23.104  1881  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-13 11:57:23.104  1881  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-13 11:57:23.110  1881  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-13 11:57:23.110  1881  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 11:57:23.110  1881  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-13 11:57:23.110  1881  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-13 11:57:23.111  1881  4309 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 11:57:23.111  1881  4309 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-13 11:57:23.111  1881  4309 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 11:57:23.111  1881  4309 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 11:57:23.111  1881  4309 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 11:57:23.111  1881  4309 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-13 11:57:23.115  1951  2036 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-13 11:57:23.115  4311  4311 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-13 11:57:23.117   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-13 11:57:23.117   874   886 E PackageManager: Failed to write settings, restoring backup
09-13 11:57:23.117   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 11:57:23.117   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 11:57:23.117   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 11:57:23.117   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 11:57:23.117   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 11:57:23.117   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.117   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.117   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 11:57:23.121   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-13 11:57:23.121   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 11:57:23.121   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.121   874   887 E DropBoxManagerService: 	... 13 more
,09-13 11:57:23.124   874  1344 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
09-13 11:57:23.124   874  1344 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-13 11:57:23.124   874  1344 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-13 11:57:23.124   874  1344 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
,09-13 11:57:23.124   874  1344 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
09-13 11:57:23.124   874  1344 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
09-13 11:57:23.124   874  1344 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
,09-13 11:57:23.124   874  1344 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,09-13 11:57:23.126   874  1344 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
,09-13 11:57:23.126   874  1344 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-13 11:57:23.126   874  1344 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,09-13 11:57:23.127   874  1344 W System.err: 	... 4 more
09-13 11:57:23.127   874  1344 D skia    : ------- write threw an exception
09-13 11:57:23.127   874  2000 I ActivityManager: Start proc 4329:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-13 11:57:23.128  1951  2036 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 11:57:23.128  1951  2036 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1951
09-13 11:57:23.128  1951  2036 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.128  1951  2036 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 11:57:23.133   874  2034 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 11:57:23.134   874  4340 E DropBoxManagerService: Can't write: system_app_crash
09-13 11:57:23.134   874  4340 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.134   874  4340 E DropBoxManagerService: 	... 5 more
09-13 11:57:23.138  1951  2036 I Process : Sending signal. PID: 1951 SIG: 9
09-13 11:57:23.140   874  2000 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{ba9dca6 u-1 android.intent.action.SCREEN_OFF} to ReceiverList{6eea2cd 1951 com.google.android.googlequicksearchbox/10028/u0 remote:4351064}: process crashing
,09-13 11:57:23.150  4311  4326 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.150  4311  4326 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.150  4311  4326 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 11:57:23.160   874  2006 I ActivityManager: Start proc 4346:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-13 11:57:23.181  4311  4344 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 11:57:23.204   874  2034 D GraphicsStats: Buffer count: 1
,09-13 11:57:23.204   874  2006 I WindowState: WIN DEATH: Window{bb6e9f7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-13 11:57:23.215   874  1684 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1951) has died
,09-13 11:57:23.216   874  1684 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-13 11:57:23.217   874  1684 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 11:57:23.221  4346  4346 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-13 11:57:23.232   874   887 I ActivityManager: Start proc 4360:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 11:57:23.246  1550  1550 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-13 11:57:23.246  1550  1550 D AndroidRuntime: Shutting down VM
09-13 11:57:23.247  1550  1550 E AndroidRuntime: FATAL EXCEPTION: main,
09-13 11:57:23.247  1550  1550 E AndroidRuntime: Process: com.google.process.gapps, PID: 1550
09-13 11:57:23.247  1550  1550 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 11:57:23.247  1550  1550 E AndroidRuntime: 	... 8 more
09-13 11:57:23.256   874  4374 E DropBoxManagerService: Can't write: system_app_crash
09-13 11:57:23.256   874  4374 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:,186)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.256   874  4374 E DropBoxManagerService: 	... 5 more
09-13 11:57:23.256  1550  1550 I Process : Sending signal. PID: 1550 SIG: 9
,09-13 11:57:23.281  4360  4360 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:57:23.281  4360  4360 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 11:57:23.281  4360  4360 D AndroidRuntime: Shutting down VM
,09-13 11:57:23.288  4360  4360 E AndroidRuntime: FATAL EXCEPTION: main
09-13 11:57:23.288  4360  4360 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4360
09-13 11:57:23.288  4360  4360 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 11:57:23.288  4360  4360 E AndroidRuntime: 	... 10 more
,09-13 11:57:23.290   874  2033 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 11:57:23.290  4360  4360 I Process : Sending signal. PID: 4360 SIG: 9
09-13 11:57:23.290   874  4377 E DropBoxManagerService: Can't write: system_app_crash
,09-13 11:57:23.290   874  4377 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.290   874  4377 E DropBoxManagerService: 	... 5 more
,09-13 11:57:23.305   874  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 15 -> obsolete
,09-13 11:57:23.306  4311  4326 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-13 11:57:23.311  4311  4344 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.311  4311  4344 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 11:57:23.311  4311  4344 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 11:57:23.311  4311  4344 E AndroidRuntime: Process: android.process.acore, PID: 4311
09-13 11:57:23.311  4311  4344 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.311  4311  4344 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 11:57:23.314   874  1317 D WifiService: Client connection lost with reason: 4
,09-13 11:57:23.315   874  4378 E DropBoxManagerService: Can't write: system_app_crash
09-13 11:57:23.315   874  4378 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.315   874  4378 E DropBoxManagerService: 	... 5 more
,09-13 11:57:23.315  1755  4375 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@31037b5
09-13 11:57:23.319   874   884 I ActivityManager: Process com.google.process.gapps (pid 1550) has died
,09-13 11:57:23.319   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-13 11:57:23.319   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
09-13 11:57:23.319   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
,09-13 11:57:23.319   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,09-13 11:57:23.326  1755  1755 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-13 11:57:23.327  4311  4344 I Process : Sending signal. PID: 4311 SIG: 9
,09-13 11:57:23.343   874  2000 I ActivityManager: Start proc 4380:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-13 11:57:23.344   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4360) has died
,09-13 11:57:23.346   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 11:57:23.362   874   887 I ActivityManager: Start proc 4393:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 11:57:23.368   874  2034 I ActivityManager: Process android.process.acore (pid 4311) has died
,09-13 11:57:23.368   874  2034 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30951ms
,09-13 11:57:23.386  4380  4380 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-13 11:57:23.388  1755  1755 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-13 11:57:23.389  1755  1755 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-13 11:57:23.393  4380  4380 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.,
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
,09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:57:23.396  4380  4380 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:57:23.397  4380  4380 D AndroidRuntime: Shutting down VM,
09-13 11:57:23.397  1755  1755 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-13 11:57:23.397  1755  1755 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-13 11:57:23.398  4380  4380 E AndroidRuntime: FATAL EXCEPTION: main
09-13 11:57:23.398  4380  4380 E AndroidRuntime: Process: com.google.process.gapps, PID: 4380
09-13 11:57:23.398  4380  4380 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 11:57:23.398  4380  4380 E AndroidRuntime: 	... 10 more
,09-13 11:57:23.402  4380  4380 I Process : Sending signal. PID: 4380 SIG: 9
09-13 11:57:23.404   874  4408 E DropBoxManagerService: Can't write: system_app_crash
09-13 11:57:23.404   874  4408 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.404   874  4408 E DropBoxManagerService: 	... 5 more
,09-13 11:57:23.411  4393  4393 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:57:23.411  4393  4393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 11:57:23.411  4393  4393 D AndroidRuntime: Shutting down VM
,09-13 11:57:23.413  1755  4407 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-13 11:57:23.420  4393  4393 E AndroidRuntime: FATAL EXCEPTION: main
09-13 11:57:23.420  4393  4393 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4393
09-13 11:57:23.420  4393  4393 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 11:57:23.420  4393  4393 E AndroidRuntime: 	... 10 more
09-13 11:57:23.421   874  1684 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 11:57:23.419  2017  4406 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 11:57:23.429  1755  4407 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-13 11:57:23.429  1755  4407 E AndroidRuntime: Process: com.google.android.gms, PID: 1755
09-13 11:57:23.429  1755  4407 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 11:57:23.429  1755  4407 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: Can't write: system_app_crash
09-13 11:57:23.429   874  4410 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at, libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.429   874  4410 E DropBoxManagerService: 	... 5 more
,09-13 11:57:23.434   874   887 I ActivityManager: Start proc 4411:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,09-13 11:57:23.442   874  3991 I ActivityManager: Process com.google.process.gapps (pid 4380) has died
,09-13 11:57:23.442   874  3991 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{d4039d8 u0 com.google.android.gms/.gcm.GcmService}
,09-13 11:57:23.442   874  3991 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{9f2f114 u0 com.google.android.gms/.auth.GetToken}
09-13 11:57:23.443   874  3991 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{82dc135 u0 com.google.android.gms/.config.ConfigService}
,09-13 11:57:23.443   874  3991 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{1fec0d7 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
09-13 11:57:23.444   874  4421 E DropBoxManagerService: Can't write: system_app_crash
09-13 11:57:23.444   874  4421 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
,09-13 11:57:23.444   874  4421 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 11:57:23.444   874  4421 E DropBoxManagerService: 	... 5 more
,09-13 11:57:23.459   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 11:57:23.459   874  3991 I ActivityManager: Start proc 4424:com.google.process.gapps/u0a11 for restart com.google.process.gapps

```
