#### Test 83444050ceb1988_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,09-02 19:06:37.246   873  1872 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
09-02 19:06:37.903  3813  3813 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-02 19:06:37.907  3813  3813 D AndroidRuntime: CheckJNI is OFF
09-02 19:06:37.943  3813  3813 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-02 19:06:37.986  3813  3813 I Radio-JNI: register_android_hardware_Radio DONE
09-02 19:06:38.005  3813  3813 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-02 19:06:38.011   873  2048 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 19:06:38.063  2072  2086 W SearchService: Abort, client detached.
09-02 19:06:38.067  3813  3813 D AndroidRuntime: Shutting down VM
09-02 19:06:38.070  2072  2072 I HotwordDetector: Closing mic
09-02 19:06:38.071  2072  2331 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d445745
09-02 19:06:38.102   873  1599 I ActivityManager: Start proc 3822:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-02 19:06:38.137   376  2341 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-02 19:06:38.138   376  2341 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-02 19:06:38.143   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-02 19:06:38.146  2072  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-02 19:06:38.147  2072  2338 I MicroRecognitionRnrImpl: Detection finished
09-02 19:06:38.186  3822  3822 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-02 19:06:38.215  3822  3822 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-02 19:06:38.223  3822  3822 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1185-1188)
09-02 19:06:38.223  3822  3822 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:06:38.239  3822  3822 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7574bea}
09-02 19:06:38.240  3822  3822 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 19:06:38.240  3822  3822 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 19:06:38.247  3822  3822 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-02 19:06:38.248  3822  3822 E SysUtils: ApplicationContext is null in ApplicationStatus
09-02 19:06:38.264  3822  3822 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-02 19:06:38.273  3822  3822 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 19:06:38.273  3822  3822 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 19:06:38.273  3822  3822 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 19:06:38.273  3822  3822 I Adreno  : Build Date                       : 10/20/15
09-02 19:06:38.273  3822  3822 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 19:06:38.273  3822  3822 I Adreno  : Local Branch                     : M14
09-02 19:06:38.273  3822  3822 I Adreno  : Remote Branch                    : 
09-02 19:06:38.273  3822  3822 I Adreno  : Remote Branch                    : 
09-02 19:06:38.273  3822  3822 I Adreno  : Reconstruct Branch               : 
,09-02 19:06:38.325   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@69a9aa9:true
,09-02 19:06:38.366  3822  3822 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 19:06:38.377  3822  3822 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-02 19:06:38.446  3822  3862 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-02 19:06:38.454  3822  3848 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-02 19:06:38.498  3822  3862 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 19:06:38.570   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +500ms,
,09-02 19:06:38.585  1897  1897 I Keyboard.Facilitator: onFinishInput()
,09-02 19:06:38.640  3822  3822 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3822
,09-02 19:06:38.734  3822  3822 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 19:06:38.883   873  1599 I ActivityManager: Killing 2981:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-02 19:06:38.904  3822  3864 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1701054160
,09-02 19:06:38.909  3822  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 19:06:38.909  3822  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 19:06:38.909  3822  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 19:06:38.909  3822  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 19:06:38.909  3822  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 19:06:38.909  3822  3864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdb7249 added. We now have 1 listener(s)
,09-02 19:06:38.912  3822  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-02 19:06:38.914  3822  3864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 19:06:38.914  3822  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:06:38.915  3822  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:06:38.915   873  1599 I ActivityManager: Killing 3226:com.google.android.gm/u0a78 (adj 15): empty #18
,09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-02 19:06:38.920  3822  3864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2be917c added. We now have 1 listener(s)
09-02 19:06:38.920  3822  3864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:06:38.923   873  1304 D WifiService: New client listening to asynchronous messages
,09-02 19:06:38.925  3822  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:06:38.925  3822  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 19:06:38.925  3822  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-02 19:06:38.925  3822  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 19:06:38.925  3822  3864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-02 19:06:38.989  3822  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:06:38.989  3822  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-02 19:06:38.996  3822  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:38.996  3822  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:38.996  3822  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 19:06:38.996  3822  3864 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:06:38.997  3822  3864 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 19:06:39.094  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:39.096  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:39.099  3822  3822 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 19:06:39.928  3822  3872 W jxcore-log: Initializing JXcore engine
,09-02 19:06:39.928  3822  3872 W jxcore-log: JXcore engine is ready
,09-02 19:06:39.992  3872  3872 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-02 19:06:39.992  3872  3872 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11027]" dev="sockfs" ino=11027 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-02 19:06:39.992  3872  3872 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-02 19:06:39.992  3872  3872 W Thread-330: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25844]" dev="sockfs" ino=25844 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-02 19:06:40.013  3822  3872 W jxcore-log: Starting JXcore engine
,09-02 19:06:40.102  3822  3872 W jxcore-log: Platform android
09-02 19:06:40.102  3822  3872 W jxcore-log: 
09-02 19:06:40.102  3822  3872 W jxcore-log: Process ARCH arm
09-02 19:06:40.102  3822  3872 W jxcore-log: 
,09-02 19:06:40.368  3822  3872 I jxcore-log: JXcore Cordova bridge is ready!
09-02 19:06:40.368  3822  3872 I jxcore-log: 
,09-02 19:06:40.368  3822  3872 W jxcore-log: JXcore engine is started
,09-02 19:06:40.374  3822  3864 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 19:06:40.379  3822  3822 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 19:06:48.345  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:06:48.353  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:06:48.358  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:06:48.392  1504  2104 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-02 19:06:48.393  1504  2104 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-02 19:06:48.393  1504  2104 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 19:06:48.393  1504  2104 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:48.438  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-02 19:06:48.438  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-02 19:06:48.439  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-02 19:06:49.497   873  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-02 19:06:50.028  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 19:06:50.028  3822  3872 I jxcore-log: 
,09-02 19:06:50.031  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 19:06:50.031  3822  3872 I jxcore-log: 
,09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:50.044  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:06:50.049  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:06:50.055  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 19:06:50.055  3822  3872 I jxcore-log: 
,09-02 19:06:50.062  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 19:06:50.062  3822  3872 I jxcore-log: 
,09-02 19:06:50.581  3822  3872 D executeNativeTests: Running unit tests
,09-02 19:06:50.640  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:06:50.640  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e added. We now have 2 listener(s)
,09-02 19:06:50.641  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:06:50.641  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:06:50.641  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:06:50.641  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:06:50.641  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f added. We now have 2 listener(s)
09-02 19:06:50.641  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:06:50.642  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:06:50.644  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:50.656  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:06:50.659  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:06:50.660  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:06:50.663  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:50.667  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:50.669  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 19:06:50.669  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 19:06:50.670  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:06:50.677  3822  3872 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-02 19:06:50.679  3822  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:06:50.679  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:06:50.679  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:06:50.679  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:06:50.680  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:50.680  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.680  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:06:50.681  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:06:50.681  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.681  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:50.681  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:06:50.681  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e removed from the list
09-02 19:06:50.681  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.681  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f removed from the list
09-02 19:06:50.681  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:50.682  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.682  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.682  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.683  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.683  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.683  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.684  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.686  3822  3872 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-02 19:06:50.686  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:50.687  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.687  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.687  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:06:50.687  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.687  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.687  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.687  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.687  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.688  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:50.688  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.688  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.688  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.688  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.689  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:06:50.689  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.689  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.690  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:50.696  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-02 19:06:50.696  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 19:06:50.696  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 19:06:50.696  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:06:50.696  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-02 19:06:50.697  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 19:06:50.698  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:06:50.699  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:50.699  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.699  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.699  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:50.699  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.699  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.699  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.699  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.699  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.699  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:50.700  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.700  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.700  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.700  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.701  3822  3872 I org.thaliproject.p2p.btconnecto,rlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.701  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.701  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.701  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.703  3822  3872 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 19:06:50.705  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:50.710  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:50.712  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:50.713  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:50.713  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:06:50.713  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:06:50.713  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:06:50.713  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:50.713  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:06:50.715  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:50.720  3822  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 19:06:50.720  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:06:50.723  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:50.727  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 19:06:50.732  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 19:06:50.733  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 19:06:50.737  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-02 19:06:50.742  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 19:06:50.742  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:06:50.743  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:06:50.745  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 19:06:50.747  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:06:50.756  2683  2695 D BtGatt.GattService: registerClient() - UUID=d6e7e309-3206-4464-87d4-b3b27a4ce836
09-02 19:06:50.758  2683  2702 D BtGatt.GattService: onClientRegistered() - UUID=d6e7e309-3206-4464-87d4-b3b27a4ce836, clientIf=5
09-02 19:06:50.759  3822  3833 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 19:06:50.761  2683  2694 D BtGatt.GattService: start scan with filters
09-02 19:06:50.770  2683  2705 D BtGatt.ScanManager: handling starting scan
09-02 19:06:50.770  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:06:50.771  2683  2705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
09-02 19:06:50.771  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:06:50.772  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:06:50.772  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 19:06:50.778  2683  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 19:06:50.778  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.779  2683  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 19:06:50.781  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:06:50.782  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:06:50.784  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 19:06:50.788  2683  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 19:06:50.789  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.789  2683  2705 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 19:06:50.790  2683  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 19:06:50.791  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:06:50.796  3822  3872 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:06:50.803  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:50.803  3822  3872 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 19:06:50.803  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:06:50.803  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:06:50.803  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.803  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 19:06:50.803  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 19:06:50.803  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:06:50.804  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 19:06:50.804  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:06:50.805  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:06:50.805  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:06:50.805  3822  3872 D BluetoothAdapter: STATE_ON
09-02 19:06:50.806  2683  2695 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:06:50.807  2683  2694 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-02 19:06:50.808  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 19:06:50.808  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 19:06:50.808  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-02 19:06:50.810  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:06:50.811  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 19:06:50.811  2683  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 19:06:50.811  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.813  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:06:50.814  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:06:50.814  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 19:06:50.814  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:06:50.815  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:50.817  2683  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 19:06:50.817  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.818  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:50.818  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:50.818  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.818  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:50.818  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:50.818  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:06:50.819  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
,09-02 19:06:50.819  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.819  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.819  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:50.819  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.820  3822  3872 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 19:06:50.822  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:50.827  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:06:50.827  2683  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 19:06:50.827  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.828  2683  2705 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:06:50.829  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:50.829  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:50.829  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:06:50.829  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:06:50.829  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:06:50.829  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:06:50.829  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:06:50.833  3822  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 19:06:50.833  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:06:50.833  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:50.837  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:50.837  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:06:50.838  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 19:06:50.838  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:06:50.838  2683  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 19:06:50.838  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.839  2683  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 19:06:50.845  2683  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 19:06:50.845  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.845  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:06:50.845  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 19:06:50.846  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 19:06:50.847  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:06:50.851  2683  2820 D BtGatt.GattService: registerClient() - UUID=4ccae4eb-f807-4d0e-8bc6-63f722a4b5d7
,09-02 19:06:50.852  2683  2702 D BtGatt.GattService: onClientRegistered() - UUID=4ccae4eb-f807-4d0e-8bc6-63f722a4b5d7, clientIf=5
,09-02 19:06:50.852  3822  3833 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 19:06:50.853  2683  2695 D BtGatt.GattService: start scan with filters
,09-02 19:06:50.858  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 19:06:50.858  2683  2705 D BtGatt.ScanManager: handling starting scan
,09-02 19:06:50.858  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:06:50.858  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:06:50.858  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-02 19:06:50.862  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:06:50.862  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:06:50.862  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:06:50.864  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:06:50.866  2683  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 19:06:50.866  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.866  2683  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 19:06:50.868  3822  3872 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:06:50.871  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:50.871  3822  3872 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:06:50.871  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:06:50.871  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:06:50.872  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.872  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 19:06:50.872  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:06:50.872  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 19:06:50.872  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:06:50.872  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:06:50.872  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 19:06:50.872  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 19:06:50.874  3822  3872 D BluetoothAdapter: STATE_ON
09-02 19:06:50.874  2683  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 19:06:50.874  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.874  2683  2820 D BtGatt.GattService: stopScan() - queue size =1
09-02 19:06:50.874  2683  2705 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 19:06:50.874  2683  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 19:06:50.875  2683  2695 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-02 19:06:50.876  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:50.876  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 19:06:50.876  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:06:50.877  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 19:06:50.877  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:06:50.879  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:06:50.879  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:06:50.880  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:06:50.880  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:06:50.881  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:06:50.883  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:06:50.883  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.883  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:06:50.883  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:50.883  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.883  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.883  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:50.883  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:50.884  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:50.884  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.884  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:06:50.884  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.884  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-02 19:06:50.886  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:06:50.886  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:06:50.886  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.887  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:50.887  2683  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 19:06:50.888  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.888  3822  3872 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 19:06:50.891  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:06:50.896  2683  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 19:06:50.896  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:50.899  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:06:50.904  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:06:50.904  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:06:50.904  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,09-02 19:06:50.904  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-02 19:06:50.904  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 19:06:50.904  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:06:50.904  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:06:50.907  2683  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 19:06:50.907  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.907  2683  2705 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:06:50.907  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:50.911  3822  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 19:06:50.910  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:50.911  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:06:50.915  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:06:50.915  2683  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 19:06:50.915  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.915  2683  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 19:06:50.916  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 19:06:50.917  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:06:50.921  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:06:50.921  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 19:06:50.921  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 19:06:50.922  2683  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 19:06:50.922  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:06:50.922  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.925  2683  2695 D BtGatt.GattService: registerClient() - UUID=04246e3e-5c63-42d9-b52a-32971f43cb1a
,09-02 19:06:50.926  2683  2702 D BtGatt.GattService: onClientRegistered() - UUID=04246e3e-5c63-42d9-b52a-32971f43cb1a, clientIf=5
09-02 19:06:50.926  3822  3834 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 19:06:50.927  2683  2820 D BtGatt.GattService: start scan with filters
,09-02 19:06:50.930  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:06:50.930  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:06:50.931  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 19:06:50.931  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:06:50.931  2683  2705 D BtGatt.ScanManager: handling starting scan
,09-02 19:06:50.934  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:06:50.934  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:06:50.934  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:06:50.936  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:06:50.939  3822  3872 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:06:50.939  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:50.939  3822  3872 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:06:50.939  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:06:50.940  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-02 19:06:50.940  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.940  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 19:06:50.940  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-02 19:06:50.940  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 19:06:50.940  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:06:50.940  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 19:06:50.940  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 19:06:50.940  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:06:50.941  2683  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 19:06:50.941  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.941  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:06:50.941  2683  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 19:06:50.942  2683  2829 D BtGatt.GattService: stopScan() - queue size =1
09-02 19:06:50.942  2683  2694 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 19:06:50.943  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:06:50.943  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:06:50.943  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:06:50.943  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 19:06:50.943  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:06:50.944  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:06:50.945  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 19:06:50.945  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:06:50.945  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:06:50.946  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-02 19:06:50.947  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:06:50.947  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:06:50.947  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:06:50.949  2683  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 19:06:50.950  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:50.950  3822  3872 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 19:06:50.950  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.950  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:06:50.951  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.951  2683  2705 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 19:06:50.951  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:50.951  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.951  2683  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 19:06:50.951  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:06:50.951  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
,09-02 19:06:50.951  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.951  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:50.951  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:50.951  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.952  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.953  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.954  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.954  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.954  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.955  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.955  3822  3872 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 19:06:50.956  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:50.956  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.956  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.956  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:50.957  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.957  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.957  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.957  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.957  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.957  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:50.957  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.957  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.957  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.957  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.958  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.959  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.959  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.959  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.960  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 19:06:50.960  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-02 19:06:50.960  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.960  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.961  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:50.961  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.961  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.961  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.961  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.961  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.961  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:50.961  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.961  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.961  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.962  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:50.963  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:06:50.963  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:06:50.963  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:50.963  2683  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 19:06:50.963  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.963  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.964  3822  3872 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 19:06:50.964  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:50.964  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.965  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.965  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:06:50.965  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.965  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.965  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.965  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.965  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.965  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:50.965  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.965  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:50.966  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.966  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.967  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.967  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.967  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.967  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:50.968  3822  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 19:06:50.969  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:50.969  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.969  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.969  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:50.969  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.969  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:50.969  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.969  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.970  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.970  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:50.970  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.970  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:50.970  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.970  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:50.970  2683  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 19:06:50.971  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.971  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.973  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.973  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:50.973  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:50.974  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 19:06:50.974  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 19:06:50.974  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 19:06:50.974  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:06:50.975  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 19:06:50.975  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:06:50.975  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:50.975  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.975  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.975  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:06:50.975  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.976  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.976  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
,09-02 19:06:50.976  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.976  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.976  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:50.976  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.976  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:50.977  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:50.977  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:50.978  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.978  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.978  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:50.979  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.979  3822  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:50.979  3822  3872 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-02 19:06:50.979  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 19:06:50.980  2683  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 19:06:50.980  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:06:50.981  2683  2705 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:06:50.985  3822  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:50.986  3822  3872 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:06:50.986  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:06:50.987  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:06:50.988  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-02 19:06:50.988  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:06:50.988  3822  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 19:06:50.988  3822  3872 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:06:50.989  3822  3872 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 19:06:50.989  3822  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:50.989  3822  3872 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:06:50.989  3822  3872 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 19:06:50.989  3822  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:50.989  3822  3872 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-02 19:06:50.989  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 19:06:50.992  2683  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 19:06:50.992  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:50.993  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 19:06:50.993  2683  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 19:06:50.993  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 19:06:50.993  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 19:06:50.994  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 19:06:50.994  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 19:06:50.994  3822  3872 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-02 19:06:50.994  3822  3872 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:06:50.994  3822  3872 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 19:06:50.995  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:50.995  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:50.995  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:50.996  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:50.996  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.996  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.996  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 19:06:50.997  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:50.997  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.997  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:50.997  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:50.997  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.997  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.997  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:50.997  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:50.998  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:50.998  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:50.998  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:50.998  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:50.998  3822  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
09-02 19:06:50.999  3822  3872 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 19:06:50.999  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:50.999  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:51.000  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:51.000  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.000  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.001  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.002  3822  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
09-02 19:06:51.002  3822  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
09-02 19:06:51.003  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.003  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.003  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.003  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:51.003  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.003  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.003  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.003  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.003  2683  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 19:06:51.004  2683  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:06:51.004  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:51.004  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.004  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.004  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.005  3822  3872 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 19:06:51.005  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:51.005  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:51.005  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:51.005  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.005  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.006  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.006  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.006  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.006  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.006  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:51.006  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:51.006  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.006  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.006  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.007  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:51.007  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.007  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.007  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.007  3822  3872 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 19:06:51.007  3822  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 19:06:51.008  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:06:51.008  3822  3872 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 19:06:51.008  3822  3872 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-02 19:06:51.008  3822  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 19:06:51.008  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:06:51.008  3822  3872 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 19:06:51.008  3822  3872 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 19:06:51.008  3822  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 19:06:51.008  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:06:51.008  3822  3872 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 19:06:51.008  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:51.008  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:51.009  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:06:51.009  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.009  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.009  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.009  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.009  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.009  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.009  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:51.009  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.009  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.009  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.009  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.011  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:06:51.011  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.011  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.011  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.012  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.013  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.013  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.013  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.013  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.013  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:51.014  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:51.014  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.014  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.014  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.014  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:51.015  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.015  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.015  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.015  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.015  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:51.016  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:51.016  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:51.016  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.016  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.016  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.016  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.017  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:51.017  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.017  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:51.017  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.017  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.017  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.018  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.020  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:51.020  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.020  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.020  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.023  3822  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 19:06:51.023  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:06:51.024  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-02 19:06:51.025  3822  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 19:06:51.025  3822  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 19:06:51.025  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 19:06:51.025  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:06:51.025  3822  3822 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 19:06:51.026  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:06:51.026  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 19:06:51.026  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 19:06:51.026  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-02 19:06:51.026  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.026  3822  3872 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 19:06:51.026  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.026  3822  3822 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-02 19:06:51.026  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.026  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:06:51.026  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:06:51.026  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:06:51.026  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.027  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.027  3822  3885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:06:51.028  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:06:51.028  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.028  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:51.028  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:51.028  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:06:51.028  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:06:51.028  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:06:51.028  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:51.028  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.028  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.028  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.028  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.028  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.028  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.028  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:51.029  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.029  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.029  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.029  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:51.030  3822  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 19:06:51.030  3822  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 19:06:51.030  3822  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 19:06:51.031  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:51.031  3822  3822 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-02 19:06:51.031  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.031  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.031  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.032  3822  3872 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 19:06:51.032  3822  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:06:51.032  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 19:06:51.034  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 19:06:51.034  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:06:51.034  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:06:51.034  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:51.038  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.038  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:51.038  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.038  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.038  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:51.038  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.038  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:51.038  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:51.038  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.039  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.039  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.039  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:06:51.039  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.039  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.040  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
,09-02 19:06:51.044  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:51.044  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:51.045  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:06:51.045  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.045  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.045  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:51.045  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.046  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.046  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.046  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:06:51.046  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.046  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.046  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:06:51.046  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:51.048  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:51.048  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.048  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:51.048  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.049  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:06:51.049  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:06:51.049  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:06:51.049  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:06:51.049  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.049  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:51.049  3822  3872 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe17e9e not in the list
09-02 19:06:51.049  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:06:51.049  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list,
09-02 19:06:51.049  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:06:51.049  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.049  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:06:51.049  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:06:51.049  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:06:51.051  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:06:51.051  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:06:51.051  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:06:51.051  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cb3d7f not in the list
09-02 19:06:51.052  3822  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 19:06:51.052  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:06:51.052  3822  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 19:06:51.052  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-02 19:06:51.052  3822  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 19:06:51.052  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-02 19:06:51.054  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 19:06:51.054  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-02 19:06:51.055  3822  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 19:06:51.055  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:06:51.055  3822  3872 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-02 19:06:51.055  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:06:51.055  3822  3872 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 19:06:51.055  3822  3872 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-02 19:06:51.056  3822  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 19:06:51.056  3822  3872 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-02 19:06:51.057  3822  3872 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 19:06:51.057  3822  3872 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 19:06:51.057  3822  3872 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 19:06:51.057  3822  3872 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-02 19:06:51.058  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:06:51.058  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9de7649 added. We now have 2 listener(s)
09-02 19:06:51.058  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:06:51.061  3822  3872 D BluetoothAdapter: enable(): BT is already enabled..!
,09-02 19:06:51.062   873   883 D WifiService: setWifiEnabled: true pid=3822, uid=10000
09-02 19:06:51.062   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:06:51.063  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:06:51.063  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@138cb4e added. We now have 3 listener(s)
09-02 19:06:51.063  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:06:51.075  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:06:51.075  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f74846f added. We now have 4 listener(s)
,09-02 19:06:51.076  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:06:51.078  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:06:51.078  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d0657c added. We now have 5 listener(s)
,09-02 19:06:51.078  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:06:51.082   873  1599 D WifiService: setWifiEnabled: false pid=3822, uid=10000
,09-02 19:06:51.083   873  1599 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:06:51.092  2683  2698 D BluetoothAdapterState: Current state: ON, message: 23
,09-02 19:06:51.092  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:06:51.092  2683  2698 D BluetoothAdapterProperties: Setting state to 13
09-02 19:06:51.092  2683  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 19:06:51.097  2683  2698 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 19:06:51.100  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:51.100  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:06:51.100  2683  2702 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:06:51.100  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:51.100  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:51.101  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:06:51.101  2683  2698 I BluetoothAdapterState: Entering PendingCommandState
09-02 19:06:51.101  2683  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-02 19:06:51.104  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.106  2683  2683 D HeadsetService: Received stop request...Stopping profile...
09-02 19:06:51.107  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.108  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 19:06:51.109   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 19:06:51.109   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-02 19:06:51.109   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 19:06:51.109   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:06:51.111  1361  1381 D BluetoothHeadset: Proxy object disconnected
,09-02 19:06:51.111  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-02 19:06:51.112   873   873 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:51.112   873   873 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:51.112   873   873 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:51.113  1985  2292 D BluetoothHeadset: Proxy object disconnected
09-02 19:06:51.113  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:51.114  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:51.114  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:51.114  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:51.116  2683  2683 D A2dpService: Received stop request...Stopping profile...
09-02 19:06:51.116  2683  2822 D A2dpStateMachine: Exit Disconnected: -1
09-02 19:06:51.117  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:51.120  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-02 19:06:51.120   873   873 D BluetoothA2dp: Proxy object disconnected
,09-02 19:06:51.122  2683  2683 D HidService: Received stop request...Stopping profile...
,09-02 19:06:51.122  2683  2683 D HidService: Stopping Bluetooth HidService
09-02 19:06:51.123  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-02 19:06:51.123  1361  1361 D HidProfile: Bluetooth service disconnected
,09-02 19:06:51.123   873  1875 D DhcpClient: Clearing IP address
09-02 19:06:51.123  2683  2683 V BluetoothAdapterState: isTurningOff()=true
09-02 19:06:51.123  2683  2683 V BluetoothAdapterState: isTurningOn()=false
09-02 19:06:51.123  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:06:51.123  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:06:51.123   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:06:51.126  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 19:06:51.126  2683  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-02 19:06:51.126  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:06:51.126  2683  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:06:51.126  2683  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:06:51.126  2683  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:06:51.126  2683  2702 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-02 19:06:51.126   372   871 D CommandListener: Setting iface cfg
09-02 19:06:51.127  2683  2683 D HealthService: Received stop request...Stopping profile...
,09-02 19:06:51.129  2683  2683 D PanService: Received stop request...Stopping profile...
09-02 19:06:51.130  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 19:06:51.130  1361  1361 D PanProfile: Bluetooth service disconnected
,09-02 19:06:51.131  2683  2683 D BluetoothMapService: Received stop request...Stopping profile...
09-02 19:06:51.131  2683  2683 D BluetoothMapService: stop()
09-02 19:06:51.132  1504  2481 V NativeCrypto: Read error: ssl=0x9b650e00: I/O error during system call, Connection timed out
09-02 19:06:51.132  2683  2683 D BluetoothMapAppObserver: deinitObservers()
09-02 19:06:51.132  2683  2683 D BluetoothMapAppObserver: removeReceiver()
,09-02 19:06:51.133  1504  2481 V NativeCrypto: SSL shutdown failed: ssl=0x9b650e00: I/O error during system call, Broken pipe
09-02 19:06:51.134  1361  1361 D BluetoothMap: Proxy object disconnected
09-02 19:06:51.134  1361  1361 D MapProfile: Bluetooth service disconnected
09-02 19:06:51.135   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 19:06:51.135   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-02 19:06:51.142   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
09-02 19:06:51.143   396   396 E Parcel  : Reading a NULL string not supported here.
,09-02 19:06:51.143   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 19:06:51.144  2683  2683 V BluetoothAdapterState: isTurningOff()=true
,09-02 19:06:51.144  2683  2683 V BluetoothAdapterState: isTurningOn()=false
09-02 19:06:51.144  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:06:51.144   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-02 19:06:51.144  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:06:51.148  2683  2683 V BluetoothAdapterState: isTurningOff()=true
,09-02 19:06:51.148  2683  2683 V BluetoothAdapterState: isTurningOn()=false
,09-02 19:06:51.148  2683  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 19:06:51.148  2683  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:06:51.148  2683  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:06:51.148  2683  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:06:51.148  2683  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:06:51.148  2683  2800 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:06:51.148  2683  2800 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:06:51.148  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:06:51.148  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:06:51.148   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-02 19:06:51.149  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-02 19:06:51.149  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 19:06:51.149  2683  2683 V BluetoothAdapterState: isTurningOff()=true
09-02 19:06:51.149  2683  2683 V BluetoothAdapterState: isTurningOn()=false
09-02 19:06:51.149  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 19:06:51.149  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:06:51.149  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:06:51.151   873  1878 D DhcpClient: Receive thread stopped
09-02 19:06:51.152   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-02 19:06:51.152  2683  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 19:06:51.152  2683  2702 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 19:06:51.152  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-02 19:06:51.153  2683  2683 V BluetoothAdapterState: isTurningOff()=true
09-02 19:06:51.153  2683  2683 V BluetoothAdapterState: isTurningOn()=false
09-02 19:06:51.153  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:06:51.153  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:06:51.153   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 19:06:51.153  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-02 19:06:51.153  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 19:06:51.155  2683  2683 D BluetoothMapService: MAP Service closeService in
09-02 19:06:51.155  2683  2683 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 19:06:51.155  2683  2683 D ObexServerSockets0: shutdown(block = true)
09-02 19:06:51.156  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-02 19:06:51.156  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 19:06:51.156  2683  2816 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 19:06:51.156  2683  2837 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 19:06:51.157  2683  2836 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 19:06:51.157  2683  2683 V BluetoothAdapterState: isTurningOff()=true
09-02 19:06:51.157  2683  2683 V BluetoothAdapterState: isTurningOn()=false
,09-02 19:06:51.157  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:06:51.157  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:06:51.158  2683  2683 D BluetoothMapService: cleanup()
09-02 19:06:51.158  2683  2683 D BluetoothMapService: MAP Service closeService in
09-02 19:06:51.158  2683  2683 I BtOppRfcommListener: stopping Accept Thread
,09-02 19:06:51.158  2683  3450 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:06:51.158  2683  3450 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 19:06:51.159  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:51.159  2683  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 19:06:51.159  2683  2698 D BluetoothAdapterProperties: Setting state to 15
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:51.159  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:51.159  2683  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 19:06:51.160  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:51.160  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:06:51.160  2683  2698 I BluetoothAdapterState: Entering BleOnState
09-02 19:06:51.162  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:51.162  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:51.162  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:51.163  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:51.166  1851  2251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 19:06:51.166  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.168  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:51.185   873   886 I ActivityManager: Start proc 3890:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-02 19:06:51.186  1361  2117 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:06:51.191  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 19:06:51.195   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:06:51.195   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-02 19:06:51.195  1361  1378 D BluetoothPan: onBluetoothStateChange on: false
09-02 19:06:51.195   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:06:51.197  1361  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:06:51.197  1985  1998 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 19:06:51.197   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:06:51.198   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 19:06:51.198  1361  2117 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 19:06:51.199  1361  1378 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 19:06:51.200  2683  2698 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-02 19:06:51.200  2683  2698 D BluetoothAdapterProperties: Setting state to 16
09-02 19:06:51.200  2683  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-02 19:06:51.201  2683  2698 D BluetoothAdapterProperties: onBleDisable
,09-02 19:06:51.201  2683  2698 I BluetoothAdapterState: Entering PendingCommandState
,09-02 19:06:51.202  2683  2699 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-02 19:06:51.204  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.204  2683  2800 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 19:06:51.204  2683  2800 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:06:51.205  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.206  2683  2702 D BluetoothAdapterProperties: Scan Mode:20
09-02 19:06:51.207  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.208  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:51.227  3890  3890 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-02 19:06:51.228   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:06:51.229   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 19:06:51.229   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:51.233   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-02 19:06:51.234  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.235  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:06:51.234  3419  3419 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ab8174e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-02 19:06:51.245  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:06:51.251  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:06:51.251   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6559587:true
,09-02 19:06:51.264   873  2045 I ActivityManager: Start proc 3907:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-02 19:06:51.273  3890  3890 D LocalBluetoothProfileManager: Adding local MAP profile
09-02 19:06:51.275  3890  3890 D BluetoothMap: Create BluetoothMap proxy object
,09-02 19:06:51.279  3890  3890 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-02 19:06:51.286   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-02 19:06:51.287   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-02 19:06:51.292  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:06:51.297   873  1938 I ActivityManager: Killing 3061:com.google.android.talk/u0a61 (adj 15): empty #17
,09-02 19:06:51.305  3907  3907 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-02 19:06:51.410  2683  2702 I bt_hci  : shut_down
09-02 19:06:51.411  2683  2706 D bt_hwcfg: hw_epilog_process
09-02 19:06:51.412  2683  2706 I bt_vendor: low_power_mode_cb
,09-02 19:06:51.441  2683  2706 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 19:06:51.441  2683  2706 I bt_vendor: epilog_cb
,09-02 19:06:51.441  2683  2706 I bt_hci  : epilog_finished_callback
,09-02 19:06:51.450  2683  2702 I bt_hci_h4: hal_close
,09-02 19:06:51.451  2683  2702 I bt_userial_vendor: device fd = 51 close
,09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 19:06:51.504  3,907  3907 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.k.d(PG:583)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 1,9:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 19:06:51.504  3907  3907 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:06:51.504  3907  3907 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 19:06:51.529  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 19:06:51.530   873  1692 I ActivityManager: Start proc 3938:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-02 19:06:51.531   873  1692 I ActivityManager: Killing 3581:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-02 19:06:51.584  2683  2699 D bt_stack_manager: event_shut_down_stack finished.
09-02 19:06:51.584  2683  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 19:06:51.589  2683  2683 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:06:51.591  2683  2698 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-02 19:06:51.592  2683  2683 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 19:06:51.592  2683  2683 D BtGatt.GattService: stop()
,09-02 19:06:51.592  2683  2683 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 19:06:51.602  2683  2683 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:06:51.602  2683  2683 V BluetoothAdapterState: isTurningOn()=false
09-02 19:06:51.602  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 19:06:51.603  2683  2683 V BluetoothAdapterState: isBleTurningOff()=true
09-02 19:06:51.603  2683  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-02 19:06:51.604  2683  2698 D BluetoothAdapterProperties: Setting state to 10
09-02 19:06:51.604  2683  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 19:06:51.605  2683  2698 I BluetoothAdapterState: Entering OffState
09-02 19:06:51.605   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-02 19:06:51.610  3938  3938 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-02 19:06:51.616  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-02 19:06:51.616  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-02 19:06:51.616  2683  2683 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 19:06:51.617  2683  2699 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-02 19:06:51.620  2683  2699 D bt_stack_manager: event_clean_up_stack finished.
,09-02 19:06:51.623  2683  2683 I art     : System.exit called, status: 0
,09-02 19:06:51.623  2683  2683 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 19:06:51.682  3938  3938 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-02 19:06:51.694   873  1999 I ActivityManager: Process com.android.bluetooth (pid 2683) has died
,09-02 19:06:51.730   873  1692 I ActivityManager: Start proc 3963:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-02 19:06:51.733   873   883 I ActivityManager: Killing 3419:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-02 19:06:51.791  3907  3927 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 19:06:51.825   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fd7f49:true
,09-02 19:06:51.884  3963  3963 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-02 19:06:52.052  3963  3982 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-02 19:06:52.052  3963  3982 I Babel_SMS: MmsConfig.loadMmsSettings
,09-02 19:06:52.056  3963  3982 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-02 19:06:52.056  3963  3982 I Babel_SMS: MmsConfig.loadFromDatabase
,09-02 19:06:52.088  3963  3982 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-02 19:06:52.089  3963  3982 I Babel_SMS: MmsConfig.loadFromResources
,09-02 19:06:52.091  3963  3982 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-02 19:06:52.092  3963  3982 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-02 19:06:52.119  3963  3963 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:06:52.121  3963  3963 I Babel_Crash: startup - clean
,09-02 19:06:52.150  3963  3963 I Babel_telephony: TeleModule.launchCompleted
,09-02 19:06:52.163   873  1938 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-02 19:06:52.173  3963  3963 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-02 19:06:52.180  3963  3963 W Babel   : BAM#gBA: invalid account id: -1
,09-02 19:06:52.180  3963  3963 W Babel   : BAM#gBA: invalid account id: -1
09-02 19:06:52.180  3963  3963 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-02 19:06:52.191  3963  3987 I Babel   : deleted: false for 0
,09-02 19:06:52.200   873  2040 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-02 19:06:52.218  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:06:52.253   873  1999 I ActivityManager: Start proc 3990:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-02 19:06:52.254  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:06:52.283  3963  3963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:06:52.370  3963  3963 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 19:06:52.383  3990  3990 D AdapterServiceConfig: Adding HeadsetService
,09-02 19:06:52.384  3990  3990 D AdapterServiceConfig: Adding A2dpService
,09-02 19:06:52.384  3990  3990 D AdapterServiceConfig: Adding HidService
,09-02 19:06:52.384  3990  3990 D AdapterServiceConfig: Adding HealthService
,09-02 19:06:52.384  3990  3990 D AdapterServiceConfig: Adding PanService
09-02 19:06:52.384  3990  3990 D AdapterServiceConfig: Adding GattService
,09-02 19:06:52.384  3990  3990 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 19:06:52.391  3963  3963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:06:52.399  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:06:52.402  3963  3963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-02 19:06:52.410  3963  3963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:06:52.422  3963  3963 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:06:52.428  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 19:06:52.437   873  1999 I ActivityManager: Killing 3629:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-02 19:06:52.515  1697  1697 D SystemUpdateService: onCreate
,09-02 19:06:52.520  3963  3963 I vclib   : onServiceConnected
,09-02 19:06:52.529  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 19:06:52.537  1697  4002 I SystemUpdateService: active receiver: enabled
,09-02 19:06:52.542  1697  4002 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 19:06:52.546  1697  4002 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 19:06:52.546  1697  4002 I SystemUpdateService: now status is 0 (complete)
,09-02 19:06:52.546  1697  4002 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 19:06:52.547  1697  4002 I SystemUpdateService: file has been verified
09-02 19:06:52.547  1697  4002 I SystemUpdateService: OTA package size = 12249756
,09-02 19:06:52.552  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 19:06:52.562  1697  2456 I iu.UploadsManager: num queued entries: 0
,09-02 19:06:52.564  1697  2456 I iu.UploadsManager: num updated entries: 0
,09-02 19:06:52.560  1697  4002 I SystemUpdateService: showing system update notification
,09-02 19:06:52.568  1697  2456 I iu.SyncManager: NEXT; no task
,09-02 19:06:52.578  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 19:06:52.580  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 19:06:52.606   873  2048 I ActivityManager: Start proc 4005:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-02 19:06:52.608  1697  1697 D SystemUpdateService: onDestroy
,09-02 19:06:52.649  4005  4005 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-02 19:06:52.652  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:52.659  4005  4005 D SprintDMHelper: simOperator: 
,09-02 19:06:52.659  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 19:06:52.693   873  2023 I ActivityManager: Start proc 4017:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-02 19:06:52.694   873  2023 I ActivityManager: Killing 3473:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-02 19:06:52.837   873  2039 I ActivityManager: Start proc 4032:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-02 19:06:52.840  3963  4031 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-02 19:06:52.844   873   883 I ActivityManager: Killing 3512:android.process.acore/u0a5 (adj 15): empty #17
,09-02 19:06:52.894  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-02 19:06:52.952  4032  4032 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-02 19:06:52.952  4032  4032 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-02 19:06:52.952  4032  4032 I GAv4    :   adb logcat -s GAv4
,09-02 19:06:52.968  4032  4032 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-02 19:06:52.975  4032  4032 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-02 19:06:53.007  4032  4050 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-02 19:06:53.123  4032  4032 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-02 19:06:53.168  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-02 19:06:53.177  4032  4032 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6138-6142)
,09-02 19:06:53.178  4032  4032 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 19:06:53.189  4032  4032 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {afeeffe}
,09-02 19:06:53.190  4032  4032 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 19:06:53.190  4032  4032 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 19:06:53.202  4032  4032 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 19:06:53.204  4032  4032 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 19:06:53.221  4032  4032 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-02 19:06:53.237  4032  4032 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 19:06:53.237  4032  4032 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 19:06:53.237  4032  4032 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 19:06:53.237  4032  4032 I Adreno  : Build Date                       : 10/20/15
09-02 19:06:53.237  4032  4032 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 19:06:53.237  4032  4032 I Adreno  : Local Branch                     : M14
09-02 19:06:53.237  4032  4032 I Adreno  : Remote Branch                    : 
09-02 19:06:53.237  4032  4032 I Adreno  : Remote Branch                    : 
09-02 19:06:53.237  4032  4032 I Adreno  : Reconstruct Branch               : 
,09-02 19:06:53.300  4032  4032 I NSApplication: Starting up...
,09-02 19:06:53.299  4032  4078 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-02 19:06:53.344   873  2051 I ActivityManager: Start proc 4083:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-02 19:06:53.346   873  2051 I ActivityManager: Killing 3706:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-02 19:06:53.410  4083  4083 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-02 19:06:53.606   873  2045 I ActivityManager: Killing 3721:com.android.musicfx/u0a18 (adj 15): empty #17
,09-02 19:06:54.106   873  2048 D WifiService: setWifiEnabled: true pid=3822, uid=10000
09-02 19:06:54.106   873  2048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:06:54.121   873  1303 D WifiConfigStore: Loading config and enabling all networks 
09-02 19:06:54.126  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.126  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:54.126  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:54.126  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:06:54.128  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:54.128  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:54.128  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:54.128  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:06:54.157   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-02 19:06:54.158   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-02 19:06:54.159   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-02 19:06:54.160   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 19:06:54.160   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-02 19:06:54.160   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-02 19:06:54.161   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 19:06:54.174   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 19:06:54.175   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.50 rxSuccessRate=13.62 delta 1000 -> 994
,09-02 19:06:54.176   372   871 D CommandListener: Setting iface cfg
,09-02 19:06:54.177   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-02 19:06:54.177   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 19:06:54.180   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 19:06:54.180   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 19:06:54.200   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 19:06:54.200   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:06:54.206   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 19:06:54.247   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 19:06:54.248  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 19:06:54.671  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 19:06:54.714  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 19:06:54.717  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 19:06:54.723   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 19:06:54.737   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-02 19:06:54.738   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 19:06:54.738   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:06:54.756   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:06:54.770   372   871 D CommandListener: Setting iface cfg
,09-02 19:06:54.771   873  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-02 19:06:54.794   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 19:06:54.794   873  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-02 19:06:54.799   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 19:06:54.806   873  4108 D DhcpClient: Receive thread started
,09-02 19:06:54.892   873  1303 E native  : do suspend false
,09-02 19:06:54.915   873  1875 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 19:06:54.930   873  4108 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172694, domain null
,09-02 19:06:54.931   873  1875 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172694 seconds
,09-02 19:06:54.935   873  1875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 19:06:54.955   873  4108 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 19:06:54.956   873  1875 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 19:06:54.961   372   871 D CommandListener: Setting iface cfg
,09-02 19:06:54.973   873  1875 D DhcpClient: Scheduling renewal in 86399s
,09-02 19:06:54.973   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-02 19:06:54.989   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 19:06:54.993   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
09-02 19:06:54.995   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 19:06:54.997   873  1305 D ConnectivityService: Adding iface wlan0 to network 101
,09-02 19:06:55.010   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 19:06:55.046   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 19:06:55.048   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-02 19:06:55.050   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-02 19:06:55.051   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-02 19:06:55.052   873  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-02 19:06:55.057   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 19:06:55.062   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-02 19:06:55.062   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-02 19:06:55.062   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-02 19:06:55.062   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-02 19:06:55.062   873  1305 D ConnectivityService:    accepting network in place of null
09-02 19:06:55.063   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 19:06:55.063   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -57]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 19:06:55.078   873  4107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128043, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 19:06:55.095   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:06:55.122   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:06:55.133   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-02 19:06:55.133   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:55.142   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-02 19:06:55.152   873  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.110,2a00:1450:4001:817::200e
,09-02 19:06:55.156   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-02 19:06:55.163  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:55.164  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:06:55.164  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:55.164  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:55.166  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:06:55.166  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:06:55.166  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:55.166  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:06:55.177  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 19:06:55.180  1697  1697 D SystemUpdateService: onCreate
,09-02 19:06:55.183  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 19:06:55.186  1697  4118 I SystemUpdateService: active receiver: enabled
,09-02 19:06:55.192  1697  4118 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 19:06:55.197  1697  4118 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-02 19:06:55.197  1697  4118 I SystemUpdateService: now status is 0 (complete)
09-02 19:06:55.197  1697  4118 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 19:06:55.198  1697  4118 I SystemUpdateService: file has been verified
09-02 19:06:55.198  1697  4118 I SystemUpdateService: OTA package size = 12249756
,09-02 19:06:55.203  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 19:06:55.206  1697  2456 I iu.UploadsManager: num queued entries: 0
,09-02 19:06:55.206  1697  4118 I SystemUpdateService: showing system update notification
,09-02 19:06:55.206  1697  2456 I iu.UploadsManager: num updated entries: 0
,09-02 19:06:55.207  1697  2456 I iu.SyncManager: NEXT; no task
,09-02 19:06:55.209  1697  4122 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-02 19:06:55.209  1697  4122 W BaseAppContext: Using Auth Proxy for data requests.
,09-02 19:06:55.210  1697  4122 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 19:06:55.214  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-02 19:06:55.215  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 19:06:55.217  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:06:55.218  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:55.219  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:06:55.222  4005  4005 D SprintDMHelper: simOperator: 
,09-02 19:06:55.222  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 19:06:55.238   873  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 17:06:55 GMT], X-Android-Received-Millis=[1472836015238], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472836015212]}
,09-02 19:06:55.278   873   885 I ActivityManager: Start proc 4124:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-02 19:06:55.285   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 19:06:55.286   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-02 19:06:55.286   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 19:06:55.293   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 19:06:55.305  1697  1697 D SystemUpdateService: onDestroy
,09-02 19:06:55.318  4124  4124 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-02 19:06:55.333  1504  2113 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 19:06:55.334  1504  2113 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-02 19:06:55.334  1504  2113 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:06:55.334  1504  2113 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:55.350  1697  4122 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-02 19:06:55.381  3044  4141 V KeepSync: Connecting to GoogleApiClient
,09-02 19:06:55.382   873  2048 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-02 19:06:55.393  4124  4124 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-02 19:06:55.403  4124  4124 I BooksApp: Created application version: 3.6.9 (30609)
,09-02 19:06:55.416  3963  4137 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-02 19:06:55.418  1504  2104 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-02 19:06:55.418  1504  2104 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-02 19:06:55.418  1504  2104 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:06:55.419  1504  2104 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:55.434  1697  4149 V BaseAuthAsyncOperation: access token request failed
,09-02 19:06:55.445  3044  4141 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-02 19:06:55.465  4124  4152 I BooksSync: Starting books sync for 61035162, extras: ade
,09-02 19:06:55.572  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-02 19:06:55.572  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-02 19:06:55.572  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 19:06:55.573  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:55.590  4124  4158 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-02 19:06:55.619  3044  4141 E KeepSync: IOException
09-02 19:06:55.619  3044  4141 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-02 19:06:55.619  3044  4141 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-02 19:06:55.619  3044  4141 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-02 19:06:55.619  3044  4141 E KeepSync: 	... 10 more
,09-02 19:06:55.619  3044  4141 W KeepSync: Sync result 2
,09-02 19:06:55.646   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-02 19:06:55.656  1504  2113 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-02 19:06:55.656  1504  2113 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-02 19:06:55.656  1504  2113 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:06:55.657  1504  2113 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:55.710  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-02 19:06:55.711  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-02 19:06:55.711  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:06:55.711  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:55.739  4124  4158 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-02 19:06:55.744  4124  4152 E BooksSync: Soft error
09-02 19:06:55.744  4124  4152 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-02 19:06:55.744  4124  4152 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-02 19:06:55.747  4124  4152 E BooksSync: Sync error
09-02 19:06:55.747  4124  4152 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-02 19:06:55.747  4124  4152 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-02 19:06:55.747  4124  4152 I BooksSync: Finished books sync
,09-02 19:06:55.762   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126456, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-02 19:06:55.763   873  2023 I ActivityManager: Killing 1926:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-02 19:06:56.057  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-02 19:06:56.057  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-02 19:06:56.057  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:06:56.057  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:56.094  3568  4161 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-02 19:06:56.094  3568  4161 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jdm.a(PG:82)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jcs.o(PG:406)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jcn.a(PG:1379)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jcs.i(PG:143)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at blb.a(PG:3937)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at czp.a(PG:18188)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at czp.a(PG:9081)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at czq.run(PG:1686)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 19:06:56.094  3568  4161 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jdj.a(PG:4091)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jdj.a(PG:1125)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jdm.a(PG:77)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	... 12 more
09-02 19:06:56.094  3568  4161 E HttpOperation: Caused by: faj: BadAuthentication
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at fal.a(PG:38)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	at jdj.a(PG:4089)
09-02 19:06:56.094  3568  4161 E HttpOperation: 	... 14 more
,09-02 19:06:56.130   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 19:06:56.159  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-02 19:06:56.159  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-02 19:06:56.160  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:06:56.160  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:06:56.204  3568  4161 E HttpOperation: [getmobileexperiments] Unexpected exception
09-02 19:06:56.204  3568  4161 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jdm.a(PG:82)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jcs.o(PG:406)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jcn.a(PG:1379)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jcs.i(PG:143)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at hec.a(PG:42)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at hee.a(PG:102)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at czr.a(PG:65)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at kka.a(PG:108)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at czp.a(PG:19176)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at czp.a(PG:9081)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at czq.run(PG:1686)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	,at java.lang.Thread.run(Thread.java:818)
09-02 19:06:56.204  3568  4161 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jdj.a(PG:4091)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jdj.a(PG:1125)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jdm.a(PG:77)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	... 15 more
09-02 19:06:56.204  3568  4161 E HttpOperation: Caused by: faj: BadAuthentication
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at fal.a(PG:38)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	at jdj.a(PG:4089)
09-02 19:06:56.204  3568  4161 E HttpOperation: 	... 17 more
,09-02 19:06:56.204  3568  4161 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-02 19:06:56.204  3568  4161 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jdm.a(PG:82)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jcs.o(PG:406),
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jcn.a(PG:1379)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jcs.i(PG:143)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at hec.a(PG:42)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at hee.a(PG:102)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at czr.a(PG:65)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at kka.a(PG:108)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at czp.a(PG:19176)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at czp.a(PG:9081)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at czq.run(PG:1686)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jdj.a(PG:4091)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jdj.a(PG:1125)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jdm.a(PG:77)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	... 15 more
09-02 19:06:56.204  3568  4161 E ExperimentLoader: Caused by: faj: BadAuthentication
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at fal.a(PG:38)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	at jdj.a(PG:4089)
09-02 19:06:56.204  3568  4161 E ExperimentLoader: 	... 17 more
,09-02 19:06:56.347   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128709, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-02 19:06:56.953   873  1599 I ActivityManager: Killing 3749:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-02 19:06:57.117   873  2040 D WifiService: setWifiEnabled: false pid=3822, uid=10000
09-02 19:06:57.118   873  2040 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:06:57.149  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 19:06:57.157   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 19:06:57.157   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-02 19:06:57.157   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 19:06:57.158   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:06:57.178   873  1875 D DhcpClient: Clearing IP address
,09-02 19:06:57.179   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:06:57.184   372   871 D CommandListener: Setting iface cfg
,09-02 19:06:57.190  1504  4140 V NativeCrypto: Read error: ssl=0x9b5f2000: I/O error during system call, Connection timed out
,09-02 19:06:57.194  1504  4140 V NativeCrypto: SSL shutdown failed: ssl=0x9b5f2000: I/O error during system call, Broken pipe
,09-02 19:06:57.203   873  2020 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-02 19:06:57.204   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-02 19:06:57.205   873  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-02 19:06:57.206   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-02 19:06:57.216   873  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-02 19:06:57.216   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-02 19:06:57.218   396   396 E Parcel  : Reading a NULL string not supported here.
,09-02 19:06:57.219   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 19:06:57.220   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-02 19:06:57.221   873  4108 D DhcpClient: Receive thread stopped
,09-02 19:06:57.229   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-02 19:06:57.232   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 19:06:57.236  1851  2251 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:06:57.236   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-02 19:06:57.238  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:57.238  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:57.238  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:57.238  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:06:57.239  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:06:57.240  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:06:57.240  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:06:57.240  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:06:57.268   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:06:57.291   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:06:57.292   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 19:06:57.292   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:57.296  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:57.297   873   890 D Tethering: MasterInitialState.processMessage what=3
09-02 19:06:57.298  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:06:57.305  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-02 19:06:57.309  1697  1697 D SystemUpdateService: onCreate
09-02 19:06:57.312  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 19:06:57.323  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 19:06:57.327  1697  2456 I iu.UploadsManager: num queued entries: 0
,09-02 19:06:57.333  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 19:06:57.335  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 19:06:57.337  1697  2456 I iu.UploadsManager: num updated entries: 0
,09-02 19:06:57.338  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:06:57.344  1697  4174 I SystemUpdateService: active receiver: enabled
,09-02 19:06:57.345  4005  4005 D SprintDMHelper: simOperator: 
09-02 19:06:57.345  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 19:06:57.366   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-02 19:06:57.367   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 19:06:57.367   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 19:06:57.387  3963  4179 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-02 19:06:57.393  1697  4174 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 19:06:57.395  1697  2456 I iu.SyncManager: NEXT; no task
,09-02 19:06:57.405  1697  4174 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 19:06:57.405  1697  4174 I SystemUpdateService: now status is 0 (complete)
09-02 19:06:57.405  1697  4174 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 19:06:57.405  1697  4174 I SystemUpdateService: file has been verified
09-02 19:06:57.405  1697  4174 I SystemUpdateService: OTA package size = 12249756
,09-02 19:06:57.414  1697  4174 I SystemUpdateService: showing system update notification
,09-02 19:06:57.433  1697  1697 D SystemUpdateService: onDestroy
,09-02 19:07:00.158   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@396779a:true
,09-02 19:07:00.160  3990  3990 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 19:07:00.168  3990  4181 I BluetoothAdapterState: Entering OffState
,09-02 19:07:00.168  3990  3990 I bt_bluedroid: init
,09-02 19:07:00.173  3990  4182 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 19:07:00.173  3990  4182 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 19:07:00.173  3990  4182 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 19:07:00.174  3990  4182 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 19:07:00.176  3990  3990 I bt_bluedroid: get_profile_interface socket
,09-02 19:07:00.180  3990  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 19:07:00.181  3990  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 19:07:00.184  3990  3990 I bt_bluedroid: get_profile_interface sdp
,09-02 19:07:00.190  3990  4001 I bt_bluedroid: config_hci_snoop_log
,09-02 19:07:00.192   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 19:07:00.198  3990  4181 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 19:07:00.198  3990  4181 D BluetoothAdapterProperties: Setting state to 14
09-02 19:07:00.198  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 19:07:00.200  3990  4181 D BluetoothBondStateMachine: make
,09-02 19:07:00.203  3990  4186 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 19:07:00.207  3990  4181 I BluetoothAdapterState: Entering PendingCommandState
,09-02 19:07:00.208  3990  3990 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 19:07:00.213  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:00.213  3990  3990 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:07:00.214  3990  3990 D BtGatt.GattService: Received start request. Starting profile...
,09-02 19:07:00.214  3990  3990 D BtGatt.GattService: start()
,09-02 19:07:00.215  3990  3990 I bt_bluedroid: get_profile_interface gatt
,09-02 19:07:00.216  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
09-02 19:07:00.216  3990  3990 D BtGatt.AdvertiseManager: advertise manager created
,09-02 19:07:00.225  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:00.225  3990  3990 V BluetoothAdapterState: isTurningOn()=false
,09-02 19:07:00.225  3990  3990 V BluetoothAdapterState: isBleTurningOn()=true
09-02 19:07:00.225  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:00.225  3990  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-02 19:07:00.225  3990  4181 I bt_bluedroid: enable
,09-02 19:07:00.226  3990  4182 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-02 19:07:00.226  3990  4182 I bt_hci  : start_up
,09-02 19:07:00.235  3990  4182 I bt_vendor: alloc value 0xb3979189
,09-02 19:07:00.236  3990  4182 I bt_vendor: init
09-02 19:07:00.236  3990  4182 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-02 19:07:00.236  3990  4182 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 19:07:00.341  3990  4182 D bt_hci  : start_up starting async portion
,09-02 19:07:00.342  3990  4189 I bt_hci  : event_finish_startup
09-02 19:07:00.342  3990  4189 I bt_hci_h4: hal_open
,09-02 19:07:00.342  3990  4189 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 19:07:00.348  3990  4189 I bt_userial_vendor: device fd = 51 open
,09-02 19:07:00.385  3990  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 19:07:00.400  4124  4147 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-02 19:07:00.418  3990  4189 D bt_hwcfg: Chipset BCM4354A2
,09-02 19:07:00.419  3990  4189 D bt_hwcfg: Target name = [BCM4354A2]
,09-02 19:07:00.419  3990  4189 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 19:07:01.029  3990  4189 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 19:07:01.030  3990  4189 D bt_hwcfg: Settlement delay -- 100 ms
09-02 19:07:01.031  3990  4189 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 19:07:01.147  3990  4189 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-02 19:07:01.149  3990  4189 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 19:07:01.178  3990  4189 I bt_hwcfg: vendor lib fwcfg completed
,09-02 19:07:01.179  3990  4189 I bt_vendor: firmware callback
09-02 19:07:01.179  3990  4189 I bt_hci  : firmware_config_callback
,09-02 19:07:01.192  3990  4193 I bt_btu  : btu_task pending for preload complete event
,09-02 19:07:01.192  3990  4193 I bt_btu_task: Bluetooth chip preload is complete
,09-02 19:07:01.192  3990  4193 I bt_btu  : btu_task received preload complete event
,09-02 19:07:01.202  3990  4193 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 19:07:01.202  3990  4193 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 19:07:01.203  3990  4193 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 19:07:01.203  3990  4193 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-02 19:07:01.203  3990  4193 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 19:07:01.204  3990  4193 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 19:07:01.204  3990  4193 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-02 19:07:01.204  3990  4193 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 19:07:01.204  3990  4193 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 19:07:01.205  3990  4193 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 19:07:01.205  3990  4193 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 19:07:01.205  3990  4193 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 19:07:01.205  3990  4193 I         : BTE_InitTraceLevels -- TRC_SMP
,09-02 19:07:01.206  3990  4193 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 19:07:01.206  3990  4193 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 19:07:01.345  3990  4193 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,09-02 19:07:01.345  3990  4193 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,09-02 19:07:01.357  3990  4185 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 19:07:01.358  3990  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 19:07:01.359  3990  4185 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 19:07:01.364  3990  4185 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 19:07:01.370  3990  4185 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:07:01.371  3990  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:07:01.372  3990  4185 D bt_hci  : do_postload posting postload work item
,09-02 19:07:01.372  3990  4189 I bt_hci  : event_postload
09-02 19:07:01.372  3990  4189 I bt_vendor: sco_config_cb
09-02 19:07:01.372  3990  4189 I bt_hci  : sco_config_callback postload finished.
09-02 19:07:01.374  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:01.379  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:01.380  3990  4185 D bt_bte_conf: Device ID record 1 : primary
09-02 19:07:01.381  3990  4185 D bt_bte_conf:   vendorId            = 000f
09-02 19:07:01.382  3990  4185 D bt_bte_conf:   vendorIdSource      = 0001
,09-02 19:07:01.382  3990  4185 D bt_bte_conf:   product             = 1200
09-02 19:07:01.383  3990  4185 D bt_bte_conf:   version             = 1436
,09-02 19:07:01.383  3990  4185 D bt_bte_conf:   clientExecutableURL = 
,09-02 19:07:01.383  3990  4185 D bt_bte_conf:   serviceDescription  = 
09-02 19:07:01.383  3990  4189 I bt_vendor: low_power_mode_cb
,09-02 19:07:01.383  3990  4185 D bt_bte_conf:   documentationURL    = 
09-02 19:07:01.384  3990  4185 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-02 19:07:01.385  3990  4182 D bt_stack_manager: event_start_up_stack finished
09-02 19:07:01.387  3990  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-02 19:07:01.387  3990  4181 D BluetoothAdapterProperties: Setting state to 15
09-02 19:07:01.387  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-02 19:07:01.388  3990  4181 I BluetoothAdapterState: Entering BleOnState
09-02 19:07:01.390  3990  4181 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-02 19:07:01.390  3990  4181 D BluetoothAdapterProperties: Setting state to 11
09-02 19:07:01.390  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-02 19:07:01.395  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:01.396  3990  3990 D HeadsetService: Received start request. Starting profile...
,09-02 19:07:01.404  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:01.405  3990  3990 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 19:07:01.405  3990  3990 D HeadsetStateMachine: make
09-02 19:07:01.406  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:01.410  3990  4181 I BluetoothAdapterState: Entering PendingCommandState
,09-02 19:07:01.415  3990  3990 D HeadsetStateMachine: max_hf_connections = 1,
09-02 19:07:01.415  3990  3990 I bt_bluedroid: get_profile_interface handsfree
09-02 19:07:01.415  3990  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 19:07:01.415  3990  4185 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-02 19:07:01.419  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:01.420  3990  3990 D A2dpService: Received start request. Starting profile...
,09-02 19:07:01.421  3990  3990 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 19:07:01.421  3990  3990 I bt_bluedroid: get_profile_interface avrcp
,09-02 19:07:01.427  3990  3990 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 19:07:01.428  3990  3990 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-02 19:07:01.428  3990  3990 D A2dpStateMachine: make
09-02 19:07:01.429  3990  3990 I bt_bluedroid: get_profile_interface a2dp
,09-02 19:07:01.430  3990  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-02 19:07:01.433  3990  4203 D A2dpStateMachine: Enter Disconnected: -2
,09-02 19:07:01.436  3990  3990 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 19:07:01.437  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
09-02 19:07:01.438  3890  3890 D BluetoothInputDevice: Proxy object connected
,09-02 19:07:01.439  3890  3890 D HidProfile: Bluetooth service connected
09-02 19:07:01.440  3990  3990 D HidService: Received start request. Starting profile...
09-02 19:07:01.440  3990  3990 I bt_bluedroid: get_profile_interface hidhost
09-02 19:07:01.440  3990  3990 D HidService: setHidService(): set to: null
09-02 19:07:01.440  3990  4185 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
09-02 19:07:01.440  3990  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-02 19:07:01.441  3990  3990 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 19:07:01.442  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:01.442  3990  3990 D HealthService: Received start request. Starting profile...
,09-02 19:07:01.445  3990  3990 I bt_bluedroid: get_profile_interface health
09-02 19:07:01.445  3990  3990 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 19:07:01.446  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:01.447  3990  3990 D PanService: Received start request. Starting profile...
,09-02 19:07:01.447  3990  3990 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-02 19:07:01.447  3990  3990 I bt_bluedroid: get_profile_interface pan
,09-02 19:07:01.448  3990  4185 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 19:07:01.448  3890  3890 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:07:01.449  3890  3890 D PanProfile: Bluetooth service connected
09-02 19:07:01.450  3990  3990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:01.452  3990  3990 D BluetoothMapService: Received start request. Starting profile...
,09-02 19:07:01.452  3990  3990 D BluetoothMapService: start()
,09-02 19:07:01.453  3890  3890 D BluetoothMap: Proxy object connected
09-02 19:07:01.453  3890  3890 D MapProfile: Bluetooth service connected
,09-02 19:07:01.454  3890  3890 D BluetoothMap: getConnectedDevices()
09-02 19:07:01.454  3990  3990 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
,09-02 19:07:01.454  3890  3890 D BluetoothMap: Bluetooth is Not enabled
09-02 19:07:01.455  3990  3990 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-02 19:07:01.455  3990  3990 D BluetoothMapAppObserver: createReceiver()
,09-02 19:07:01.456  3990  3990 D BluetoothMapAppObserver: initObservers()
,09-02 19:07:01.456  3990  3990 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 19:07:01.464  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:01.465  3990  3990 V BluetoothAdapterState: isTurningOff()=false
09-02 19:07:01.465  3990  3990 V BluetoothAdapterState: isTurningOn()=true
,09-02 19:07:01.465  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:01.465  3990  4201 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 19:07:01.465  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isTurningOn()=true
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isTurningOn()=true
09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isTurningOn()=true
,09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:01.467  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isTurningOff()=false
09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isTurningOn()=true
,09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isTurningOff()=false
09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isTurningOn()=true
09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:01.468  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:01.468  3990  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-02 19:07:01.468  3990  4181 D BluetoothAdapterProperties: ScanMode =  20
09-02 19:07:01.468  3990  4181 D BluetoothAdapterProperties: State =  11
09-02 19:07:01.474  3990  4185 D BluetoothAdapterProperties: Scan Mode:21
09-02 19:07:01.475  3990  4185 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:07:01.475  3990  4181 D BluetoothAdapterProperties: Setting state to 12
09-02 19:07:01.475  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 19:07:01.475  3990  4181 I BluetoothAdapterState: Entering OnState
09-02 19:07:01.475  1361  2117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:01.476  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:01.477  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:01.478  1361  1361 D BluetoothInputDevice: Proxy object connected
,09-02 19:07:01.478  1361  1361 D HidProfile: Bluetooth service connected
09-02 19:07:01.478   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:01.478  3890  3900 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:07:01.479  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:01.480   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 19:07:01.480  1361  1378 D BluetoothPan: onBluetoothStateChange on: true
,09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:01.482  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:01.482  3990  3990 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 19:07:01.482  1361  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:07:01.483  3990  3990 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-02 19:07:01.483  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:07:01.484  1361  1361 D PanProfile: Bluetooth service connected
,09-02 19:07:01.484  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:01.484  3990  3990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:01.485  1985  2007 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 19:07:01.486  3890  3902 D BluetoothPan: onBluetoothStateChange on: true
,09-02 19:07:01.486   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:07:01.486  3990  3990 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:07:01.487  3890  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 19:07:01.487   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:01.487  1361  1378 D BluetoothMap: onBluetoothStateChange: up=true
09-02 19:07:01.488  3990  3990 D ObexServerSockets: Succeed to create listening sockets 
09-02 19:07:01.488  3990  3990 D ObexServerSockets0: startAccept()
,09-02 19:07:01.488  3990  3990 D ObexServerSockets0: prepareForNewConnect()
,09-02 19:07:01.489  1361  1361 D BluetoothMap: Proxy object connected
,09-02 19:07:01.489  1361  1361 D MapProfile: Bluetooth service connected
09-02 19:07:01.489  1361  1361 D BluetoothMap: getConnectedDevices()
,09-02 19:07:01.489  1361  1381 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:07:01.490  3990  3990 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 19:07:01.490  3990  3990 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-02 19:07:01.491   873   873 D BluetoothA2dp: Proxy object connected
,09-02 19:07:01.491  1361  1361 D BluetoothA2dp: Proxy object connected
09-02 19:07:01.491  3890  3902 D BluetoothMap: onBluetoothStateChange: up=true
09-02 19:07:01.492  3990  4208 D ObexServerSockets0: Accepting socket connection...
,09-02 19:07:01.493  3990  4209 D ObexServerSockets0: Accepting socket connection...
09-02 19:07:01.495   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 19:07:01.495  3990  3990 D BluetoothMapService: onReceive
09-02 19:07:01.495  3990  3990 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:01.495  3990  3990 D BluetoothMapService: STATE_ON
09-02 19:07:01.495  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:01.497  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:01.498  3890  3890 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-02 19:07:01.502  3890  3890 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-02 19:07:01.508  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:07:01.510  3890  3890 D BluetoothA2dp: Proxy object connected
,09-02 19:07:01.515  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:01.518  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:01.524  3990  3990 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 19:07:01.524  3890  3890 D BluetoothPbap: Proxy object connected
09-02 19:07:01.524  1361  1361 D BluetoothPbap: Proxy object connected
09-02 19:07:01.524  3990  3990 D ObexServerSockets0: prepareForNewConnect()
09-02 19:07:01.524  1361  1361 D PbapServerProfile: Bluetooth service connected
09-02 19:07:01.524  3890  3890 D PbapServerProfile: Bluetooth service connected
,09-02 19:07:01.535  3990  4214 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:01.551  3990  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:01.553  3990  4218 I BtOppRfcommListener: Accept thread started.
,09-02 19:07:01.578  1361  1378 D BluetoothHeadset: Proxy object connected
,09-02 19:07:01.579   873   873 D BluetoothHeadset: Proxy object connected
09-02 19:07:01.579   873   873 D BluetoothHeadset: Proxy object connected
,09-02 19:07:01.579  1361  1361 D HeadsetProfile: Bluetooth service connected
09-02 19:07:01.579   873   873 D BluetoothHeadset: Proxy object connected
,09-02 19:07:01.579  1985  2292 D BluetoothHeadset: Proxy object connected
09-02 19:07:01.580   873   890 D BluetoothHeadset: Proxy object connected
,09-02 19:07:01.586  1985  1998 D BluetoothHeadset: Proxy object connected
,09-02 19:07:01.587   873   890 D BluetoothHeadset: Proxy object connected
,09-02 19:07:01.605  3890  3900 D BluetoothHeadset: Proxy object connected
09-02 19:07:01.606  3890  3890 D HeadsetProfile: Bluetooth service connected
,09-02 19:07:03.068   873  1305 D ConnectivityService: handlePromptUnvalidated 101
,09-02 19:07:03.138  3990  4181 D BluetoothAdapterState: Current state: ON, message: 23
,09-02 19:07:03.139  3990  4181 D BluetoothAdapterProperties: Setting state to 13
,09-02 19:07:03.139  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 19:07:03.143  3990  4181 D BluetoothAdapterProperties: onBluetoothDisable()
,09-02 19:07:03.149  3990  3990 D BluetoothMapService: onReceive
,09-02 19:07:03.149  3990  3990 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:03.149  3990  3990 D BluetoothMapService: STATE_TURNING_OFF
09-02 19:07:03.149  3990  3990 D BluetoothMapService: MAP Service closeService in
,09-02 19:07:03.149  3990  3990 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 19:07:03.150  3990  3990 D ObexServerSockets0: shutdown(block = true)
09-02 19:07:03.150  3990  3990 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 19:07:03.151  3990  3990 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 19:07:03.151  3990  4196 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-02 19:07:03.152  3990  4209 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-02 19:07:03.154  3990  4185 D BluetoothAdapterProperties: Scan Mode:20
09-02 19:07:03.155  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:07:03.155  3990  4208 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:03.155  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:03.156  3990  3990 I BtOppRfcommListener: stopping Accept Thread
,09-02 19:07:03.156  3990  4218 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-02 19:07:03.153  3990  4181 I BluetoothAdapterState: Entering PendingCommandState
09-02 19:07:03.156  3990  4218 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 19:07:03.156  3990  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-02 19:07:03.157  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:03.157  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:03.161  3990  3990 D HeadsetService: Received stop request...Stopping profile...
,09-02 19:07:03.163  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:03.163  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:03.165  3990  3990 V BluetoothAdapterState: isTurningOff()=true
,09-02 19:07:03.165  3990  3990 V BluetoothAdapterState: isTurningOn()=false
,09-02 19:07:03.166  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:03.166  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:03.166  3822  3822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:03.166  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:03.169  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.169  1361  1378 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:03.170  3990  3990 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 19:07:03.170  3990  3990 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:07:03.170  3990  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-02 19:07:03.170  3890  3902 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:03.171   873   873 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:03.171  3990  4193 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:07:03.171   873   873 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:03.171   873   873 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:03.171  3990  4193 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 19:07:03.171  3990  4193 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:07:03.171  1985  2005 D BluetoothHeadset: Proxy object disconnected
09-02 19:07:03.171  3990  3990 D A2dpService: Received stop request...Stopping profile...
09-02 19:07:03.172  3990  4185 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-02 19:07:03.172  3990  4203 D A2dpStateMachine: Exit Disconnected: -1
,09-02 19:07:03.172  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 19:07:03.173  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.177  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-02 19:07:03.177   873   873 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:03.178  3990  3990 V BluetoothAdapterState: isTurningOff()=true
,09-02 19:07:03.178  3990  3990 V BluetoothAdapterState: isTurningOn()=false
09-02 19:07:03.178  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:03.178  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:03.179  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:03.180  3990  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 19:07:03.180  3990  4193 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:07:03.180  3990  4193 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 19:07:03.180  3990  4193 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 19:07:03.180  3990  4193 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-02 19:07:03.180  3990  4193 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:03.180  3990  4193 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:03.181  3890  3890 D HeadsetProfile: Bluetooth service disconnected
09-02 19:07:03.184  3990  3990 D HidService: Received stop request...Stopping profile...
09-02 19:07:03.185  3990  3990 D HidService: Stopping Bluetooth HidService
09-02 19:07:03.186  1361  1361 D BluetoothInputDevice: Proxy object disconnected
,09-02 19:07:03.187  3990  3990 D HealthService: Received stop request...Stopping profile...
09-02 19:07:03.186  1361  1361 D HidProfile: Bluetooth service disconnected
09-02 19:07:03.188  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:03.189  3990  3990 D PanService: Received stop request...Stopping profile...
09-02 19:07:03.191  3990  3990 D BluetoothMapService: Received stop request...Stopping profile...
09-02 19:07:03.191  3990  3990 D BluetoothMapService: stop()
09-02 19:07:03.191  3990  3990 D BluetoothMapAppObserver: deinitObservers()
,09-02 19:07:03.191  3990  3990 D BluetoothMapAppObserver: removeReceiver()
09-02 19:07:03.191  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 19:07:03.191  1361  1361 D PanProfile: Bluetooth service disconnected
09-02 19:07:03.192  1361  1361 D BluetoothMap: Proxy object disconnected
09-02 19:07:03.192  1361  1361 D MapProfile: Bluetooth service disconnected
,09-02 19:07:03.193  3990  3990 V BluetoothAdapterState: isTurningOff()=true
09-02 19:07:03.193  3990  3990 V BluetoothAdapterState: isTurningOn()=false
09-02 19:07:03.193  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:03.193  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:03.193  3990  3990 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 19:07:03.193  3990  4185 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 19:07:03.193  3990  3990 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 19:07:03.194  3890  3890 D DockEventReceiver: finishStartingService: stopping service
09-02 19:07:03.194  1361  1361 D BluetoothPbap: Proxy object disconnected
,09-02 19:07:03.195  1361  1361 D PbapServerProfile: Bluetooth service disconnected
09-02 19:07:03.195  3990  3990 V BluetoothAdapterState: isTurningOff()=true
09-02 19:07:03.195  3990  3990 V BluetoothAdapterState: isTurningOn()=false
09-02 19:07:03.195  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:03.195  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:03.195  3990  3990 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:07:03.195  3990  4185 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 19:07:03.196  3890  3890 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:03.197  3990  3990 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:07:03.197  3990  3990 V BluetoothAdapterState: isTurningOff()=true
,09-02 19:07:03.198  3990  3990 V BluetoothAdapterState: isTurningOn()=false
09-02 19:07:03.198  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:03.198  3890  3890 D BluetoothInputDevice: Proxy object disconnected
09-02 19:07:03.198  3890  3890 D HidProfile: Bluetooth service disconnected
09-02 19:07:03.199  3890  3890 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 19:07:03.199  3890  3890 D PanProfile: Bluetooth service disconnected
,09-02 19:07:03.200  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:03.200  3890  3890 D BluetoothMap: Proxy object disconnected
09-02 19:07:03.200  3890  3890 D MapProfile: Bluetooth service disconnected
09-02 19:07:03.200  3990  3990 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 19:07:03.200  3990  3990 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 19:07:03.204  3990  3990 D BluetoothMapService: MAP Service closeService in
,09-02 19:07:03.204  3990  3990 V BluetoothAdapterState: isTurningOff()=true
09-02 19:07:03.204  3990  3990 V BluetoothAdapterState: isTurningOn()=false
,09-02 19:07:03.205  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:03.205  3990  3990 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:03.205  3990  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 19:07:03.205  3990  4181 D BluetoothAdapterProperties: Setting state to 15
09-02 19:07:03.205  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 19:07:03.205  3990  3990 D BluetoothMapService: cleanup()
09-02 19:07:03.205  3990  3990 D BluetoothMapService: MAP Service closeService in
09-02 19:07:03.206  1361  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 19:07:03.206  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 19:07:03.206  3990  4181 I BluetoothAdapterState: Entering BleOnState
,09-02 19:07:03.207   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:03.207  3890  3902 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 19:07:03.207   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:03.208  1361  1374 D BluetoothPan: onBluetoothStateChange on: false
09-02 19:07:03.208  1361  2117 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:03.209  1985  2007 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 19:07:03.209  3890  3900 D BluetoothPan: onBluetoothStateChange on: false
09-02 19:07:03.210   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:03.210  3890  3902 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 19:07:03.211   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 19:07:03.212  1361  1378 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 19:07:03.212  3890  3900 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 19:07:03.212  1361  1381 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 19:07:03.213  3890  3902 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 19:07:03.213  3890  3900 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:03.214  3990  4181 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-02 19:07:03.214  3990  4181 D BluetoothAdapterProperties: Setting state to 16
09-02 19:07:03.214  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-02 19:07:03.215  3990  4181 D BluetoothAdapterProperties: onBleDisable
,09-02 19:07:03.215  3990  4181 I BluetoothAdapterState: Entering PendingCommandState
09-02 19:07:03.215  3990  4182 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 19:07:03.216  3990  4193 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 19:07:03.216  3990  4193 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 19:07:03.218  3990  4185 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:07:03.219  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.220  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:03.220  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 19:07:03.222  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:03.223  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:03.226  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:03.230  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:03.421  3990  4185 I bt_hci  : shut_down
,09-02 19:07:03.422  3990  4189 D bt_hwcfg: hw_epilog_process
,09-02 19:07:03.442  3990  4189 I bt_vendor: low_power_mode_cb
,09-02 19:07:03.459  3990  4189 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 19:07:03.459  3990  4189 I bt_vendor: epilog_cb
09-02 19:07:03.459  3990  4189 I bt_hci  : epilog_finished_callback
,09-02 19:07:03.463  3990  4185 I bt_hci_h4: hal_close
,09-02 19:07:03.464  3990  4185 I bt_userial_vendor: device fd = 51 close
,09-02 19:07:03.576  3990  4182 D bt_stack_manager: event_shut_down_stack finished.
,09-02 19:07:03.577  3990  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 19:07:03.583  3990  4181 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-02 19:07:03.584  3990  3990 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:07:03.585  3990  3990 D BtGatt.GattService: Received stop request...Stopping profile...
,09-02 19:07:03.586  3990  3990 D BtGatt.GattService: stop()
,09-02 19:07:03.586  3990  3990 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 19:07:03.590  3990  3990 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:03.591  3990  3990 V BluetoothAdapterState: isTurningOn()=false
09-02 19:07:03.591  3990  3990 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:03.592  3990  3990 V BluetoothAdapterState: isBleTurningOff()=true
09-02 19:07:03.593  3990  4181 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-02 19:07:03.593  3990  4181 D BluetoothAdapterProperties: Setting state to 10
09-02 19:07:03.594  3990  4181 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-02 19:07:03.595  3990  4181 I BluetoothAdapterState: Entering OffState
09-02 19:07:03.596   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-02 19:07:03.612  3990  3990 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-02 19:07:03.612  3990  3990 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-02 19:07:03.612  3990  3990 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 19:07:03.613  3990  4182 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-02 19:07:03.617  3990  4182 D bt_stack_manager: event_clean_up_stack finished.
,09-02 19:07:03.620  3990  3990 I art     : System.exit called, status: 0
,09-02 19:07:03.620  3990  3990 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 19:07:03.680   873  2048 I ActivityManager: Process com.android.bluetooth (pid 3990) has died
,09-02 19:07:05.479  3529  3540 D Finsky  : [269] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-02 19:07:05.496  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:07:05.513  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:07:05.518  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:07:05.595  1504  2104 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-02 19:07:05.596  1504  2104 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-02 19:07:05.596  1504  2104 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:07:05.596  1504  2104 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:07:05.655  3529  3540 D Finsky  : [269] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-02 19:07:06.136  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:07:06.136  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:09.144  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:09.144  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fda4e5a added. We now have 6 listener(s)
,09-02 19:07:09.145  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:09.148  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:09.149  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@76ef88b added. We now have 7 listener(s)
,09-02 19:07:09.149  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:09.151  3822  3872 I System.out: IsBluetoothEnabled
,09-02 19:07:09.162  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:09.204   873   890 I ActivityManager: Start proc 4231:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 19:07:09.344  4231  4231 D AdapterServiceConfig: Adding HeadsetService
,09-02 19:07:09.344  4231  4231 D AdapterServiceConfig: Adding A2dpService
09-02 19:07:09.344  4231  4231 D AdapterServiceConfig: Adding HidService
09-02 19:07:09.345  4231  4231 D AdapterServiceConfig: Adding HealthService
,09-02 19:07:09.345  4231  4231 D AdapterServiceConfig: Adding PanService
,09-02 19:07:09.345  4231  4231 D AdapterServiceConfig: Adding GattService
,09-02 19:07:09.345  4231  4231 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 19:07:09.363   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed5f0f1:true
,09-02 19:07:09.365  4231  4231 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 19:07:09.374  4231  4231 I bt_bluedroid: init
,09-02 19:07:09.374  4231  4243 I BluetoothAdapterState: Entering OffState
,09-02 19:07:09.377  4231  4244 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 19:07:09.377  4231  4244 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-02 19:07:09.377  4231  4244 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-02 19:07:09.377  4231  4244 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 19:07:09.379  4231  4231 I bt_bluedroid: get_profile_interface socket
09-02 19:07:09.381  4231  4231 I bt_bluedroid: get_profile_interface sdp
,09-02 19:07:09.386  4231  4247 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-02 19:07:09.389  4231  4247 D BluetoothAdapterProperties: Name is: Nexus 6
09-02 19:07:09.389  4231  4241 I bt_bluedroid: config_hci_snoop_log
,09-02 19:07:09.392   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 19:07:09.400  4231  4243 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 19:07:09.400  4231  4243 D BluetoothAdapterProperties: Setting state to 14
,09-02 19:07:09.401  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 19:07:09.404  4231  4243 D BluetoothBondStateMachine: make
,09-02 19:07:09.408  4231  4248 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 19:07:09.416  4231  4243 I BluetoothAdapterState: Entering PendingCommandState
,09-02 19:07:09.416  4231  4231 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 19:07:09.424  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:09.426  4231  4231 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 19:07:09.427  4231  4231 D BtGatt.GattService: Received start request. Starting profile...
,09-02 19:07:09.427  4231  4231 D BtGatt.GattService: start()
09-02 19:07:09.428  4231  4231 I bt_bluedroid: get_profile_interface gatt
,09-02 19:07:09.430  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:09.430  4231  4231 D BtGatt.AdvertiseManager: advertise manager created
,09-02 19:07:09.444  4231  4231 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:09.444  4231  4231 V BluetoothAdapterState: isTurningOn()=false
,09-02 19:07:09.445  4231  4231 V BluetoothAdapterState: isBleTurningOn()=true
09-02 19:07:09.445  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:09.446  4231  4243 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-02 19:07:09.447  4231  4243 I bt_bluedroid: enable
09-02 19:07:09.448  4231  4244 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-02 19:07:09.449  4231  4244 I bt_hci  : start_up
,09-02 19:07:09.472  4231  4244 I bt_vendor: alloc value 0xb39ea189
09-02 19:07:09.473  4231  4244 I bt_vendor: init
09-02 19:07:09.473  4231  4244 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-02 19:07:09.473  4231  4244 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 19:07:09.584  4231  4244 D bt_hci  : start_up starting async portion
,09-02 19:07:09.584  4231  4251 I bt_hci  : event_finish_startup
09-02 19:07:09.585  4231  4251 I bt_hci_h4: hal_open
09-02 19:07:09.586  4231  4251 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 19:07:09.595  4231  4251 I bt_userial_vendor: device fd = 51 open
,09-02 19:07:09.625  4231  4251 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 19:07:09.657  4231  4251 D bt_hwcfg: Chipset BCM4354A2
,09-02 19:07:09.658  4231  4251 D bt_hwcfg: Target name = [BCM4354A2]
,09-02 19:07:09.658  4231  4251 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 19:07:10.340  4231  4251 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-02 19:07:10.342  4231  4251 D bt_hwcfg: Settlement delay -- 100 ms
09-02 19:07:10.342  4231  4251 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 19:07:10.459  4231  4251 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-02 19:07:10.460  4231  4251 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 19:07:10.490  4231  4251 I bt_hwcfg: vendor lib fwcfg completed
,09-02 19:07:10.490  4231  4251 I bt_vendor: firmware callback
09-02 19:07:10.491  4231  4251 I bt_hci  : firmware_config_callback
,09-02 19:07:10.504  4231  4253 I bt_btu  : btu_task pending for preload complete event
,09-02 19:07:10.504  4231  4253 I bt_btu_task: Bluetooth chip preload is complete
09-02 19:07:10.505  4231  4253 I bt_btu  : btu_task received preload complete event
,09-02 19:07:10.517  4231  4253 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 19:07:10.517  4231  4253 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 19:07:10.518  4231  4253 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-02 19:07:10.518  4231  4253 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 19:07:10.518  4231  4253 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 19:07:10.519  4231  4253 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 19:07:10.519  4231  4253 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-02 19:07:10.519  4231  4253 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 19:07:10.519  4231  4253 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 19:07:10.519  4231  4253 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 19:07:10.520  4231  4253 I         : BTE_InitTraceLevels -- TRC_SDP
,09-02 19:07:10.520  4231  4253 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 19:07:10.520  4231  4253 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 19:07:10.520  4231  4253 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 19:07:10.521  4231  4253 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 19:07:10.652  4231  4253 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3967d9d
,09-02 19:07:10.652  4231  4253 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3967d9d 
,09-02 19:07:10.690  4231  4247 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 19:07:10.692  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 19:07:10.692  4231  4247 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 19:07:10.695  4231  4247 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 19:07:10.699  4231  4247 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:07:10.699  4231  4247 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 19:07:10.699  4231  4247 D bt_hci  : do_postload posting postload work item
,09-02 19:07:10.701  4231  4251 I bt_hci  : event_postload
,09-02 19:07:10.701  4231  4251 I bt_vendor: sco_config_cb
09-02 19:07:10.701  4231  4251 I bt_hci  : sco_config_callback postload finished.
,09-02 19:07:10.701  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:10.703  4231  4247 D bt_bte_conf: Device ID record 1 : primary
09-02 19:07:10.704  4231  4247 D bt_bte_conf:   vendorId            = 000f
09-02 19:07:10.704  4231  4247 D bt_bte_conf:   vendorIdSource      = 0001
09-02 19:07:10.704  4231  4247 D bt_bte_conf:   product             = 1200
09-02 19:07:10.705  4231  4247 D bt_bte_conf:   version             = 1436
09-02 19:07:10.705  4231  4247 D bt_bte_conf:   clientExecutableURL = 
,09-02 19:07:10.705  4231  4247 D bt_bte_conf:   serviceDescription  = 
09-02 19:07:10.705  4231  4247 D bt_bte_conf:   documentationURL    = 
,09-02 19:07:10.706  4231  4247 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-02 19:07:10.706  4231  4244 D bt_stack_manager: event_start_up_stack finished
09-02 19:07:10.707  4231  4243 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-02 19:07:10.707  4231  4243 D BluetoothAdapterProperties: Setting state to 15
09-02 19:07:10.708  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-02 19:07:10.708  4231  4251 I bt_vendor: low_power_mode_cb
,09-02 19:07:10.709  4231  4243 I BluetoothAdapterState: Entering BleOnState
,09-02 19:07:10.713  4231  4243 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-02 19:07:10.713  4231  4243 D BluetoothAdapterProperties: Setting state to 11
,09-02 19:07:10.713  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-02 19:07:10.722  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
09-02 19:07:10.723  4231  4231 D HeadsetService: Received start request. Starting profile...
,09-02 19:07:10.728  4231  4231 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 19:07:10.728  4231  4231 D HeadsetStateMachine: make
,09-02 19:07:10.729  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:10.746  4231  4231 D HeadsetStateMachine: max_hf_connections = 1
,09-02 19:07:10.746  4231  4231 I bt_bluedroid: get_profile_interface handsfree
,09-02 19:07:10.747  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 19:07:10.747  4231  4247 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-02 19:07:10.752  4231  4243 I BluetoothAdapterState: Entering PendingCommandState
09-02 19:07:10.752  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
09-02 19:07:10.752  4231  4231 D A2dpService: Received start request. Starting profile...
09-02 19:07:10.753  4231  4231 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 19:07:10.753  4231  4231 I bt_bluedroid: get_profile_interface avrcp
,09-02 19:07:10.760  4231  4231 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 19:07:10.760  4231  4231 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-02 19:07:10.760  4231  4231 D A2dpStateMachine: make
,09-02 19:07:10.761  4231  4231 I bt_bluedroid: get_profile_interface a2dp
09-02 19:07:10.762  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-02 19:07:10.766  4231  4262 D A2dpStateMachine: Enter Disconnected: -2
,09-02 19:07:10.769  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:10.769  4231  4231 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 19:07:10.770  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:10.771  4231  4231 D HidService: Received start request. Starting profile...
09-02 19:07:10.771  4231  4231 I bt_bluedroid: get_profile_interface hidhost
09-02 19:07:10.771  4231  4231 D HidService: setHidService(): set to: null
09-02 19:07:10.771  4231  4247 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39493e5
,09-02 19:07:10.771  4231  4247 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-02 19:07:10.772  4231  4231 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 19:07:10.773  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
09-02 19:07:10.774  4231  4231 D HealthService: Received start request. Starting profile...
,09-02 19:07:10.775  4231  4231 I bt_bluedroid: get_profile_interface health
,09-02 19:07:10.776  4231  4231 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 19:07:10.777  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:10.777  4231  4231 D PanService: Received start request. Starting profile...
,09-02 19:07:10.778  4231  4231 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 19:07:10.778  4231  4231 I bt_bluedroid: get_profile_interface pan
09-02 19:07:10.778  4231  4247 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 19:07:10.786  4231  4231 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:10.786  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-02 19:07:10.786  4231  4260 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 19:07:10.786  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:10.786  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 19:07:10.789  4231  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:10.790  4231  4231 D BluetoothMapService: Received start request. Starting profile...
,09-02 19:07:10.790  4231  4231 D BluetoothMapService: start()
,09-02 19:07:10.792  4231  4231 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 19:07:10.792  4231  4231 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-02 19:07:10.792  4231  4231 D BluetoothMapAppObserver: createReceiver()
09-02 19:07:10.793  4231  4231 D BluetoothMapAppObserver: initObservers()
09-02 19:07:10.793  4231  4231 D BluetoothMapAppObserver: getEnabledAccountItems()
09-02 19:07:10.799  4231  4231 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:10.799  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-02 19:07:10.799  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:10.799  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:10.800  4231  4231 V BluetoothAdapterState: isTurningOff()=false
09-02 19:07:10.800  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-02 19:07:10.800  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 19:07:10.800  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:10.800  4231  4231 V BluetoothAdapterState: isTurningOff()=false
09-02 19:07:10.800  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-02 19:07:10.800  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:10.801  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:10.801  4231  4231 V BluetoothAdapterState: isTurningOff()=false
,09-02 19:07:10.801  4231  4231 V BluetoothAdapterState: isTurningOn()=true
09-02 19:07:10.801  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:10.801  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:10.802  4231  4231 V BluetoothAdapterState: isTurningOff()=false
09-02 19:07:10.802  4231  4231 V BluetoothAdapterState: isTurningOn()=true
,09-02 19:07:10.802  4231  4231 V BluetoothAdapterState: isBleTurningOn()=false
09-02 19:07:10.802  4231  4231 V BluetoothAdapterState: isBleTurningOff()=false
09-02 19:07:10.802  4231  4243 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-02 19:07:10.802  4231  4243 D BluetoothAdapterProperties: ScanMode =  20
09-02 19:07:10.802  4231  4243 D BluetoothAdapterProperties: State =  11
09-02 19:07:10.803  4231  4247 D BluetoothAdapterProperties: Scan Mode:21
09-02 19:07:10.803  4231  4243 D BluetoothAdapterProperties: Setting state to 12
09-02 19:07:10.803  4231  4247 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:07:10.803  4231  4243 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 19:07:10.804  4231  4243 I BluetoothAdapterState: Entering OnState
09-02 19:07:10.804  1361  2117 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:10.806  1361  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:10.807  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:10.807   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 19:07:10.807  3890  3900 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:07:10.808  1361  1361 D BluetoothInputDevice: Proxy object connected
09-02 19:07:10.808  1361  1361 D HidProfile: Bluetooth service connected
09-02 19:07:10.809   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:10.809  1361  1374 D BluetoothPan: onBluetoothStateChange on: true
09-02 19:07:10.809  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:10.810  1361  2117 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:07:10.811  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:07:10.811  1361  1361 D PanProfile: Bluetooth service connected
09-02 19:07:10.813  1985  2007 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:10.813  1361  1361 D BluetoothA2dp: Proxy object connected
09-02 19:07:10.813  3890  3902 D BluetoothPan: onBluetoothStateChange on: true
,09-02 19:07:10.816   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:07:10.817   873   873 D BluetoothA2dp: Proxy object connected
09-02 19:07:10.817  3890  3900 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 19:07:10.819   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 19:07:10.819  1361  1374 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 19:07:10.819  4231  4231 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 19:07:10.820  4231  4231 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-02 19:07:10.821  4231  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:10.822  3890  3902 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 19:07:10.822  1361  1378 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:07:10.822  4231  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:10.823  4231  4231 D ObexServerSockets: Succeed to create listening sockets 
,09-02 19:07:10.823  4231  4231 D ObexServerSockets0: startAccept()
09-02 19:07:10.823  4231  4231 D ObexServerSockets0: prepareForNewConnect()
,09-02 19:07:10.824  3890  3900 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 19:07:10.826  4231  4231 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 19:07:10.826  4231  4231 D BluetoothSdpJni: SDP Create record success - handle: 0
09-02 19:07:10.826  3890  3890 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:07:10.826  3890  3890 D PanProfile: Bluetooth service connected
09-02 19:07:10.826  3890  3902 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:07:10.827  4231  4269 D ObexServerSockets0: Accepting socket connection...
,09-02 19:07:10.827  4231  4270 D ObexServerSockets0: Accepting socket connection...
09-02 19:07:10.827  1361  1361 D BluetoothMap: Proxy object connected
09-02 19:07:10.827  1361  1361 D MapProfile: Bluetooth service connected
09-02 19:07:10.827  1361  1361 D BluetoothMap: getConnectedDevices()
,09-02 19:07:10.829   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 19:07:10.830  4231  4231 D BluetoothMapService: onReceive
09-02 19:07:10.830  4231  4231 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:10.830  4231  4231 D BluetoothMapService: STATE_ON
,09-02 19:07:10.831  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:10.832  3890  3890 D BluetoothInputDevice: Proxy object connected
,09-02 19:07:10.832  3890  3890 D HidProfile: Bluetooth service connected
,09-02 19:07:10.834  3890  3890 D BluetoothMap: Proxy object connected
,09-02 19:07:10.834  3890  3890 D MapProfile: Bluetooth service connected
,09-02 19:07:10.834  3890  3890 D BluetoothMap: getConnectedDevices()
09-02 19:07:10.835  3890  3890 D BluetoothA2dp: Proxy object connected
,09-02 19:07:10.840  3890  3890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:07:10.844  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:10.844  3890  3890 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:10.850  3890  3890 D BluetoothPbap: Proxy object connected
,09-02 19:07:10.850  3890  3890 D PbapServerProfile: Bluetooth service connected
,09-02 19:07:10.854  1361  1361 D BluetoothPbap: Proxy object connected
,09-02 19:07:10.854  1361  1361 D PbapServerProfile: Bluetooth service connected
,09-02 19:07:10.856  4231  4231 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 19:07:10.856  4231  4231 D ObexServerSockets0: prepareForNewConnect()
,09-02 19:07:10.858  4231  4274 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:10.877  4231  4278 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:10.879  4231  4278 I BtOppRfcommListener: Accept thread started.
,09-02 19:07:10.906  1361  1381 D BluetoothHeadset: Proxy object connected
,09-02 19:07:10.907  1361  1361 D HeadsetProfile: Bluetooth service connected
09-02 19:07:10.907  3890  4268 D BluetoothHeadset: Proxy object connected
09-02 19:07:10.907   873   873 D BluetoothHeadset: Proxy object connected
09-02 19:07:10.907   873   890 D BluetoothHeadset: Proxy object connected
09-02 19:07:10.907   873   873 D BluetoothHeadset: Proxy object connected
09-02 19:07:10.907   873   873 D BluetoothHeadset: Proxy object connected
09-02 19:07:10.907  1985  2292 D BluetoothHeadset: Proxy object connected
,09-02 19:07:10.909   873   890 D BluetoothHeadset: Proxy object connected
,09-02 19:07:10.907  3890  3890 D HeadsetProfile: Bluetooth service connected
,09-02 19:07:10.913  1985  1998 D BluetoothHeadset: Proxy object connected
,09-02 19:07:10.919   873   890 D BluetoothHeadset: Proxy object connected
,09-02 19:07:10.922  3890  4268 D BluetoothHeadset: Proxy object connected
,09-02 19:07:10.922  3890  3890 D HeadsetProfile: Bluetooth service connected
,09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:11.183  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:11.190  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:11.193  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:11.194  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c5d68 added. We now have 8 listener(s)
,09-02 19:07:11.194  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:11.200   873  2020 D WifiService: setWifiEnabled: false pid=3822, uid=10000
,09-02 19:07:11.200   873  2020 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:07:11.213  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:11.214   873   883 D WifiService: setWifiEnabled: true pid=3822, uid=10000
09-02 19:07:11.214   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 19:07:11.227   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:11.245  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:11.252  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:11.260   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-02 19:07:11.261   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-02 19:07:11.261   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-02 19:07:11.262   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 19:07:11.263   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-02 19:07:11.263   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-02 19:07:11.263   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 19:07:11.279   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 19:07:11.280   372   871 D CommandListener: Setting iface cfg
,09-02 19:07:11.281   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-02 19:07:11.281   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 19:07:11.284   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 19:07:11.285   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 19:07:11.290   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 19:07:11.313   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:12.238  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:12.246  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:12.260  3822  3872 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-02 19:07:12.264  3822  3872 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 19:07:12.274  3822  3872 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a0390 Bundle[{}]
,09-02 19:07:12.276  3822  3872 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 19:07:12.277  3822  3872 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-02 19:07:12.278  3822  3872 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 19:07:12.279  3822  3872 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 19:07:12.280  3822  3872 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 19:07:12.281  3822  3872 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 19:07:12.286  3822  3872 I System.out: Running OutgoingSocketThread
,09-02 19:07:12.289  3822  4284 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,09-02 19:07:12.291  3822  4284 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41555
,09-02 19:07:12.292  3822  4284 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 19:07:12.834   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.10 rxSuccessRate=0.13 delta 1000 -> 1000
,09-02 19:07:12.837   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-02 19:07:12.837   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:07:12.852   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 19:07:12.906   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 19:07:12.911  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 19:07:13.290  3822  3872 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,09-02 19:07:13.290  3822  3872 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,09-02 19:07:13.303  3822  3872 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,09-02 19:07:13.307  3822  3872 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-02 19:07:13.308  3822  3872 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,09-02 19:07:13.318  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:07:13.319  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd9a581 added. We now have 2 listener(s)
,09-02 19:07:13.331  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 19:07:13.332  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:07:13.332  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:13.332  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:13.333  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2def626 added. We now have 9 listener(s)
09-02 19:07:13.333  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:13.334  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:13.337  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 19:07:13.346  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:13.354  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:13.360  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:13.361  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:13.362  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:07:13.362  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16de814 added. We now have 3 listener(s)
09-02 19:07:13.363  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:13.364  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:13.368  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 19:07:13.368  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.369  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:13.369  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:13.369  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfa18bd added. We now have 10 listener(s)
09-02 19:07:13.369  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:13.369  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:13.369  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:13.369  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:13.369  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:07:13.369  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.370  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:13.370  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:13.370  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd9a581 removed from the list
09-02 19:07:13.370  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.370  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2def626 removed from the list
,09-02 19:07:13.370  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:13.370  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.371  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.371  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:13.372  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:13.372  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.372  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.372  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2def626 not in the list
09-02 19:07:13.372  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.372  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:13.373  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.373  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:07:13.373  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.373  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfa18bd removed from the list
09-02 19:07:13.373  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.373  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.373  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.374  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:07:13.374  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16de814 removed from the list
09-02 19:07:13.374  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:13.374  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c344eb2 added. We now have 2 listener(s)
,09-02 19:07:13.376  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 19:07:13.376  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.376  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:13.376  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:13.377  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ebee03 added. We now have 9 listener(s)
,09-02 19:07:13.377  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:13.377  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:13.379  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:13.380  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 19:07:13.381  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:13.382  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:13.383   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-02 19:07:13.386  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:07:13.386  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:13.386  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:13.386  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb483b9 added. We now have 3 listener(s)
,09-02 19:07:13.388  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:13.389  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:07:13.389  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.389  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:13.389  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:13.389  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:13.389  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d14a3fe added. We now have 10 listener(s)
,09-02 19:07:13.389  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:13.390  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 19:07:13.390  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:13.390  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:13.390  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:13.390  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:07:13.392   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-02 19:07:13.393   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:07:13.393   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 19:07:13.398  3822  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 19:07:13.401  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:07:13.406  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:07:13.407  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 19:07:13.407  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:13.410   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:07:13.415  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:07:13.415  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:13.415  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:07:13.416  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:07:13.418  4231  4259 D BtGatt.GattService: registerClient() - UUID=0ccf4360-f525-4b94-8f74-6b7cc725451c
,09-02 19:07:13.419  4231  4247 D BtGatt.GattService: onClientRegistered() - UUID=0ccf4360-f525-4b94-8f74-6b7cc725451c, clientIf=5
,09-02 19:07:13.420   372   871 D CommandListener: Setting iface cfg
,09-02 19:07:13.420  3822  3834 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 19:07:13.420   873  1303 D WifiStateMachine: Start Dhcp Watchdog 3
09-02 19:07:13.421  4231  4241 D BtGatt.GattService: start scan with filters
,09-02 19:07:13.424  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:07:13.424  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:13.424  4231  4250 D BtGatt.ScanManager: handling starting scan
09-02 19:07:13.424  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:13.424  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:07:13.426  4231  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bec7924
,09-02 19:07:13.427  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:07:13.427  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:07:13.427  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:07:13.429  4231  4247 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 19:07:13.429  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.429  4231  4250 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 19:07:13.429  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:07:13.433  3822  3872 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 19:07:13.433  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:13.433  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:07:13.433  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.433  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:13.433  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:13.433  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:13.433  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 19:07:13.433  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:07:13.433  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:07:13.434  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 19:07:13.435  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 19:07:13.435  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.435  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:07:13.436  4231  4250 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:07:13.436  4231  4250 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 19:07:13.436  4231  4267 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:07:13.436   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:13.436   873  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-02 19:07:13.437  4231  4242 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 19:07:13.437  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:13.437  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:07:13.437  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:07:13.437  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 19:07:13.437  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 19:07:13.439  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:13.439  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:07:13.439  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:07:13.439  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:07:13.439  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:13.440   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-02 19:07:13.440  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:13.440  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:07:13.441  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:13.443  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:13.443  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:13.443  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:13.444  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.444  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:13.444  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:13.444  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:13.444  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c344eb2 removed from the list
09-02 19:07:13.444  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.445  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ebee03 removed from the list
,09-02 19:07:13.445  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:13.445  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:13.446  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.446  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.447  4231  4247 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-02 19:07:13.447  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.447  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:13.447  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.447  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.447  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ebee03 not in the list
09-02 19:07:13.447  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.447  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.448   873  4287 D DhcpClient: Receive thread started
,09-02 19:07:13.449  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.449  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:13.449  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.449  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d14a3fe removed from the list
09-02 19:07:13.449  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:07:13.449  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.450  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.450  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:13.450  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb483b9 removed from the list
09-02 19:07:13.451  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:07:13.451  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e13020a added. We now have 2 listener(s)
09-02 19:07:13.452  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 19:07:13.452  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:07:13.453  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:07:13.453  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.453  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:13.453  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:13.453  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6731a7b added. We now have 9 listener(s)
09-02 19:07:13.453  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:13.454  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:13.458  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:13.458  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 19:07:13.459  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:07:13.459  4231  4250 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:13.460  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:13.462  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:13.463  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:13.463  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:07:13.463  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed5f0f1 added. We now have 3 listener(s)
,09-02 19:07:13.464  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:13.464  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 19:07:13.464  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.464  4231  4250 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 19:07:13.465  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:13.467  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:07:13.467  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.467  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:13.467  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:13.467  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be734d6 added. We now have 10 listener(s)
09-02 19:07:13.467  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:13.468  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:13.469  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:13.469  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-02 19:07:13.469  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:13.469  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:13.469  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:07:13.469  4231  4247 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 19:07:13.469  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.471  3822  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 19:07:13.472  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:07:13.474  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 19:07:13.475  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 19:07:13.475  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:13.477  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 19:07:13.477  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:13.477  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:07:13.478  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:07:13.479  4231  4259 D BtGatt.GattService: registerClient() - UUID=cb2128ff-a751-487f-8083-e1d97078f773
,09-02 19:07:13.480  4231  4247 D BtGatt.GattService: onClientRegistered() - UUID=cb2128ff-a751-487f-8083-e1d97078f773, clientIf=5
09-02 19:07:13.480  3822  3868 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 19:07:13.480  4231  4241 D BtGatt.GattService: start scan with filters
,09-02 19:07:13.483  4231  4250 D BtGatt.ScanManager: handling starting scan
,09-02 19:07:13.483  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:07:13.483  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 19:07:13.483  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:13.483  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:07:13.486  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:13.487  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:13.487  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:07:13.488  4231  4247 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 19:07:13.488  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:07:13.488  4231  4250 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 19:07:13.489  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:07:13.493  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 19:07:13.493  3822  3872 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-02 19:07:13.493  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:13.493  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:13.493  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:13.493  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 19:07:13.493  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.494  4231  4250 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 19:07:13.494  4231  4250 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 19:07:13.494  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.494  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:13.494  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:13.494  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:13.494  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e13020a removed from the list
09-02 19:07:13.494  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.494  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6731a7b removed from the list
,09-02 19:07:13.494  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:07:13.494  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:13.495  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.495  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-02 19:07:13.495  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.495  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:13.496  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:07:13.496  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.496  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.496  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6731a7b not in the list
09-02 19:07:13.496  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:13.496  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:13.496  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-02 19:07:13.497  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 19:07:13.497  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 19:07:13.497  3822  3872 D BluetoothAdapter: STATE_ON
09-02 19:07:13.498  4231  4242 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:07:13.498  4231  4259 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 19:07:13.499  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-02 19:07:13.499  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:07:13.499  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:07:13.499  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:13.499  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
09-02 19:07:13.500  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:13.501  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:07:13.501  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 19:07:13.501  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:07:13.501  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.502  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.502  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:07:13.502  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.503  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:07:13.503  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be734d6 removed from the list
09-02 19:07:13.503  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:07:13.503  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.503  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:13.503  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:13.503  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.503  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:07:13.503  4231  4247 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 19:07:13.503  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed5f0f1 removed from the list
09-02 19:07:13.503  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.504  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:13.504  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9c862 added. We now have 2 listener(s)
,09-02 19:07:13.505  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:07:13.505  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.506  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:13.506  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:13.506  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7345df3 added. We now have 9 listener(s)
09-02 19:07:13.506  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:13.506  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:13.508  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 19:07:13.508  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.508  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:13.511  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:13.513  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-02 19:07:13.513  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:13.513  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:13.513  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0cd29 added. We now have 3 listener(s)
09-02 19:07:13.514  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:13.515  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 19:07:13.515  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:13.515  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:07:13.515  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.515  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.515  4231  4250 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:07:13.515  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:13.515  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:13.516  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b008ae added. We now have 10 listener(s)
,09-02 19:07:13.516  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:13.516  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:13.516  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:13.516  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:13.516  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:13.516  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:07:13.519  3822  3872 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 19:07:13.519  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:07:13.522  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 19:07:13.522  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 19:07:13.522  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.522  4231  4250 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 19:07:13.522  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 19:07:13.522  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:13.525  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 19:07:13.525  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:13.525  3822  3872 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 19:07:13.526  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:07:13.527  4231  4247 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 19:07:13.527  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:07:13.528  4231  4242 D BtGatt.GattService: registerClient() - UUID=842e3a4f-b558-4f00-ab45-be0a0150b4dd
09-02 19:07:13.528  4231  4247 D BtGatt.GattService: onClientRegistered() - UUID=842e3a4f-b558-4f00-ab45-be0a0150b4dd, clientIf=5
,09-02 19:07:13.528  3822  3868 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 19:07:13.528  4231  4259 D BtGatt.GattService: start scan with filters
,09-02 19:07:13.530  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 19:07:13.530  4231  4250 D BtGatt.ScanManager: handling starting scan
09-02 19:07:13.530  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:13.531  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:13.531  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 19:07:13.531   873  1303 E native  : do suspend false
,09-02 19:07:13.533  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:13.533  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:07:13.533  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:07:13.535  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:07:13.536  4231  4247 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 19:07:13.536  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.536  4231  4250 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 19:07:13.539  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:13.539  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:13.539  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:13.539  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.539  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.539  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:13.539  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:13.540  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f9c862 removed from the list
,09-02 19:07:13.540  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.540  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7345df3 removed from the list
,09-02 19:07:13.540  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:13.540  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:13.540  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.540  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 19:07:13.540  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.540  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:13.541  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:13.541  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 19:07:13.541  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.541  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:07:13.541  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.541  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7345df3 not in the list
09-02 19:07:13.541  4231  4250 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:07:13.541  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:13.542  4231  4250 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 19:07:13.542  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 19:07:13.542  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:07:13.542  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:07:13.542  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 19:07:13.542  3822  3872 D BluetoothAdapter: STATE_ON
,09-02 19:07:13.543  4231  4259 D BtGatt.GattService: stopScan() - queue size =1
09-02 19:07:13.543  4231  4267 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 19:07:13.544  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:13.544  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 19:07:13.544  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-02 19:07:13.544   873  1875 D DhcpClient: Broadcasting DHCPDISCOVER
09-02 19:07:13.544  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:13.544  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 19:07:13.545  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:13.545  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 19:07:13.545  3822  3872 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:07:13.545  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:07:13.546  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.546  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:13.547  3822  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:13.547  3822  3822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:13.547  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.547  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:13.547  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.547  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b008ae removed from the list
09-02 19:07:13.547  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.547  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:13.547  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.547  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:13.547  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a0cd29 removed from the list
,09-02 19:07:13.549  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:13.549  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17801ba added. We now have 2 listener(s)
09-02 19:07:13.550  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:07:13.551  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:13.551  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:13.551  4231  4247 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 19:07:13.551  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.551  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:13.551  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b986b added. We now have 9 listener(s)
09-02 19:07:13.551  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:13.551  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:13.553  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:13.555   873  4287 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,09-02 19:07:13.556   873  1875 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
09-02 19:07:13.556  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 19:07:13.556  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:13.556  3822  3872 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:13.557   873  1875 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 19:07:13.558  3822  3872 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:13.558  3822  3872 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:13.558  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:07:13.558  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f3f861 added. We now have 3 listener(s)
09-02 19:07:13.559  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:13.561  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:13.562  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 19:07:13.562  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:07:13.562  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:13.562  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:13.562  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e947f86 added. We now have 10 listener(s)
09-02 19:07:13.562  4231  4247 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 19:07:13.562  3822  3872 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:13.562  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 19:07:13.562  3822  3872 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:13.562  4231  4250 D BtGatt.ScanManager: stopping BLe Batch,
,09-02 19:07:13.562  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:07:13.562  3822  3872 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:13.562  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.562  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:13.562  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:13.562  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:07:13.563  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17801ba removed from the list
09-02 19:07:13.563  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:13.563  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b986b removed from the list
09-02 19:07:13.563  3822  3872 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:13.563  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.563  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:13.563  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.564  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:07:13.564  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:13.564  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:13.564  3822  3872 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b986b not in the list
09-02 19:07:13.564  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.564  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.565  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:07:13.565  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:13.565  3822  3872 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:13.565  3822  3872 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e947f86 removed from the list
,09-02 19:07:13.565  3822  3872 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:13.565  3822  3872 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:13.565  3822  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:13.565  3822  3872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:07:13.565  3822  3872 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f3f861 removed from the list
09-02 19:07:13.566  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 19:07:13.566  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 19:07:13.566  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 19:07:13.566  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:13.566  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 19:07:13.566  3822  3872 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:13.568  4231  4247 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 19:07:13.568  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.568  4231  4250 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 19:07:13.569   873  4287 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-02 19:07:13.570   873  1875 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 19:07:13.570  3822  4288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
09-02 19:07:13.571  3822  4288 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
09-02 19:07:13.571  3822  4288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 19:07:13.571   372   871 D CommandListener: Setting iface cfg
,09-02 19:07:13.573  4231  4247 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 19:07:13.573  3822  4289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
09-02 19:07:13.573  4231  4247 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 19:07:13.573  3822  4289 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
09-02 19:07:13.574  3822  4289 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 19:07:13.575   873  1875 D DhcpClient: Scheduling renewal in 86399s
,09-02 19:07:13.575  3822  3872 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 19:07:13.575  3822  3872 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 19:07:13.575  3822  3872 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 19:07:13.575  3822  3872 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 19:07:13.576  3822  3872 D com.test.thalitest.ThaliTestRunner: Total duration: 22937 ms
,09-02 19:07:13.576   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-02 19:07:13.577  3822  3872 I jxcore-log: *Native tests were executed*
09-02 19:07:13.577  3822  3872 I jxcore-log: 
09-02 19:07:13.577  3822  3872 I jxcore-log: Total number of executed tests:  80
09-02 19:07:13.577  3822  3872 I jxcore-log: 
09-02 19:07:13.577  3822  3872 I jxcore-log: Number of passed tests:  80
09-02 19:07:13.577  3822  3872 I jxcore-log: 
09-02 19:07:13.577  3822  3872 I jxcore-log: Number of failed tests:  0
09-02 19:07:13.577  3822  3872 I jxcore-log: 
09-02 19:07:13.577  3822  3872 I jxcore-log: Number of ignored tests:  0
09-02 19:07:13.577  3822  3872 I jxcore-log: 
,09-02 19:07:13.578  3822  3872 I jxcore-log: Total duration:  22937
09-02 19:07:13.578  3822  3872 I jxcore-log: 
09-02 19:07:13.578  3822  3872 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 19:07:13.578  3822  3872 I jxcore-log: 
09-02 19:07:13.581  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.581  3822  3872 I jxcore-log: 
,09-02 19:07:13.587  3822  3822 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 19:07:13.588   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-02 19:07:13.588  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.588  3822  3872 I jxcore-log: 
09-02 19:07:13.589  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.589  3822  3872 I jxcore-log: 
09-02 19:07:13.589   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
09-02 19:07:13.589  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.589  3822  3872 I jxcore-log: 
09-02 19:07:13.589   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 19:07:13.590  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.590  3822  3872 I jxcore-log: 
09-02 19:07:13.590   873  1305 D ConnectivityService: Adding iface wlan0 to network 102
09-02 19:07:13.594   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 19:07:13.596  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.596  3822  3872 I jxcore-log: 
,09-02 19:07:13.598  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.598  3822  3872 I jxcore-log: 
,09-02 19:07:13.599  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.599  3822  3872 I jxcore-log: 
,09-02 19:07:13.600  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.600  3822  3872 I jxcore-log: 
09-02 19:07:13.600  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:07:13.600  3822  3872 I jxcore-log: 
,09-02 19:07:13.601  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.601  3822  3872 I jxcore-log: 
,09-02 19:07:13.602  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.602  3822  3872 I jxcore-log: 
,09-02 19:07:13.602  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.602  3822  3872 I jxcore-log: 
09-02 19:07:13.603  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.603  3822  3872 I jxcore-log: 
,09-02 19:07:13.603  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.603  3822  3872 I jxcore-log: 
09-02 19:07:13.604  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.604  3822  3872 I jxcore-log: 
,09-02 19:07:13.604  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.604  3822  3872 I jxcore-log: 
,09-02 19:07:13.605  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.605  3822  3872 I jxcore-log: 
09-02 19:07:13.605  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.605  3822  3872 I jxcore-log: 
,09-02 19:07:13.606  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.606  3822  3872 I jxcore-log: 
09-02 19:07:13.606  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.606  3822  3872 I jxcore-log: 
,09-02 19:07:13.607  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:07:13.607  3822  3872 I jxcore-log: 
09-02 19:07:13.607  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.607  3822  3872 I jxcore-log: 
,09-02 19:07:13.608  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.608  3822  3872 I jxcore-log: 
,09-02 19:07:13.608  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.608  3822  3872 I jxcore-log: 
09-02 19:07:13.609  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.609  3822  3872 I jxcore-log: 
,09-02 19:07:13.609  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.609  3822  3872 I jxcore-log: 
,09-02 19:07:13.610  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.610  3822  3872 I jxcore-log: 
09-02 19:07:13.610  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:07:13.610  3822  3872 I jxcore-log: 
,09-02 19:07:13.628   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 19:07:13.628   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-02 19:07:13.629   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-02 19:07:13.630   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-02 19:07:13.630   873  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-02 19:07:13.636   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-02 19:07:13.640   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-02 19:07:13.640   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-02 19:07:13.640   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-02 19:07:13.641   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 19:07:13.641   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:13.641   873  1305 D ConnectivityService:    accepting network in place of null
,09-02 19:07:13.642   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -59]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 19:07:13.655   873  4286 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146620, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 19:07:13.681   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:07:13.722   873  4285 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.142,2a00:1450:4001:810::200e
,09-02 19:07:13.729   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 19:07:13.734   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-02 19:07:13.734   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:13.737   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-02 19:07:13.738   873   890 D Tethering: MasterInitialState.processMessage what=3
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:13.750  3822  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:13.753  3822  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:13.754  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:07:13.754  3822  3872 I jxcore-log: 
,09-02 19:07:13.782  1697  1697 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 19:07:13.784  1697  1697 D SystemUpdateService: onCreate
,09-02 19:07:13.789  1697  1697 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 19:07:13.795   873  4285 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 17:07:13 GMT], X-Android-Received-Millis=[1472836033794], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472836033769]}
,09-02 19:07:13.797   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-02 19:07:13.798   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-02 19:07:13.798   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-02 19:07:13.801   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 19:07:13.807  1697  4301 I SystemUpdateService: active receiver: enabled
,09-02 19:07:13.814  1697  1697 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 19:07:13.824  1697  2456 I iu.UploadsManager: num queued entries: 0
,09-02 19:07:13.827  1697  2456 I iu.UploadsManager: num updated entries: 0
,09-02 19:07:13.829  1697  4301 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 19:07:13.830  1697  1697 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 19:07:13.833  1697  1697 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 19:07:13.835  4005  4005 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:13.842  1697  4305 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-02 19:07:13.842  1697  4305 W BaseAppContext: Using Auth Proxy for data requests.
,09-02 19:07:13.843  4005  4005 D SprintDMHelper: simOperator: 
,09-02 19:07:13.843  4005  4005 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 19:07:13.855  1697  4305 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 19:07:13.867  1697  4301 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-02 19:07:13.867  1697  4301 I SystemUpdateService: now status is 0 (complete)
09-02 19:07:13.867  1697  4301 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 19:07:13.867  1697  4301 I SystemUpdateService: file has been verified
09-02 19:07:13.867  1697  4301 I SystemUpdateService: OTA package size = 12249756
,09-02 19:07:13.873  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:07:13.874  1697  2456 I iu.SyncManager: NEXT; no task
,09-02 19:07:13.876  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:07:13.889  1697  4301 I SystemUpdateService: showing system update notification
,09-02 19:07:13.908  1697  1697 D SystemUpdateService: onDestroy
,09-02 19:07:13.916  1504  2113 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 19:07:13.916  1504  2113 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-02 19:07:13.916  1504  2113 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 19:07:13.916  1504  2113 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:07:13.936  1697  4305 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-02 19:07:13.941  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 19:07:13.943  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:07:13.943  3822  3872 I jxcore-log: 
,09-02 19:07:13.991  3963  4307 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-02 19:07:14.003  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 19:07:14.004  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:07:14.004  3822  3872 I jxcore-log: 
,09-02 19:07:14.047  3822  3822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 19:07:14.048  3822  3872 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:07:14.048  3822  3872 I jxcore-log: 
,09-02 19:07:14.301  4295  4295 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-02 19:07:14.306  4295  4295 D AndroidRuntime: CheckJNI is OFF
,09-02 19:07:14.350  4295  4295 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-02 19:07:14.376  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 19:07:14.392  4295  4295 I Radio-JNI: register_android_hardware_Radio DONE
,09-02 19:07:14.414  4295  4295 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 19:07:14.422   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-02 19:07:14.422   873   886 I ActivityManager: Killing 3822:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-02 19:07:14.432  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-02 19:07:14.432  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-02 19:07:14.432  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 19:07:14.432  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 19:07:14.503   873  2045 I WindowState: WIN DEATH: Window{728019 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-02 19:07:14.504   873   883 D GraphicsStats: Buffer count: 2
09-02 19:07:14.505   873  1304 D WifiService: Client connection lost with reason: 4
,09-02 19:07:14.527   873   886 W ActivityManager: Force removing ActivityRecord{5cb25a6 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,09-02 19:07:14.569   873   896 W PackageSettings: Skipping PackageSetting{76adf61 com.example.hello/10273} due to missing metadata
,09-02 19:07:14.597   873  1692 W ActivityManager: Spurious death for ProcessRecord{ef0ba18 0:com.test.thalitest/u0a0}, curProc for 3822: null
,09-02 19:07:14.599   873   896 I art     : Starting a blocking GC Explicit
,09-02 19:07:14.623  3529  3529 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-02 19:07:14.625  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-02 19:07:14.626  3529  3529 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-02 19:07:14.634   873  1999 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3822 uid 10000
,09-02 19:07:14.636  1897  1897 I Keyboard.Facilitator: onFinishInput()
,09-02 19:07:14.684   873   896 I art     : Explicit concurrent mark sweep GC freed 55792(3MB) AllocSpace objects, 10(296KB) LOS objects, 33% free, 29MB/43MB, paused 1.198ms total 79.151ms
,09-02 19:07:14.689  2072  4323 I MicroRecognitionRnrImpl: Starting detection.
,09-02 19:07:14.691  2072  4324 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@a9af156
,09-02 19:07:14.694   376  4326 I AudioFlinger: AudioFlinger's thread 0xb1dc0000 ready to run
,09-02 19:07:14.697   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-02 19:07:14.698  2072  4324 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@a9af156
,09-02 19:07:14.703   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-02 19:07:14.705  4295  4295 I art     : System.exit called, status: 0
,09-02 19:07:14.705  4295  4295 I AndroidRuntime: VM exiting with result code 0.
09-02 19:07:14.708   376  4326 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
09-02 19:07:14.708   376  4326 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
09-02 19:07:14.708   376  4326 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,09-02 19:07:14.717   376  4326 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-02 19:07:14.719   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-02 19:07:14.733  1851  2152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 19:07:14.733   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-02 19:07:14.734  4231  4231 D BluetoothMapAppObserver: onReceive
09-02 19:07:14.734  4231  4231 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-02 19:07:14.740   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 19:07:14.749  3692  3692 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-02 19:07:14.750  1897  1897 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-02 19:07:14.753  1897  4332 I Keyboard.Facilitator.DecoderInitializer: run()
,09-02 19:07:14.788  1985  1985 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-02 19:07:14.792  1897  4332 I Decoder : createOrResetDecoder
,09-02 19:07:14.796   873   883 I ActivityManager: Start proc 4334:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-02 19:07:14.797  2072  2072 I HotwordWorkerImpl: onReady
,09-02 19:07:14.812  1504  1504 I ConfigService: onCreate
,09-02 19:07:14.843  1897  4332 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-02 19:07:14.848   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-02 19:07:14.853  4334  4334 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-02 19:07:14.861  2000  2127 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-02 19:07:14.864   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-02 19:07:14.865   873   885 E PackageManager: Failed to write settings, restoring backup
09-02 19:07:14.865   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-02 19:07:14.865   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-02 19:07:14.865   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-02 19:07:14.865   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-02 19:07:14.865   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-02 19:07:14.865   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:14.865   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:14.865   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 19:07:14.867   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-02 19:07:14.867   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-02 19:07:14.867   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 19:07:14.867   873   886 E DropBoxManagerService: 	... 13 more
,09-02 19:07:14.874   873  1999 I ActivityManager: Start proc 4347:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-02 19:07:14.875  2000  2127 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-02 19:07:14.875  2000  2127 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2000
09-02 19:07:14.875  2000  2127 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:14.875  2000  2127 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 19:07:14.877   873  2023 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 19:07:14.879   873  4355 E DropBoxManagerService: Can't write: system_app_crash
09-02 19:07:14.879   873  4355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 19:07:14.879   873  4355 E DropBoxManagerService: 	... 5 more
,09-02 19:07:14.880  2072  2086 W SearchService: Abort, client detached.
,09-02 19:07:14.886  2072  2072 I HotwordDetector: Closing mic
,09-02 19:07:14.886  2072  2331 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a9af156
09-02 19:07:14.887  2072  4324 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-02 19:07:14.892   873  4361 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-02 19:07:14.900  2072  4362 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
09-02 19:07:14.900  1897  4332 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-02 19:07:14.903  1897  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-02 19:07:14.903  1897  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-02 19:07:14.908  1897  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-02 19:07:14.908  1897  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-02 19:07:14.909  1897  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-02 19:07:14.910  1897  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-02 19:07:14.912  1897  4332 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-02 19:07:14.912  1897  4332 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-02 19:07:14.912  1897  4332 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-02 19:07:14.918  1897  4332 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-02 19:07:14.918  1897  4332 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-02 19:07:14.919  1897  4332 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-02 19:07:14.924   873  4361 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 19:07:14.924   873  4361 I Adreno  : Build Date                       : 10/20/15
09-02 19:07:14.924   873  4361 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 19:07:14.924   873  4361 I Adreno  : Local Branch                     : M14
09-02 19:07:14.924   873  4361 I Adreno  : Remote Branch                    : 
09-02 19:07:14.924   873  4361 I Adreno  : Remote Branch                    : 
09-02 19:07:14.924   873  4361 I Adreno  : Reconstruct Branch               : 
09-02 19:07:14.929   873  4361 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 19:07:14.939   376  4326 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-02 19:07:14.939   376  4326 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-02 19:07:14.942   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-02 19:07:14.944  2072  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-02 19:07:14.945  2072  4323 I MicroRecognitionRnrImpl: Detection finished
,09-02 19:07:14.961  4334  4334 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-02 19:07:14.999  4334  4375 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-02 19:07:15.002   873  2045 I ActivityManager: Start proc 4372:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-02 19:07:15.009  1697  4371 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-02 19:07:15.010  1697  4371 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-02 19:07:15.022  4334  4364 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:15.022  4334  4364 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:15.023  4334  4364 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 19:07:15.034  4372  4372 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-02 19:07:15.047   873  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,09-02 19:07:15.050  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-02 19:07:15.051  1504  1504 D AndroidRuntime: Shutting down VM
,09-02 19:07:15.051  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
09-02 19:07:15.051  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
09-02 19:07:15.051  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-02 19:07:15.051  1504  1504 E AndroidRuntime: 	... 8 more
,09-02 19:07:15.058   873  4387 E DropBoxManagerService: Can't write: system_app_crash
09-02 19:07:15.058   873  4387 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 19:07:15.058   873  4387 E DropBoxManagerService: 	... 5 more
,09-02 19:07:15.082  4334  4364 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-02 19:07:15.087  4334  4375 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:15.087  4334  4375 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 19:07:15.088  4334  4375 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-02 19:07:15.088  4334  4375 E AndroidRuntime: Process: android.process.acore, PID: 4334
09-02 19:07:15.088  4334  4375 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 19:07:15.088  4334  4375 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 19:07:15.091   873  4389 E DropBoxManagerService: Can't write: system_app_crash
09-02 19:07:15.091   873  4389 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 19:07:15.091   873  4389 E DropBoxManagerService: 	... 5 more
09-02 19:07:15.093  4334  4364 I Process : Sending signal. PID: 4334 SIG: 9
,09-02 19:07:15.151   873  2220 I ActivityManager: Process android.process.acore (pid 4334) has died
,09-02 19:07:15.151   873  2220 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-02 19:07:15.194   873   891 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,09-02 19:07:15.239   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,09-02 19:07:15.239   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
09-02 19:07:15.239   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
09-02 19:07:15.240   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,09-02 19:07:15.240   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
09-02 19:07:15.240   281   281 E qdoverlay: MdpCtrl close error in unset
,09-02 19:07:15.501   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-02 19:07:15.501   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,09-02 19:07:15.502   281   281 E qdoverlay: MdpCtrl close error in unset

```
