#### Test 81418577c146d2e_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 08:16:34.443   873  1850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=108637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 08:16:36.415  3824  3824 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 08:16:36.420  3824  3824 D AndroidRuntime: CheckJNI is OFF
08-16 08:16:36.456  3824  3824 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 08:16:36.500  3824  3824 I Radio-JNI: register_android_hardware_Radio DONE
08-16 08:16:36.520  3824  3824 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 08:16:36.524   873  1940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 08:16:36.558  1995  2011 W SearchService: Abort, client detached.
08-16 08:16:36.566  1995  2312 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@bc3333e
08-16 08:16:36.567  1995  1995 I HotwordDetector: Closing mic
08-16 08:16:36.567  1995  2322 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 08:16:36.581  3824  3824 D AndroidRuntime: Shutting down VM
08-16 08:16:36.628   377  2324 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 08:16:36.630   377  2324 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 08:16:36.630   873  1924 I ActivityManager: Start proc 3833:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 08:16:36.639   377  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 08:16:36.641  1995  2321 I MicroRecognitionRnrImpl: Detection finished
08-16 08:16:36.643  1995  2315 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 08:16:36.706  3833  3833 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 08:16:36.735  3833  3833 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 08:16:36.746  3833  3833 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 935-941)
08-16 08:16:36.746  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 08:16:36.772  3833  3833 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7ac7f45}
08-16 08:16:36.774  3833  3833 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 08:16:36.775  3833  3833 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 08:16:36.785  3833  3833 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 08:16:36.787  3833  3833 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 08:16:36.821  3833  3833 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 08:16:36.841  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 08:16:36.841  3833  3833 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 08:16:36.841  3833  3833 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 08:16:36.841  3833  3833 I Adreno  : Build Date                       : 10/20/15
08-16 08:16:36.841  3833  3833 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 08:16:36.841  3833  3833 I Adreno  : Local Branch                     : M14
08-16 08:16:36.841  3833  3833 I Adreno  : Remote Branch                    : 
08-16 08:16:36.841  3833  3833 I Adreno  : Remote Branch                    : 
08-16 08:16:36.841  3833  3833 I Adreno  : Reconstruct Branch               : 
,08-16 08:16:36.905   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d1077c1:true
,08-16 08:16:36.976  3833  3833 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 08:16:37.009  3833  3833 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 08:16:37.119  3833  3873 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 08:16:37.134  3833  3858 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 08:16:37.181  3833  3873 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 08:16:37.282  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-16 08:16:37.282   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +689ms
,08-16 08:16:37.432  3833  3833 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3833
,08-16 08:16:37.482   873  2961 I ActivityManager: Killing 2962:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 08:16:37.543   873  2961 I ActivityManager: Killing 3235:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 08:16:37.646  3833  3833 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 08:16:37.827  3833  3875 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681196752
,08-16 08:16:37.851  3833  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 08:16:37.851  3833  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 08:16:37.851  3833  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 08:16:37.851  3833  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 08:16:37.851  3833  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 08:16:37.851  3833  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@778deb9 added. We now have 1 listener(s)
08-16 08:16:37.859  3833  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-16 08:16:37.860  3833  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:16:37.862  3833  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:16:37.862  3833  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 08:16:37.869  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 08:16:37.870  3833  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35e7cac added. We now have 1 listener(s)
08-16 08:16:37.871  3833  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:16:37.877   873  1306 D WifiService: New client listening to asynchronous messages
08-16 08:16:37.879  3833  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:16:37.879  3833  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 08:16:37.879  3833  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 08:16:37.879  3833  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 08:16:37.879  3833  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 08:16:37.884  3833  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:16:37.884  3833  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 08:16:37.894  3833  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:37.895  3833  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:37.895  3833  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 08:16:37.895  3833  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 08:16:37.897  3833  3875 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 08:16:37.977  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:16:37.980  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:16:37.982  3833  3833 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 08:16:39.087  3833  3884 W jxcore-log: Initializing JXcore engine
,08-16 08:16:39.087  3833  3884 W jxcore-log: JXcore engine is ready
,08-16 08:16:39.123  3884  3884 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 08:16:39.123  3884  3884 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12693]" dev="sockfs" ino=12693 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-16 08:16:39.123  3884  3884 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 08:16:39.123  3884  3884 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25704]" dev="sockfs" ino=25704 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 08:16:39.139  3833  3884 W jxcore-log: Starting JXcore engine
,08-16 08:16:39.219  3833  3884 W jxcore-log: Platform android
08-16 08:16:39.219  3833  3884 W jxcore-log: 
,08-16 08:16:39.219  3833  3884 W jxcore-log: Process ARCH arm
08-16 08:16:39.219  3833  3884 W jxcore-log: 
,08-16 08:16:39.392  3833  3884 I jxcore-log: JXcore Cordova bridge is ready!
08-16 08:16:39.392  3833  3884 I jxcore-log: 
,08-16 08:16:39.393  3833  3884 W jxcore-log: JXcore engine is started
,08-16 08:16:39.401  3833  3875 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 08:16:39.406  3833  3833 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 08:16:46.868  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:16:46.874  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:16:46.875  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:16:46.906  1511  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 08:16:46.906  1511  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 08:16:46.907  1511  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 08:16:46.907  1511  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:16:46.930  3540  3540 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 08:16:46.930  3540  3540 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 08:16:46.930  3540  3540 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-16 08:16:47.350   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 08:16:49.514  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 08:16:49.514  3833  3884 I jxcore-log: 
,08-16 08:16:49.516  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 08:16:49.516  3833  3884 I jxcore-log: 
,08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:49.528  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:16:49.535  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:16:49.538  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 08:16:49.538  3833  3884 I jxcore-log: 
,08-16 08:16:49.540  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 08:16:49.540  3833  3884 I jxcore-log: 
,08-16 08:16:49.863  3833  3884 D ExecuteNativeTests: Running unit tests
,08-16 08:16:49.921  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 08:16:49.921  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 added. We now have 2 listener(s)
08-16 08:16:49.923  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 08:16:49.923  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 08:16:49.923  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:16:49.923  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 08:16:49.923  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 added. We now have 2 listener(s)
08-16 08:16:49.923  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:16:49.923  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:16:49.925  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:49.940  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:16:49.946  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:16:49.946  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 08:16:49.951  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:16:49.953  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 08:16:49.955  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:16:49.956  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 08:16:49.956  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 08:16:49.957  3833  3884 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 08:16:49.957  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 08:16:49.958  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 08:16:49.958  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:16:49.958  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:16:49.958  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:49.959  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:49.959  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:49.959  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:49.959  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.959  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:16:49.959  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:16:49.960  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 removed from the list
08-16 08:16:49.960  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:49.960  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 removed from the list
08-16 08:16:49.960  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:49.960  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:49.965  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.965  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:49.966  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:49.967  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:49.967  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:16:49.967  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:49.969  3833  3884 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 08:16:49.969  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:49.969  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 08:16:49.969  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:49.969  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 08:16:49.969  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.970  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:49.970  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
,08-16 08:16:49.970  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:49.970  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
,08-16 08:16:49.970  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:49.970  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.970  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:16:49.970  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.970  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:49.971  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 08:16:49.971  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:49.971  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:49.971  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:49.975  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 08:16:49.976  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 08:16:49.977  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 08:16:49.977  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:49.977  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:49.977  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:49.977  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:49.978  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.978  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:49.978  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:49.978  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:49.978  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:49.978  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:49.978  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.978  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:49.978  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:49.978  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:49.980  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:49.980  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:49.980  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:49.980  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:49.981  3833  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 08:16:49.983  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:49.986  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:49.988  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:49.988  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:16:49.990  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:49.990  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:16:49.990  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:16:49.991  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:16:49.991  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:49.991  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:16:49.991  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:49.994  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 08:16:49.994  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:16:50.000  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 08:16:50.003  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 08:16:50.003  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 08:16:50.006  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 08:16:50.009  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 08:16:50.009  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 08:16:50.009  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 08:16:50.010  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 08:16:50.010  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:16:50.015  2668  2678 D BtGatt.GattService: registerClient() - UUID=45a83fec-5d8f-47cf-a0d5-75397ab4c8a2
08-16 08:16:50.015  2668  2688 D BtGatt.GattService: onClientRegistered() - UUID=45a83fec-5d8f-47cf-a0d5-75397ab4c8a2, clientIf=5
08-16 08:16:50.016  3833  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 08:16:50.017  2668  2679 D BtGatt.GattService: start scan with filters
08-16 08:16:50.020  2668  2692 D BtGatt.ScanManager: handling starting scan
08-16 08:16:50.021  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 08:16:50.021  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 08:16:50.021  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 08:16:50.021  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 08:16:50.021  2668  2692 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:16:50.023  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:16:50.024  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 08:16:50.024  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:16:50.025  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 08:16:50.029  2668  2688 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 08:16:50.029  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.029  2668  2692 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 08:16:50.030  3833  3884 I io.jxcore.node.ConnectionHelper: start: OK
08-16 08:16:50.032  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.032  3833  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 08:16:50.032  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.032  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 08:16:50.032  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.032  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 08:16:50.032  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 08:16:50.032  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 08:16:50.032  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 08:16:50.032  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 08:16:50.033  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 08:16:50.033  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 08:16:50.034  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:16:50.034  2668  2679 D BtGatt.GattService: stopScan() - queue size =1
08-16 08:16:50.035  2668  2678 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 08:16:50.035  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:16:50.035  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 08:16:50.036  2668  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 08:16:50.036  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.036  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 08:16:50.036  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 08:16:50.036  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 08:16:50.036  2668  2692 D BtGatt.ScanManager: Starting BLE batch scan
08-16 08:16:50.036  2668  2692 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 08:16:50.037  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.037  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 08:16:50.037  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 08:16:50.037  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:16:50.038  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:16:50.041  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.042  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.042  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.042  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:16:50.042  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.042  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.042  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.042  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.042  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.042  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.042  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.043  3833  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 08:16:50.044  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:50.047  2668  2688 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 08:16:50.048  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:50.048  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:50.050  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.050  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:16:50.050  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:16:50.050  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:16:50.050  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:16:50.050  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:50.050  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:16:50.053  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.054  2668  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 08:16:50.054  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.054  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 08:16:50.054  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:16:50.055  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.060  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 08:16:50.061  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 08:16:50.061  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 08:16:50.062  2668  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 08:16:50.062  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.063  2668  2692 D BtGatt.ScanManager: stopping BLe Batch
,08-16 08:16:50.064  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 08:16:50.064  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 08:16:50.064  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 08:16:50.064  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:16:50.066  2668  2679 D BtGatt.GattService: registerClient() - UUID=a23dde0f-a017-4c3c-aa37-d2dd31ff2367
08-16 08:16:50.066  2668  2688 D BtGatt.GattService: onClientRegistered() - UUID=a23dde0f-a017-4c3c-aa37-d2dd31ff2367, clientIf=5
08-16 08:16:50.067  3833  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 08:16:50.067  2668  2856 D BtGatt.GattService: start scan with filters
08-16 08:16:50.069  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 08:16:50.069  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 08:16:50.069  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 08:16:50.069  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 08:16:50.069  2668  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 08:16:50.070  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.070  2668  2692 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 08:16:50.071  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:16:50.071  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:16:50.071  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 08:16:50.072  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 08:16:50.074  3833  3884 I io.jxcore.node.ConnectionHelper: start: OK
08-16 08:16:50.077  2668  2688 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 08:16:50.078  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.076  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.078  3833  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 08:16:50.078  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.078  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 08:16:50.078  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.078  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 08:16:50.078  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 08:16:50.078  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 08:16:50.078  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 08:16:50.078  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 08:16:50.078  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 08:16:50.078  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 08:16:50.079  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:16:50.079  2668  2679 D BtGatt.GattService: stopScan() - queue size =0
08-16 08:16:50.079  2668  2692 D BtGatt.ScanManager: handling starting scan
08-16 08:16:50.080  2668  2856 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 08:16:50.080  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:16:50.080  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 08:16:50.080  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 08:16:50.080  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 08:16:50.080  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 08:16:50.081  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.081  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 08:16:50.081  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 08:16:50.081  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:16:50.081  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:16:50.082  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.082  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.082  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.083  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.083  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.083  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:16:50.083  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.083  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.083  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.083  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.083  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.083  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.083  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.084  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.084  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.084  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.084  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.084  3833  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 08:16:50.086  2668  2688 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 08:16:50.086  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.086  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:50.086  2668  2692 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:50.090  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:50.091  2668  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 08:16:50.091  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.092  2668  2692 D BtGatt.ScanManager: Starting BLE batch scan
08-16 08:16:50.092  2668  2692 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 08:16:50.093  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.093  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:16:50.094  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:16:50.094  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:16:50.094  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:16:50.094  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:50.094  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:16:50.095  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.098  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.099  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 08:16:50.099  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 08:16:50.102  2668  2688 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 08:16:50.102  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.102  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 08:16:50.103  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 08:16:50.103  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 08:16:50.107  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 08:16:50.107  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 08:16:50.107  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 08:16:50.108  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:16:50.110  2668  2857 D BtGatt.GattService: registerClient() - UUID=db49c52b-e1fb-4060-9645-57db153b6cd5
08-16 08:16:50.110  2668  2688 D BtGatt.GattService: onClientRegistered() - UUID=db49c52b-e1fb-4060-9645-57db153b6cd5, clientIf=5
08-16 08:16:50.111  2668  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 08:16:50.111  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.111  3833  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 08:16:50.111  2668  2856 D BtGatt.GattService: start scan with filters
08-16 08:16:50.113  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 08:16:50.114  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 08:16:50.114  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 08:16:50.114  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 08:16:50.116  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:16:50.116  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 08:16:50.116  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:16:50.117  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 08:16:50.119  3833  3884 I io.jxcore.node.ConnectionHelper: start: OK
08-16 08:16:50.119  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.119  3833  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 08:16:50.119  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.119  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 08:16:50.119  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.119  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 08:16:50.119  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 08:16:50.119  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 08:16:50.119  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 08:16:50.119  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 08:16:50.119  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 08:16:50.119  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 08:16:50.120  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:16:50.120  2668  2856 D BtGatt.GattService: stopScan() - queue size =0
08-16 08:16:50.121  2668  2678 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 08:16:50.121  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:16:50.121  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 08:16:50.121  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 08:16:50.121  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 08:16:50.121  2668  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 08:16:50.121  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 08:16:50.121  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.121  2668  2692 D BtGatt.ScanManager: stopping BLe Batch
08-16 08:16:50.122  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.122  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 08:16:50.122  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 08:16:50.122  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:16:50.122  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:16:50.123  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.123  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.123  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.124  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.124  3833  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 08:16:50.124  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.124  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.124  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.124  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.124  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:16:50.124  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.124  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.124  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.124  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.124  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.124  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.124  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.125  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.125  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.125  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.125  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.126  3833  3884 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 08:16:50.126  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.126  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.126  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.126  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.126  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.126  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.127  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.127  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.127  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.127  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.127  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.127  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.127  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.127  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.127  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.127  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.127  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.128  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.128  2668  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 08:16:50.128  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 08:16:50.128  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.128  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.128  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.128  2668  2692 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 08:16:50.128  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.129  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.129  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.129  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.129  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.129  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.129  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.129  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.129  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.129  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.129  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.129  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.130  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.130  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.130  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.130  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.130  3833  3884 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 08:16:50.130  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.130  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.130  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.131  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.131  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.131  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.131  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.131  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.131  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.131  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.131  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.131  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.131  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.131  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.132  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.132  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.132  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.132  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.133  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 08:16:50.133  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.133  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.133  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.133  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.133  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.133  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.133  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.133  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.133  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.133  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.133  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.133  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.133  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.134  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.134  2668  2688 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 08:16:50.134  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.134  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.134  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.134  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.134  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.135  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 08:16:50.136  2668  2692 D BtGatt.ScanManager: handling starting scan
08-16 08:16:50.136  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 08:16:50.136  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 08:16:50.136  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:16:50.136  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 08:16:50.136  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 08:16:50.136  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.136  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.137  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.138  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.138  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.138  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.138  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.138  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.138  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.138  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.138  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.138  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.138  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.139  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.140  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.140  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.140  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.141  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.141  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:16:50.141  3833  3884 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 08:16:50.141  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 08:16:50.145  2668  2688 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 08:16:50.145  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.145  2668  2692 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 08:16:50.146  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:16:50.146  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 08:16:50.146  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 08:16:50.146  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 08:16:50.146  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 08:16:50.146  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 08:16:50.147  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 08:16:50.147  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 08:16:50.147  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 08:16:50.148  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 08:16:50.149  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 08:16:50.149  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 08:16:50.149  3833  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 08:16:50.150  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 08:16:50.150  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:16:50.150  3833  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 08:16:50.150  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 08:16:50.150  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:16:50.150  3833  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 08:16:50.150  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 08:16:50.152  2668  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 08:16:50.152  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.152  2668  2692 D BtGatt.ScanManager: Starting BLE batch scan
08-16 08:16:50.153  2668  2692 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 08:16:50.153  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 08:16:50.153  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 08:16:50.153  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 08:16:50.154  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 08:16:50.154  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 08:16:50.154  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 08:16:50.154  3833  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 08:16:50.154  3833  3884 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 08:16:50.154  3833  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-16 08:16:50.155  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.155  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.155  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.155  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.155  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.155  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.155  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 08:16:50.156  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.156  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.156  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.156  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.156  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.156  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.156  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.156  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.156  3833  3894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:16:50.156  3833  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-16 08:16:50.157  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.157  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.157  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.157  3833  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-16 08:16:50.157  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.157  3833  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-16 08:16:50.158  3833  3884 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 08:16:50.158  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.158  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.158  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.158  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.158  3833  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-16 08:16:50.158  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.158  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.158  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.158  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.159  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.159  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.159  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.159  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.159  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.159  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.159  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.159  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.159  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.159  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.160  3833  3884 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 08:16:50.160  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.160  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.160  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.160  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.160  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.160  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.161  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.161  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.161  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.161  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.161  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.161  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.161  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.161  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.162  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.162  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.162  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.162  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.162  3833  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 08:16:50.163  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 08:16:50.163  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 08:16:50.163  3833  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 08:16:50.163  3833  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 08:16:50.163  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 08:16:50.163  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 08:16:50.163  3833  3884 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 08:16:50.163  3833  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 08:16:50.163  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 08:16:50.163  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 08:16:50.163  2668  2688 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 08:16:50.163  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.163  3833  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 08:16:50.164  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.164  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.164  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.164  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.164  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.164  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.164  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.164  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.164  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.164  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.164  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.164  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.164  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.164  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.165  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.165  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.165  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.165  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.166  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.166  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.166  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.166  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.166  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.166  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.166  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.166  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.166  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.166  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.166  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.166  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.166  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.166  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.166  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.166  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.166  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.166  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.167  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.167  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.167  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.167  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.167  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.167  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.167  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.167  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.167  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.167  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.167  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.168  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.168  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.168  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.168  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.169  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 08:16:50.169  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:50.170  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 08:16:50.170  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 08:16:50.170  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 08:16:50.170  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 08:16:50.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 08:16:50.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 08:16:50.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 08:16:50.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 08:16:50.171  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 08:16:50.171  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.171  3833  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 08:16:50.171  3833  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 08:16:50.171  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.171  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 08:16:50.171  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 08:16:50.172  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 08:16:50.172  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.172  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.172  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.173  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.173  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:16:50.173  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:16:50.173  2668  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 08:16:50.173  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.173  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.173  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.173  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.173  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.174  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.174  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.174  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.174  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.174  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.174  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.174  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.174  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.174  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.174  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.174  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.175  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.175  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.175  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.175  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.176  3833  3884 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 08:16:50.176  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 08:16:50.176  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 08:16:50.177  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 08:16:50.177  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.177  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.177  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.178  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.178  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.178  3833  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 08:16:50.178  3833  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 08:16:50.179  3833  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 08:16:50.178  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.179  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.179  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.179  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.179  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.179  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.179  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.179  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.179  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.181  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.181  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.181  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.181  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.181  2668  2688 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 08:16:50.181  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.181  2668  2692 D BtGatt.ScanManager: stopping BLe Batch
08-16 08:16:50.183  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.183  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.183  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.184  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.184  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.184  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.184  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.184  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.184  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.184  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.184  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.184  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.184  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.184  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.185  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.185  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.185  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.185  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.185  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:16:50.185  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:16:50.185  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:16:50.186  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:16:50.186  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.186  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.186  3833  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0d6777 not in the list
08-16 08:16:50.186  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.186  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.186  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:16:50.186  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.186  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.186  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:16:50.186  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:16:50.187  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:16:50.187  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:16:50.187  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:16:50.187  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4457fe4 not in the list
08-16 08:16:50.187  2668  2688 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 08:16:50.187  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.187  2668  2692 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 08:16:50.188  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 08:16:50.188  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 08:16:50.188  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 08:16:50.188  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 08:16:50.188  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 08:16:50.188  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 08:16:50.189  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 08:16:50.189  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 08:16:50.190  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 08:16:50.190  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 08:16:50.190  3833  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 08:16:50.190  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 08:16:50.190  3833  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 08:16:50.190  3833  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 08:16:50.191  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 08:16:50.191  3833  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 08:16:50.191  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 08:16:50.191  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 08:16:50.191  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 08:16:50.191  3833  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 08:16:50.192  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:16:50.192  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a196826 added. We now have 2 listener(s)
08-16 08:16:50.192  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:16:50.193  2668  2688 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 08:16:50.193  2668  2688 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:16:50.193  3833  3884 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 08:16:50.193   873  1924 D WifiService: setWifiEnabled: true pid=3833, uid=10000
08-16 08:16:50.194   873  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 08:16:50.194  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:16:50.194  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df11c67 added. We now have 3 listener(s)
08-16 08:16:50.194  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:16:50.199  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:16:50.199  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4faaa14 added. We now have 4 listener(s)
08-16 08:16:50.199  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:16:50.202  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:16:50.202  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e04b2bd added. We now have 5 listener(s)
08-16 08:16:50.202  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:16:50.205   873  1929 D WifiService: setWifiEnabled: false pid=3833, uid=10000
08-16 08:16:50.205   873  1929 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 08:16:50.209  2668  2684 D BluetoothAdapterState: Current state: ON, message: 23
08-16 08:16:50.209  2668  2684 D BluetoothAdapterProperties: Setting state to 13
08-16 08:16:50.209  2668  2684 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 08:16:50.209  2668  2684 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 08:16:50.210  2668  2684 I BluetoothAdapterState: Entering PendingCommandState
08-16 08:16:50.211  2668  2688 D BluetoothAdapterProperties: Scan Mode:20
08-16 08:16:50.211  2668  2684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 08:16:50.212  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:16:50.213  2668  2668 D HeadsetService: Received stop request...Stopping profile...
,08-16 08:16:50.215   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 08:16:50.215   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 08:16:50.216  1911  1926 D BluetoothHeadset: Proxy object disconnected
08-16 08:16:50.216   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 08:16:50.216  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:50.216  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:50.216  1361  1372 D BluetoothHeadset: Proxy object disconnected
08-16 08:16:50.217  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-16 08:16:50.217  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.217  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.217  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:16:50.218  2668  2668 D A2dpService: Received stop request...Stopping profile...
08-16 08:16:50.218  2668  2836 D A2dpStateMachine: Exit Disconnected: -1
08-16 08:16:50.219  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.219   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 08:16:50.220  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-16 08:16:50.220  2668  2668 D HidService: Received stop request...Stopping profile...
08-16 08:16:50.220  2668  2668 D HidService: Stopping Bluetooth HidService
08-16 08:16:50.221  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 08:16:50.221  2668  2668 V BluetoothAdapterState: isTurningOff()=true
08-16 08:16:50.221  2668  2668 V BluetoothAdapterState: isTurningOn()=false
08-16 08:16:50.221  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 08:16:50.221  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:16:50.221  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:16:50.222  2668  2668 D HealthService: Received stop request...Stopping profile...
08-16 08:16:50.223  2668  2668 D PanService: Received stop request...Stopping profile...
08-16 08:16:50.224  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.224  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 08:16:50.224  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 08:16:50.226  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE mu,ltiple advertisement supported: SUPPORTED
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:50.226  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:50.226  2668  2668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 08:16:50.226  2668  2668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 08:16:50.227  2668  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:16:50.227  2668  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:16:50.227  2668  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:16:50.227  2668  2668 D BluetoothMapService: Received stop request...Stopping profile...
08-16 08:16:50.227  2668  2688 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 08:16:50.227  2668  2668 D BluetoothMapService: stop()
08-16 08:16:50.227  2668  2688 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 08:16:50.228  2668  2668 D BluetoothMapAppObserver: deinitObservers()
08-16 08:16:50.228  2668  2668 D BluetoothMapAppObserver: removeReceiver()
08-16 08:16:50.228  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.228  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:50.229  1361  1361 D BluetoothMap: Proxy object disconnected
08-16 08:16:50.229  1361  1361 D MapProfile: Bluetooth service disconnected
08-16 08:16:50.229  2668  2668 V BluetoothAdapterState: isTurningOff()=true
08-16 08:16:50.229  2668  2668 V BluetoothAdapterState: isTurningOn()=false
08-16 08:16:50.230  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:16:50.230  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:16:50.231  2668  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 08:16:50.231  2668  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:16:50.231  2668  2798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:16:50.231  2668  2798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:16:50.231  2668  2798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 08:16:50.231  2668  2798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:16:50.232  2668  2688 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 08:16:50.233  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isTurningOff()=true
08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isTurningOn()=false
08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isTurningOff()=true
,08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isTurningOn()=false
08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:16:50.234  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:16:50.236  2668  2668 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 08:16:50.236  2668  2668 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 08:16:50.236  2668  2688 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 08:16:50.237  2668  2668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 08:16:50.237  2668  2688 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-16 08:16:50.238  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 08:16:50.238  2668  2668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 08:16:50.239  2668  2668 V BluetoothAdapterState: isTurningOff()=true
08-16 08:16:50.239  2668  2668 V BluetoothAdapterState: isTurningOn()=false
,08-16 08:16:50.239  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:16:50.239  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:16:50.240  2668  2668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-16 08:16:50.240  2668  2668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 08:16:50.241  2668  2668 D BluetoothMapService: MAP Service closeService in
08-16 08:16:50.241  2668  2668 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 08:16:50.241   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 08:16:50.241  2668  2668 D ObexServerSockets0: shutdown(block = true)
,08-16 08:16:50.241   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 08:16:50.241   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 08:16:50.241   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 08:16:50.242  2668  2668 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 08:16:50.242  2668  2821 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 08:16:50.242  2668  2859 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 08:16:50.242  2668  2858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 08:16:50.243  2668  2668 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 08:16:50.243  2668  2668 V BluetoothAdapterState: isTurningOff()=true
08-16 08:16:50.243  2668  2668 V BluetoothAdapterState: isTurningOn()=false
08-16 08:16:50.243  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:16:50.243  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:16:50.244  2668  2668 D BluetoothMapService: cleanup()
,08-16 08:16:50.244  2668  2668 D BluetoothMapService: MAP Service closeService in
,08-16 08:16:50.244  2668  2684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 08:16:50.244  2668  2684 D BluetoothAdapterProperties: Setting state to 15
08-16 08:16:50.244  2668  2684 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 08:16:50.245  2668  2684 I BluetoothAdapterState: Entering BleOnState
,08-16 08:16:50.252   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 08:16:50.252   873  1852 D DhcpClient: Clearing IP address
,08-16 08:16:50.255   373   871 D CommandListener: Setting iface cfg
,08-16 08:16:50.258  1511  2143 V NativeCrypto: Read error: ssl=0xaedf6c00: I/O error during system call, Connection timed out
,08-16 08:16:50.260  1511  2143 V NativeCrypto: SSL shutdown failed: ssl=0xaedf6c00: I/O error during system call, Broken pipe
,08-16 08:16:50.262  2668  2668 I BtOppRfcommListener: stopping Accept Thread
,08-16 08:16:50.262  2668  3470 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:16:50.263  2668  3470 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 08:16:50.263   873   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-16 08:16:50.263   873  1847 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-16 08:16:50.266   873  1847 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-16 08:16:50.267   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-16 08:16:50.267   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 08:16:50.268  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:50.268  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:16:50.269   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 08:16:50.269  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.269  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:16:50.273   873  1866 D DhcpClient: Receive thread stopped
,08-16 08:16:50.274  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:50.274  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:50.275  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.275  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:16:50.275   873   886 I ActivityManager: Start proc 3900:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 08:16:50.276  1361  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 08:16:50.276  1361  2021 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:16:50.277  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 08:16:50.278   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-16 08:16:50.279   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 08:16:50.281   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 08:16:50.281   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 08:16:50.282  1361  1372 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 08:16:50.283   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 08:16:50.284   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 08:16:50.284  1361  1378 D BluetoothPan: onBluetoothStateChange on: false
08-16 08:16:50.284   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:16:50.284   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:16:50.285  1911  1926 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 08:16:50.285  1361  2021 D BluetoothMap: onBluetoothStateChange: up=false
08-16 08:16:50.286   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 08:16:50.287  2668  2684 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 08:16:50.287  2668  2684 D BluetoothAdapterProperties: Setting state to 16
08-16 08:16:50.287  2668  2684 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 08:16:50.287  2668  2684 D BluetoothAdapterProperties: onBleDisable
08-16 08:16:50.288  2668  2684 I BluetoothAdapterState: Entering PendingCommandState
,08-16 08:16:50.288  2668  2685 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 08:16:50.289  2668  2798 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 08:16:50.289  2668  2798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 08:16:50.289   417   417 E Parcel  : Reading a NULL string not supported here.
,08-16 08:16:50.290  2668  2688 D BluetoothAdapterProperties: Scan Mode:20
,08-16 08:16:50.290   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-16 08:16:50.290   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 08:16:50.293  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:50.293  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:50.294  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.294  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:16:50.295  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:50.295  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:50.296  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.296  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:16:50.297  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.298  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.298  2080  2286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:16:50.298   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 08:16:50.299  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:16:50.300  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:16:50.327   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:16:50.334  3900  3900 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 08:16:50.343  3900  3900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 08:16:50.349  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:16:50.350   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:16:50.352   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-16 08:16:50.352   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:16:50.354   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dad827b:true
,08-16 08:16:50.362   873  1386 I ActivityManager: Start proc 3916:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 08:16:50.364   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 08:16:50.367  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:50.367  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:16:50.368  3413  3413 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@778deb9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 08:16:50.369  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:50.369  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:16:50.369  1995  1995 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-16 08:16:50.384  3900  3900 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 08:16:50.387  3900  3900 D BluetoothMap: Create BluetoothMap proxy object
,08-16 08:16:50.397  3900  3900 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 08:16:50.403  3916  3916 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 08:16:50.411  3900  3900 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:16:50.416   873  1909 I ActivityManager: Killing 3067:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 08:16:50.419   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 08:16:50.420   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 08:16:50.491  2668  2688 I bt_hci  : shut_down
,08-16 08:16:50.492  2668  2693 D bt_hwcfg: hw_epilog_process
,08-16 08:16:50.493  2668  2693 I bt_vendor: low_power_mode_cb
,08-16 08:16:50.516  2668  2693 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 08:16:50.516  2668  2693 I bt_vendor: epilog_cb
,08-16 08:16:50.516  2668  2693 I bt_hci  : epilog_finished_callback
,08-16 08:16:50.523  2668  2688 I bt_hci_h4: hal_close
,08-16 08:16:50.524  2668  2688 I bt_userial_vendor: device fd = 51 close
,08-16 08:16:50.645  2668  2685 D bt_stack_manager: event_shut_down_stack finished.
,08-16 08:16:50.645  2668  2684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-16 08:16:50.650  2668  2684 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 08:16:50.650  2668  2668 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 08:16:50.652  2668  2668 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 08:16:50.652  2668  2668 D BtGatt.GattService: stop()
,08-16 08:16:50.652  2668  2668 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 08:16:50.656  2668  2668 V BluetoothAdapterState: isTurningOff()=false
,08-16 08:16:50.656  2668  2668 V BluetoothAdapterState: isTurningOn()=false
,08-16 08:16:50.656  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:16:50.657  2668  2668 V BluetoothAdapterState: isBleTurningOff()=true
08-16 08:16:50.657  2668  2684 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 08:16:50.658  2668  2684 D BluetoothAdapterProperties: Setting state to 10
,08-16 08:16:50.658  2668  2684 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 08:16:50.660  2668  2684 I BluetoothAdapterState: Entering OffState
,08-16 08:16:50.661   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 08:16:50.674  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 08:16:50.678  2668  2668 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 08:16:50.678  2668  2668 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 08:16:50.678  2668  2685 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 08:16:50.678  2668  2668 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 08:16:50.682  2668  2685 D bt_stack_manager: event_clean_up_stack finished.
,08-16 08:16:50.684  2668  2668 I art     : System.exit called, status: 0
,08-16 08:16:50.684  2668  2668 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 08:16:50.707  3916  3916 D StrictMode: StrictMode policy violation; ~duration=208 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.707  3916  3916 D StrictMode: StrictMode policy violation; ~duration=208 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.707  3916  3916 D StrictMode: StrictMode policy violation; ~duration=207 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.707  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.708  3916  3916 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.708  3916  3916 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.708  3916  3916 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.708  3916  3916 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.708  3916  3916 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:16:50.708  3916  3916 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 08:16:50.776   873  2959 I ActivityManager: Start proc 3952:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 08:16:50.781   873  2959 I ActivityManager: Killing 3596:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 08:16:50.820   873  1945 I ActivityManager: Process com.android.bluetooth (pid 2668) has died
,08-16 08:16:50.870  3952  3952 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 08:16:51.038  3952  3971 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 08:16:51.039  3952  3971 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 08:16:51.040  3952  3971 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 08:16:51.040  3952  3971 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 08:16:51.086  3952  3971 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 08:16:51.086  3952  3971 I Babel_SMS: MmsConfig.loadFromResources
,08-16 08:16:51.087  3952  3971 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 08:16:51.089  3952  3971 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 08:16:51.100  3952  3952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 08:16:51.104  3952  3952 I Babel_Crash: startup - clean
,08-16 08:16:51.130  3952  3952 I Babel_telephony: TeleModule.launchCompleted
,08-16 08:16:51.141   873  1929 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 08:16:51.153  3952  3952 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 08:16:51.160  3952  3952 W Babel   : BAM#gBA: invalid account id: -1
,08-16 08:16:51.161  3952  3952 W Babel   : BAM#gBA: invalid account id: -1
,08-16 08:16:51.161  3952  3952 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 08:16:51.166   873   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 08:16:51.172  3952  3976 I Babel   : deleted: false for 0
,08-16 08:16:51.182  3900  3900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 08:16:51.210   873  2960 I ActivityManager: Start proc 3979:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
08-16 08:16:51.216  3900  3900 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:16:51.251  3952  3952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 08:16:51.329  3952  3952 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 08:16:51.338  3952  3952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 08:16:51.340  3916  3939 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 08:16:51.351  3952  3952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 08:16:51.357  3952  3952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 08:16:51.375  3952  3952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 08:16:51.385  3979  3979 D AdapterServiceConfig: Adding HeadsetService
08-16 08:16:51.385  3979  3979 D AdapterServiceConfig: Adding A2dpService
08-16 08:16:51.386  3979  3979 D AdapterServiceConfig: Adding HidService
08-16 08:16:51.386  3979  3979 D AdapterServiceConfig: Adding HealthService
,08-16 08:16:51.386  3979  3979 D AdapterServiceConfig: Adding PanService
,08-16 08:16:51.390  3979  3979 D AdapterServiceConfig: Adding GattService
,08-16 08:16:51.390  3979  3979 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 08:16:51.395   873  1909 I ActivityManager: Killing 3413:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 08:16:51.398  3952  3952 I vclib   : onServiceConnected
,08-16 08:16:51.499   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bcd27c2:true
,08-16 08:16:51.566  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:16:51.602   873  2960 I ActivityManager: Start proc 3992:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-16 08:16:51.638  3992  3992 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 08:16:51.674  3992  3992 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 08:16:51.693   873  1924 I ActivityManager: Killing 3637:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-16 08:16:51.770  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 08:16:51.775  1716  1716 D SystemUpdateService: onCreate
,08-16 08:16:51.785  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 08:16:51.793  1716  4016 I SystemUpdateService: active receiver: enabled
,08-16 08:16:51.804  1716  4016 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 08:16:51.805  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 08:16:51.807  1716  4016 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 08:16:51.807  1716  4016 I SystemUpdateService: now status is 0 (complete)
08-16 08:16:51.807  1716  4016 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip,
08-16 08:16:51.807  1716  4016 I SystemUpdateService: file has been verified
,08-16 08:16:51.808  1716  4016 I SystemUpdateService: OTA package size = 12249756
,08-16 08:16:51.811  1716  2406 I iu.UploadsManager: num queued entries: 0
,08-16 08:16:51.813  1716  2406 I iu.UploadsManager: num updated entries: 0
,08-16 08:16:51.817  1716  2406 I iu.SyncManager: NEXT; no task
,08-16 08:16:51.818  1716  4016 I SystemUpdateService: showing system update notification
,08-16 08:16:51.824  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 08:16:51.826  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 08:16:51.846   873  2961 I ActivityManager: Start proc 4018:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 08:16:51.848  1716  1716 D SystemUpdateService: onDestroy
,08-16 08:16:51.882  4018  4018 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 08:16:51.885  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:16:51.893  4018  4018 D SprintDMHelper: simOperator: 
08-16 08:16:51.893  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 08:16:51.921   873   883 I ActivityManager: Start proc 4030:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 08:16:51.922   873   883 I ActivityManager: Killing 3486:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 08:16:52.066   873  2960 I ActivityManager: Start proc 4045:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 08:16:52.070  3952  4044 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 08:16:52.076   873  1929 I ActivityManager: Killing 3523:android.process.acore/u0a5 (adj 15): empty #17
,08-16 08:16:52.144  4045  4045 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 08:16:52.207  4045  4045 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 08:16:52.207  4045  4045 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 08:16:52.207  4045  4045 I GAv4    :   adb logcat -s GAv4
,08-16 08:16:52.224  4045  4045 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 08:16:52.231  4045  4045 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 08:16:52.253  4045  4063 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 08:16:52.365  4045  4045 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 08:16:52.411  4045  4045 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 08:16:52.423  4045  4045 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6611-6617)
08-16 08:16:52.423  4045  4045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 08:16:52.433  4045  4045 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eb1e829}
08-16 08:16:52.433  4045  4045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 08:16:52.434  4045  4045 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 08:16:52.443  4045  4045 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 08:16:52.444  4045  4045 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 08:16:52.464  4045  4045 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 08:16:52.477  4045  4045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 08:16:52.477  4045  4045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 08:16:52.477  4045  4045 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 08:16:52.477  4045  4045 I Adreno  : Build Date                       : 10/20/15
08-16 08:16:52.477  4045  4045 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 08:16:52.477  4045  4045 I Adreno  : Local Branch                     : M14
08-16 08:16:52.477  4045  4045 I Adreno  : Remote Branch                    : 
08-16 08:16:52.477  4045  4045 I Adreno  : Remote Branch                    : 
08-16 08:16:52.477  4045  4045 I Adreno  : Reconstruct Branch               : 
,08-16 08:16:52.535  4045  4045 I NSApplication: Starting up...
,08-16 08:16:52.549  4045  4091 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 08:16:52.580   873  1945 I ActivityManager: Start proc 4096:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 08:16:52.581   873  1945 I ActivityManager: Killing 3714:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 08:16:52.669  4096  4096 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 08:16:52.846   873  2959 I ActivityManager: Killing 3729:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 08:16:53.220   873  1924 D WifiService: setWifiEnabled: true pid=3833, uid=10000
,08-16 08:16:53.221   873  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 08:16:53.239   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-16 08:16:53.245  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:53.245  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:16:53.245  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:53.246  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 08:16:53.249  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:53.249  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:16:53.249  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:53.249  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:16:53.271   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-16 08:16:53.272   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 08:16:53.273   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 08:16:53.274   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 08:16:53.274   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 08:16:53.274   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 08:16:53.274   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 08:16:53.287   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 08:16:53.289   373   871 D CommandListener: Setting iface cfg
,08-16 08:16:53.289   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=12.38 rxSuccessRate=14.88 delta 1000 -> 994
,08-16 08:16:53.289   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 08:16:53.290   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 08:16:53.292   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 08:16:53.293   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 08:16:53.300   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 08:16:53.300   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 08:16:53.314   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 08:16:53.359   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 08:16:53.360  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 08:16:53.775  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 08:16:53.819  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 08:16:53.820  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 08:16:53.829   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 08:16:53.844   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 08:16:53.845   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:16:53.845   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 08:16:53.867   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 08:16:53.884   373   871 D CommandListener: Setting iface cfg
,08-16 08:16:53.885   873  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 08:16:53.901   873  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-16 08:16:53.904   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 08:16:53.927   873  4122 D DhcpClient: Receive thread started
,08-16 08:16:54.011   873  1305 E native  : do suspend false
,08-16 08:16:54.033   873  1852 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 08:16:54.053   873  4122 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172693, domain null
,08-16 08:16:54.054   873  1852 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172693 seconds
,08-16 08:16:54.058   873  1852 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 08:16:54.070   873  4122 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 08:16:54.072   873  1852 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 08:16:54.076   373   871 D CommandListener: Setting iface cfg
,08-16 08:16:54.090   873  1852 D DhcpClient: Scheduling renewal in 86399s
,08-16 08:16:54.091   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 08:16:54.105   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 08:16:54.106   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
08-16 08:16:54.107   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 08:16:54.108   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 08:16:54.109   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 08:16:54.110   873  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 08:16:54.159   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 08:16:54.159   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 08:16:54.160   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 08:16:54.161   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 08:16:54.163   873  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 08:16:54.181   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 08:16:54.189   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 08:16:54.189   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-16 08:16:54.189   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 08:16:54.190   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 08:16:54.190   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-16 08:16:54.190   873  1307 D ConnectivityService:    accepting network in place of null
,08-16 08:16:54.191   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 08:16:54.200   873  4120 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128395, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 08:16:54.234   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:16:54.268   873  4119 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.206,2a00:1450:4001:813::200e
,08-16 08:16:54.268   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:16:54.276   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 08:16:54.276   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:16:54.284   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 08:16:54.287   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 08:16:54.296  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:54.296  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:16:54.297  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:54.297  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:16:54.304  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:16:54.304  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:16:54.305  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:54.305  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:16:54.307  1995  1995 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 08:16:54.312  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 08:16:54.315  1716  1716 D SystemUpdateService: onCreate
,08-16 08:16:54.318  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 08:16:54.324  1716  4132 I SystemUpdateService: active receiver: enabled
,08-16 08:16:54.331  1716  4132 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 08:16:54.334  1716  4132 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 08:16:54.334  1716  4132 I SystemUpdateService: now status is 0 (complete)
,08-16 08:16:54.334  1716  4132 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 08:16:54.336  1716  4132 I SystemUpdateService: file has been verified
08-16 08:16:54.336  1716  4132 I SystemUpdateService: OTA package size = 12249756
08-16 08:16:54.336  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 08:16:54.340  1716  2406 I iu.UploadsManager: num queued entries: 0
,08-16 08:16:54.344  1716  2406 I iu.UploadsManager: num updated entries: 0
,08-16 08:16:54.345  1716  2406 I iu.SyncManager: NEXT; no task
,08-16 08:16:54.346  1716  4132 I SystemUpdateService: showing system update notification
,08-16 08:16:54.348   873  4119 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 06:16:54 GMT], X-Android-Received-Millis=[1471328214348], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471328214306]}
,08-16 08:16:54.349  1716  4136 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 08:16:54.349  1716  4136 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 08:16:54.349  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 08:16:54.350   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 08:16:54.350   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-16 08:16:54.350   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 08:16:54.351  1716  4136 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
08-16 08:16:54.351   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 08:16:54.352  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 08:16:54.355  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:16:54.360  4018  4018 D SprintDMHelper: simOperator: 
,08-16 08:16:54.361  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 08:16:54.363  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:16:54.365  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:16:54.366  1716  1716 D SystemUpdateService: onDestroy
,08-16 08:16:54.383   873   885 I ActivityManager: Start proc 4139:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-16 08:16:54.419  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 08:16:54.420  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 08:16:54.420  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 08:16:54.420  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 08:16:54.422  4139  4139 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-16 08:16:54.441  1716  4136 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-16 08:16:54.497  4139  4139 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 08:16:54.510  4139  4139 I BooksApp: Created application version: 3.6.9 (30609)
,08-16 08:16:54.527  3952  4147 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 08:16:54.539  1511  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 08:16:54.539  1511  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 08:16:54.539  1511  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 08:16:54.539  1511  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:16:54.563  3578  4154 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 08:16:54.563  3578  4154 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jdm.a(PG:82)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jcs.o(PG:406)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jcn.a(PG:1379)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jcs.i(PG:143)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at blb.a(PG:3937)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at czp.a(PG:18188)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at czp.a(PG:9081)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at czq.run(PG:1686)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 08:16:54.563  3578  4154 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jdj.a(PG:4091)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jdj.a(PG:1125)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jdm.a(PG:77)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	... 12 more
08-16 08:16:54.563  3578  4154 E HttpOperation: Caused by: faj: BadAuthentication
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at fal.a(PG:38)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	at jdj.a(PG:4089)
08-16 08:16:54.563  3578  4154 E HttpOperation: 	... 14 more
,08-16 08:16:54.622  4139  4166 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 08:16:54.623  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 08:16:54.623  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 08:16:54.623  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth,
,08-16 08:16:54.623  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:16:54.639  3578  4154 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 08:16:54.639  3578  4154 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jdm.a(PG:82)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jcs.o(PG:406)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jcn.a(PG:1379)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jcs.i(PG:143)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at hec.a(PG:42)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at hee.a(PG:102)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at czr.a(PG:65)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at kka.a(PG:108)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at czp.a(PG:19176)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at czp.a(PG:9081)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at czq.run(PG:1686)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 08:16:54.639  3578  4154 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jdj.a(PG:4091)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jdj.a(PG:1125)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jdm.a(PG:77)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	... 15 more
08-16 08:16:54.639  3578  4154 E HttpOperation: Caused by: faj: BadAuthentication
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at fal.a(PG:38)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	at jdj.a(PG:4089)
08-16 08:16:54.639  3578  4154 E HttpOperation: 	... 17 more
,08-16 08:16:54.639  3578  4154 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 08:16:54.639  3578  4154 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at hec.a(PG:42)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at hee.a(PG:102)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at czr.a(PG:65)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at kka.a(PG:108)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	... 15 more
08-16 08:16:54.639  3578  4154 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at fal.a(PG:38)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 08:16:54.639  3578  4154 E ExperimentLoader: 	... 17 more
,08-16 08:16:54.660  1716  1716 I GCM     : Message from null null,
08-16 08:16:54.661  1716  1716 E GCM     : Dropping message from null
,08-16 08:16:54.777   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126709, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 08:16:54.797  4139  4173 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 08:16:54.863  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 08:16:54.863  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 08:16:54.863  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 08:16:54.863  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:16:54.929  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 08:16:54.929  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 08:16:54.930  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 08:16:54.931  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:16:54.964  4139  4173 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 08:16:54.967  4139  4166 E BooksSync: Soft error
08-16 08:16:54.967  4139  4166 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 08:16:54.967  4139  4166 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 08:16:54.967  4139  4166 E BooksSync: Sync error
08-16 08:16:54.967  4139  4166 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 08:16:54.967  4139  4166 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 08:16:54.967  4139  4166 I BooksSync: Finished books sync
,08-16 08:16:54.978   873  1389 I ActivityManager: Killing 2182:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 08:16:54.982   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128479, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 08:16:55.276   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 08:16:56.228   873  1389 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,08-16 08:16:56.229   873  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 08:16:56.261  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 08:16:56.266   873  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 08:16:56.267   873  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 08:16:56.268   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 08:16:56.269   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 08:16:56.285   873  1852 D DhcpClient: Clearing IP address
,08-16 08:16:56.285   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 08:16:56.289   373   871 D CommandListener: Setting iface cfg
,08-16 08:16:56.301  1511  4160 V NativeCrypto: Read error: ssl=0x9a9e9800: I/O error during system call, Connection timed out
,08-16 08:16:56.304   873  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-16 08:16:56.304  1511  4160 V NativeCrypto: SSL shutdown failed: ssl=0x9a9e9800: I/O error during system call, Broken pipe
,08-16 08:16:56.305   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 08:16:56.305   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 08:16:56.319   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 08:16:56.322   417   417 E Parcel  : Reading a NULL string not supported here.
08-16 08:16:56.323   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 08:16:56.326   873  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 08:16:56.328   873  4122 D DhcpClient: Receive thread stopped
,08-16 08:16:56.341   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 08:16:56.341  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:56.341  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:16:56.341  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:16:56.341  2080  2286 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 08:16:56.341  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:16:56.342  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:16:56.342  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:16:56.342  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:16:56.342  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:16:56.344   873  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 08:16:56.369   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:16:56.393   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:16:56.393   873  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 08:16:56.393   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-16 08:16:56.395   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 08:16:56.404  1995  1995 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-16 08:16:56.412  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:16:56.414  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:16:56.419  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 08:16:56.421  1716  1716 D SystemUpdateService: onCreate
,08-16 08:16:56.423  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 08:16:56.424  1716  4182 I SystemUpdateService: active receiver: enabled
,08-16 08:16:56.428  1716  4182 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 08:16:56.429  1716  4182 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 08:16:56.430  1716  4182 I SystemUpdateService: now status is 0 (complete)
,08-16 08:16:56.430  1716  4182 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 08:16:56.430  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-16 08:16:56.430  1716  4182 I SystemUpdateService: file has been verified
08-16 08:16:56.430  1716  4182 I SystemUpdateService: OTA package size = 12249756
,08-16 08:16:56.434  1716  4182 I SystemUpdateService: showing system update notification
,08-16 08:16:56.435  1716  2406 I iu.UploadsManager: num queued entries: 0
,08-16 08:16:56.436  1716  2406 I iu.UploadsManager: num updated entries: 0
,08-16 08:16:56.437  1716  2406 I iu.SyncManager: NEXT; no task
,08-16 08:16:56.438  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 08:16:56.439  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 08:16:56.441  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:16:56.444  4018  4018 D SprintDMHelper: simOperator: 
,08-16 08:16:56.444  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 08:16:56.451  1716  1716 D SystemUpdateService: onDestroy
,08-16 08:16:56.465   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 08:16:56.468  3952  4186 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 08:16:56.639   873  1909 I ActivityManager: Killing 3752:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 08:16:59.266   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@97907b5:true
,08-16 08:16:59.266  3979  3979 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 08:16:59.271  3979  3979 I bt_bluedroid: init
,08-16 08:16:59.272  3979  4190 I BluetoothAdapterState: Entering OffState,
,08-16 08:16:59.277  3979  4191 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 08:16:59.277  3979  4191 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 08:16:59.277  3979  4191 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 08:16:59.278  3979  4191 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 08:16:59.280  3979  3979 I bt_bluedroid: get_profile_interface socket
,08-16 08:16:59.282  3979  3979 I bt_bluedroid: get_profile_interface sdp
,08-16 08:16:59.286  3979  3989 I bt_bluedroid: config_hci_snoop_log
08-16 08:16:59.285  3979  4194 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 08:16:59.288   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 08:16:59.289  3979  4194 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 08:16:59.295  3979  4190 D BluetoothAdapterState: Current state: OFF, message: 0
08-16 08:16:59.296  3979  4190 D BluetoothAdapterProperties: Setting state to 14
,08-16 08:16:59.296  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 08:16:59.300  3979  4190 D BluetoothBondStateMachine: make
,08-16 08:16:59.305  3979  4195 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 08:16:59.311  3979  4190 I BluetoothAdapterState: Entering PendingCommandState
,08-16 08:16:59.313  3979  3979 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 08:16:59.317  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:16:59.318  3979  3979 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 08:16:59.318  3979  3979 D BtGatt.GattService: Received start request. Starting profile...
,08-16 08:16:59.319  3979  3979 D BtGatt.GattService: start()
,08-16 08:16:59.319  3979  3979 I bt_bluedroid: get_profile_interface gatt,
08-16 08:16:59.320  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
08-16 08:16:59.320  3979  3979 D BtGatt.AdvertiseManager: advertise manager created
,08-16 08:16:59.331  3979  3979 V BluetoothAdapterState: isTurningOff()=false
08-16 08:16:59.331  3979  3979 V BluetoothAdapterState: isTurningOn()=false
08-16 08:16:59.331  3979  3979 V BluetoothAdapterState: isBleTurningOn()=true
08-16 08:16:59.332  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:16:59.333  3979  4190 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 08:16:59.334  3979  4190 I bt_bluedroid: enable
,08-16 08:16:59.334  3979  4191 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 08:16:59.336  3979  4191 I bt_hci  : start_up
,08-16 08:16:59.357  3979  4191 I bt_vendor: alloc value 0xb3979189
,08-16 08:16:59.357  3979  4191 I bt_vendor: init
08-16 08:16:59.357  3979  4191 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 08:16:59.358  3979  4191 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 08:16:59.467  3979  4191 D bt_hci  : start_up starting async portion
08-16 08:16:59.467  3979  4198 I bt_hci  : event_finish_startup
08-16 08:16:59.468  3979  4198 I bt_hci_h4: hal_open
08-16 08:16:59.468  3979  4198 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 08:16:59.473  3979  4198 I bt_userial_vendor: device fd = 51 open
,08-16 08:16:59.487  4139  4162 I art     : Waiting for a blocking GC DisableMovingGc
,08-16 08:16:59.492  4139  4162 I art     : WaitForGcToComplete blocked for 5.198ms for cause DisableMovingGc
,08-16 08:16:59.492  4139  4162 I art     : Starting a blocking GC DisableMovingGc
,08-16 08:16:59.505  4139  4162 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 08:16:59.508  3979  4198 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 08:16:59.540  3979  4198 D bt_hwcfg: Chipset BCM4354A2
,08-16 08:16:59.541  3979  4198 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 08:16:59.541  3979  4198 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 08:17:00.219  3979  4198 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 08:17:00.221  3979  4198 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 08:17:00.221  3979  4198 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 08:17:00.338  3979  4198 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 08:17:00.339  3979  4198 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 08:17:00.369  3979  4198 I bt_hwcfg: vendor lib fwcfg completed
,08-16 08:17:00.369  3979  4198 I bt_vendor: firmware callback
08-16 08:17:00.369  3979  4198 I bt_hci  : firmware_config_callback
,08-16 08:17:00.380  3979  4202 I bt_btu  : btu_task pending for preload complete event
08-16 08:17:00.381  3979  4202 I bt_btu_task: Bluetooth chip preload is complete
08-16 08:17:00.381  3979  4202 I bt_btu  : btu_task received preload complete event
,08-16 08:17:00.391  3979  4202 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 08:17:00.391  3979  4202 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 08:17:00.391  3979  4202 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 08:17:00.392  3979  4202 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 08:17:00.392  3979  4202 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 08:17:00.392  3979  4202 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 08:17:00.392  3979  4202 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 08:17:00.393  3979  4202 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 08:17:00.393  3979  4202 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 08:17:00.393  3979  4202 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 08:17:00.394  3979  4202 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 08:17:00.394  3979  4202 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 08:17:00.394  3979  4202 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 08:17:00.394  3979  4202 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 08:17:00.395  3979  4202 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 08:17:00.530  3979  4202 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,08-16 08:17:00.530  3979  4202 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-16 08:17:00.555  3979  4194 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 08:17:00.557  3979  4194 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 08:17:00.558  3979  4194 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 08:17:00.563  3979  4194 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 08:17:00.567  3979  4194 D BluetoothAdapterProperties: Scan Mode:20
,08-16 08:17:00.568  3979  4194 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 08:17:00.569  3979  4194 D bt_hci  : do_postload posting postload work item
,08-16 08:17:00.570  3979  4198 I bt_hci  : event_postload
,08-16 08:17:00.570  3979  4198 I bt_vendor: sco_config_cb
08-16 08:17:00.570  3979  4198 I bt_hci  : sco_config_callback postload finished.
,08-16 08:17:00.571  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:00.576  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:00.576  3979  4194 D bt_bte_conf: Device ID record 1 : primary
,08-16 08:17:00.576  3979  4194 D bt_bte_conf:   vendorId            = 000f
,08-16 08:17:00.576  3979  4194 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 08:17:00.577  3979  4194 D bt_bte_conf:   product             = 1200
,08-16 08:17:00.577  3979  4194 D bt_bte_conf:   version             = 1436
,08-16 08:17:00.577  3979  4194 D bt_bte_conf:   clientExecutableURL = 
,08-16 08:17:00.577  3979  4194 D bt_bte_conf:   serviceDescription  = 
,08-16 08:17:00.577  3979  4198 I bt_vendor: low_power_mode_cb
08-16 08:17:00.577  3979  4194 D bt_bte_conf:   documentationURL    = 
08-16 08:17:00.578  3979  4194 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 08:17:00.578  3979  4191 D bt_stack_manager: event_start_up_stack finished
08-16 08:17:00.580  3979  4190 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 08:17:00.581  3979  4190 D BluetoothAdapterProperties: Setting state to 15
,08-16 08:17:00.581  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 08:17:00.582  3979  4190 I BluetoothAdapterState: Entering BleOnState
08-16 08:17:00.588  3979  4190 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 08:17:00.588  3979  4190 D BluetoothAdapterProperties: Setting state to 11
,08-16 08:17:00.589  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 08:17:00.600  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:00.605  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:00.613  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:00.614  3979  3979 D HeadsetService: Received start request. Starting profile...
08-16 08:17:00.617  3979  3979 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 08:17:00.617  3979  3979 D HeadsetStateMachine: make,
,08-16 08:17:00.630  3979  4190 I BluetoothAdapterState: Entering PendingCommandState
,08-16 08:17:00.633  3979  3979 D HeadsetStateMachine: max_hf_connections = 1
,08-16 08:17:00.633  3979  3979 I bt_bluedroid: get_profile_interface handsfree
,08-16 08:17:00.633  3979  4194 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 08:17:00.634  3979  4194 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 08:17:00.640  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:17:00.641  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:00.642  3979  3979 D A2dpService: Received start request. Starting profile...
,08-16 08:17:00.643  3979  3979 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 08:17:00.643  3979  3979 I bt_bluedroid: get_profile_interface avrcp
,08-16 08:17:00.651  3979  3979 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 08:17:00.651  3979  3979 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 08:17:00.652  3979  3979 D A2dpStateMachine: make
,08-16 08:17:00.653  3979  3979 I bt_bluedroid: get_profile_interface a2dp
,08-16 08:17:00.653  3979  4194 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 08:17:00.657  3979  4211 D A2dpStateMachine: Enter Disconnected: -2
,08-16 08:17:00.657  3979  3979 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 08:17:00.658  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:00.660  3900  3900 D BluetoothInputDevice: Proxy object connected
08-16 08:17:00.660  3979  3979 D HidService: Received start request. Starting profile...
08-16 08:17:00.660  3979  3979 I bt_bluedroid: get_profile_interface hidhost
08-16 08:17:00.660  3900  3900 D HidProfile: Bluetooth service connected
08-16 08:17:00.660  3979  3979 D HidService: setHidService(): set to: null
08-16 08:17:00.660  3979  4194 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-16 08:17:00.660  3979  4194 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 08:17:00.661  3979  3979 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 08:17:00.662  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7,
08-16 08:17:00.663  3979  3979 D HealthService: Received start request. Starting profile...
,08-16 08:17:00.664  3979  3979 I bt_bluedroid: get_profile_interface health
,08-16 08:17:00.666  3979  3979 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 08:17:00.667  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:00.668  3900  3900 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 08:17:00.668  3979  3979 D PanService: Received start request. Starting profile...
08-16 08:17:00.668  3979  3979 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 08:17:00.668  3979  3979 I bt_bluedroid: get_profile_interface pan
08-16 08:17:00.668  3900  3900 D PanProfile: Bluetooth service connected
,08-16 08:17:00.669  3979  4194 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 08:17:00.677  3979  3979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:00.681  3900  3900 D BluetoothMap: Proxy object connected
,08-16 08:17:00.681  3900  3900 D MapProfile: Bluetooth service connected
08-16 08:17:00.681  3900  3900 D BluetoothMap: getConnectedDevices()
08-16 08:17:00.682  3900  3900 D BluetoothMap: Bluetooth is Not enabled
08-16 08:17:00.682  3979  3979 D BluetoothMapService: Received start request. Starting profile...
08-16 08:17:00.682  3979  3979 D BluetoothMapService: start()
,08-16 08:17:00.686  3979  3979 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 08:17:00.687  3979  3979 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 08:17:00.687  3979  3979 D BluetoothMapAppObserver: createReceiver()
,08-16 08:17:00.688  3979  3979 D BluetoothMapAppObserver: initObservers()
,08-16 08:17:00.688  3979  3979 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 08:17:00.694  3979  3979 V BluetoothAdapterState: isTurningOff()=false
,08-16 08:17:00.694  3979  3979 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:00.694  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:00.694  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:00.697  3979  4208 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isTurningOff()=false
,08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:00.698  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:00.699  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:17:00.700  3979  4190 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 08:17:00.700  3979  4190 D BluetoothAdapterProperties: ScanMode =  20
08-16 08:17:00.700  3979  4190 D BluetoothAdapterProperties: State =  11
08-16 08:17:00.702  3979  4194 D BluetoothAdapterProperties: Scan Mode:21
08-16 08:17:00.702  3979  4194 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 08:17:00.702  3979  4190 D BluetoothAdapterProperties: Setting state to 12
08-16 08:17:00.702  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 08:17:00.702  3979  4190 I BluetoothAdapterState: Entering OnState
08-16 08:17:00.703  1361  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 08:17:00.706  1361  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 08:17:00.706  1361  1361 D BluetoothInputDevice: Proxy object connected
,08-16 08:17:00.706  1361  1361 D HidProfile: Bluetooth service connected
08-16 08:17:00.706  1361  2021 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:17:00.706  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:17:00.709  3900  3911 D BluetoothMap: onBluetoothStateChange: up=true
08-16 08:17:00.709  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 08:17:00.709  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:17:00.710  1361  1372 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 08:17:00.711  3900  3912 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 08:17:00.711   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 08:17:00.711   873   873 D BluetoothA2dp: Proxy object connected
08-16 08:17:00.711  1361  2021 D BluetoothPan: onBluetoothStateChange on: true
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:17:00.712  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:17:00.714  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 08:17:00.714   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:17:00.714  1361  1361 D PanProfile: Bluetooth service connected
,08-16 08:17:00.714   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:17:00.714  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:17:00.714  3900  3911 D BluetoothPan: onBluetoothStateChange on: true
08-16 08:17:00.714  1911  2037 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:17:00.715  3979  3979 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 08:17:00.715  1361  1372 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 08:17:00.715  3979  3979 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 08:17:00.716  1361  1361 D BluetoothMap: Proxy object connected
,08-16 08:17:00.716  1361  1361 D MapProfile: Bluetooth service connected
08-16 08:17:00.716   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:17:00.716  1361  1361 D BluetoothMap: getConnectedDevices()
08-16 08:17:00.716  3900  3912 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 08:17:00.716  3979  3979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 08:17:00.719  3979  3979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 08:17:00.720   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 08:17:00.721  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:00.722  3979  3979 D ObexServerSockets: Succeed to create listening sockets 
,08-16 08:17:00.722  3979  3979 D ObexServerSockets0: startAccept()
08-16 08:17:00.722  3979  3979 D ObexServerSockets0: prepareForNewConnect()
08-16 08:17:00.722  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:00.722  3900  3900 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 08:17:00.723  3979  3979 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 08:17:00.723  3979  3979 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 08:17:00.723  3979  3979 D BluetoothMapService: onReceive
08-16 08:17:00.724  3979  3979 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:17:00.724  3979  3979 D BluetoothMapService: STATE_ON
08-16 08:17:00.724  3979  4217 D ObexServerSockets0: Accepting socket connection...
08-16 08:17:00.725  3979  4218 D ObexServerSockets0: Accepting socket connection...
,08-16 08:17:00.728  3900  3900 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 08:17:00.734  3900  3900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 08:17:00.737  3900  3900 D BluetoothA2dp: Proxy object connected
,08-16 08:17:00.741  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:17:00.742  3900  3900 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:17:00.748  1361  1361 D BluetoothPbap: Proxy object connected
,08-16 08:17:00.748  1361  1361 D PbapServerProfile: Bluetooth service connected
08-16 08:17:00.748  3979  3979 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 08:17:00.748  3979  3979 D ObexServerSockets0: prepareForNewConnect()
08-16 08:17:00.748  3900  3900 D BluetoothPbap: Proxy object connected
,08-16 08:17:00.750  3900  3900 D PbapServerProfile: Bluetooth service connected
,08-16 08:17:00.754  3979  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 08:17:00.765  3979  4226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 08:17:00.766  3979  4226 I BtOppRfcommListener: Accept thread started.
,08-16 08:17:00.808   873   873 D BluetoothHeadset: Proxy object connected
,08-16 08:17:00.808   873   873 D BluetoothHeadset: Proxy object connected
08-16 08:17:00.808  1911  1925 D BluetoothHeadset: Proxy object connected
08-16 08:17:00.808   873   873 D BluetoothHeadset: Proxy object connected
,08-16 08:17:00.808  1361  1378 D BluetoothHeadset: Proxy object connected
08-16 08:17:00.808  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 08:17:00.814   873   890 D BluetoothHeadset: Proxy object connected
,08-16 08:17:00.814   873   890 D BluetoothHeadset: Proxy object connected
08-16 08:17:00.814  1911  1926 D BluetoothHeadset: Proxy object connected
,08-16 08:17:00.817   873   890 D BluetoothHeadset: Proxy object connected
,08-16 08:17:00.831  3900  3911 D BluetoothHeadset: Proxy object connected
,08-16 08:17:00.832  3900  3900 D HeadsetProfile: Bluetooth service connected
,08-16 08:17:02.195   873  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-16 08:17:02.249  3979  4190 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 08:17:02.250  3979  4190 D BluetoothAdapterProperties: Setting state to 13
,08-16 08:17:02.250  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 08:17:02.252  3979  4190 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 08:17:02.255  3979  4190 I BluetoothAdapterState: Entering PendingCommandState
,08-16 08:17:02.260  3979  4194 D BluetoothAdapterProperties: Scan Mode:20
,08-16 08:17:02.261  3979  4190 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 08:17:02.266  3979  3979 D BluetoothMapService: onReceive
,08-16 08:17:02.267  3979  3979 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 08:17:02.267  3979  3979 D BluetoothMapService: STATE_TURNING_OFF
,08-16 08:17:02.268  3979  3979 D BluetoothMapService: MAP Service closeService in
,08-16 08:17:02.268  3979  3979 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 08:17:02.268  3979  3979 D ObexServerSockets0: shutdown(block = true)
,08-16 08:17:02.269  3979  4217 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 08:17:02.273  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:17:02.273  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 08:17:02.274  3979  3979 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 08:17:02.275  3979  4218 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 08:17:02.275  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 08:17:02.275  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:17:02.279  3979  4205 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 08:17:02.280  3979  3979 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 08:17:02.280  3979  3979 I BtOppRfcommListener: stopping Accept Thread
,08-16 08:17:02.280  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:17:02.280  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:17:02.281  3979  4226 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 08:17:02.281  3979  4226 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 08:17:02.282  3833  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 08:17:02.282  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 08:17:02.285  3979  3979 D HeadsetService: Received stop request...Stopping profile...
,08-16 08:17:02.285  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:02.287  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:02.288  3900  3900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 08:17:02.289   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 08:17:02.289   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 08:17:02.289  3900  3912 D BluetoothHeadset: Proxy object disconnected
08-16 08:17:02.290  1911  2152 D BluetoothHeadset: Proxy object disconnected
08-16 08:17:02.290   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 08:17:02.291  1361  1372 D BluetoothHeadset: Proxy object disconnected
08-16 08:17:02.291  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,08-16 08:17:02.293  3900  3900 D HeadsetProfile: Bluetooth service disconnected
,08-16 08:17:02.294  3979  3979 D A2dpService: Received stop request...Stopping profile...
,08-16 08:17:02.294  3979  4211 D A2dpStateMachine: Exit Disconnected: -1
08-16 08:17:02.295   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 08:17:02.296  1361  1361 D BluetoothA2dp: Proxy object disconnected
,08-16 08:17:02.296  3979  3979 D HidService: Received stop request...Stopping profile...
08-16 08:17:02.296  3979  3979 D HidService: Stopping Bluetooth HidService
,08-16 08:17:02.297  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 08:17:02.297  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 08:17:02.297  3979  3979 D HealthService: Received stop request...Stopping profile...
,08-16 08:17:02.298  3979  3979 D PanService: Received stop request...Stopping profile...
,08-16 08:17:02.299  3979  3979 V BluetoothAdapterState: isTurningOff()=true
,08-16 08:17:02.299  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 08:17:02.299  3979  3979 V BluetoothAdapterState: isTurningOn()=false
08-16 08:17:02.299  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 08:17:02.299  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:02.300  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:02.300  3979  3979 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 08:17:02.300  3979  3979 D BluetoothMapService: stop()
08-16 08:17:02.301  3979  3979 D BluetoothMapAppObserver: deinitObservers()
08-16 08:17:02.301  3979  3979 D BluetoothMapAppObserver: removeReceiver()
,08-16 08:17:02.303  3900  3900 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:17:02.303  1361  1361 D BluetoothMap: Proxy object disconnected
08-16 08:17:02.303  1361  1361 D MapProfile: Bluetooth service disconnected
,08-16 08:17:02.303  3900  3900 D BluetoothA2dp: Proxy object disconnected
08-16 08:17:02.304  3900  3900 D BluetoothInputDevice: Proxy object disconnected
08-16 08:17:02.304  3900  3900 D HidProfile: Bluetooth service disconnected,
08-16 08:17:02.304  3900  3900 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 08:17:02.304  3900  3900 D PanProfile: Bluetooth service disconnected,
08-16 08:17:02.304  3979  3979 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 08:17:02.304  3979  4194 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 08:17:02.304  3979  4202 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:17:02.304  3979  3979 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 08:17:02.304  3900  3900 D BluetoothMap: Proxy object disconnected
,08-16 08:17:02.304  3979  4202 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:17:02.305  3979  4202 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 08:17:02.305  3900  3900 D MapProfile: Bluetooth service disconnected
,08-16 08:17:02.305  3979  4194 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 08:17:02.306  3979  3979 V BluetoothAdapterState: isTurningOff()=true
08-16 08:17:02.307  3979  3979 V BluetoothAdapterState: isTurningOn()=false
,08-16 08:17:02.307  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:02.307  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:02.308  3979  4194 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 08:17:02.308  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 08:17:02.308  3979  4202 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:17:02.308  3979  4202 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 08:17:02.308  3979  4202 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:17:02.308  3979  4202 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 08:17:02.308  3979  4202 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 08:17:02.308  3979  4202 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 08:17:02.312  3979  3979 V BluetoothAdapterState: isTurningOff()=true
08-16 08:17:02.312  3979  3979 V BluetoothAdapterState: isTurningOn()=false
08-16 08:17:02.312  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:02.312  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:17:02.312  3979  3979 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 08:17:02.313  3979  4194 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 08:17:02.313  3979  3979 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 08:17:02.313  3979  3979 V BluetoothAdapterState: isTurningOff()=true
08-16 08:17:02.313  3979  3979 V BluetoothAdapterState: isTurningOn()=false
08-16 08:17:02.313  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:02.313  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:02.314  3979  3979 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 08:17:02.314  3979  4194 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 08:17:02.314  3979  3979 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 08:17:02.314  3979  3979 V BluetoothAdapterState: isTurningOff()=true
,08-16 08:17:02.314  3979  3979 V BluetoothAdapterState: isTurningOn()=false
08-16 08:17:02.314  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:02.314  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:02.315  3979  3979 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 08:17:02.315  3979  3979 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 08:17:02.316  3979  3979 D BluetoothMapService: MAP Service closeService in
08-16 08:17:02.316  3979  3979 V BluetoothAdapterState: isTurningOff()=true
08-16 08:17:02.316  3979  3979 V BluetoothAdapterState: isTurningOn()=false
,08-16 08:17:02.316  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:02.316  3979  3979 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:02.316  3979  3979 D BluetoothMapService: cleanup()
08-16 08:17:02.316  3979  3979 D BluetoothMapService: MAP Service closeService in
08-16 08:17:02.316  3979  4190 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 08:17:02.316  3979  4190 D BluetoothAdapterProperties: Setting state to 15
,08-16 08:17:02.316  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 08:17:02.317  3979  4190 I BluetoothAdapterState: Entering BleOnState
08-16 08:17:02.317  3900  3911 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 08:17:02.318  1361  1361 D BluetoothPbap: Proxy object disconnected
08-16 08:17:02.318  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-16 08:17:02.318  3900  3900 D BluetoothPbap: Proxy object disconnected
08-16 08:17:02.319  3900  3900 D PbapServerProfile: Bluetooth service disconnected
08-16 08:17:02.319  3900  4229 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 08:17:02.319  1361  2021 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 08:17:02.322  1361  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:17:02.322  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 08:17:02.324  3900  3912 D BluetoothMap: onBluetoothStateChange: up=false
08-16 08:17:02.324  1361  2021 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 08:17:02.325  3900  3911 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 08:17:02.325   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 08:17:02.325  1361  1378 D BluetoothPan: onBluetoothStateChange on: false
,08-16 08:17:02.326   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:17:02.326   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:17:02.326  3900  4229 D BluetoothPan: onBluetoothStateChange on: false
08-16 08:17:02.327  1911  2037 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:17:02.327  1361  1372 D BluetoothMap: onBluetoothStateChange: up=false
08-16 08:17:02.327   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 08:17:02.327  3900  3912 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 08:17:02.328  3979  4190 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 08:17:02.328  3979  4190 D BluetoothAdapterProperties: Setting state to 16
08-16 08:17:02.328  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 08:17:02.329  3979  4190 D BluetoothAdapterProperties: onBleDisable
08-16 08:17:02.329  3979  4190 I BluetoothAdapterState: Entering PendingCommandState
,08-16 08:17:02.329  3979  4191 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 08:17:02.331  3979  4202 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 08:17:02.331  3979  4202 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
,08-16 08:17:02.333  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:02.334  3979  4194 D BluetoothAdapterProperties: Scan Mode:20
08-16 08:17:02.334  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:02.335  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:02.336  3900  3900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 08:17:02.336  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:02.340  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:17:02.344  3900  3900 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:17:02.532  3979  4194 I bt_hci  : shut_down
,08-16 08:17:02.532  3979  4198 D bt_hwcfg: hw_epilog_process
,08-16 08:17:02.545  3979  4198 I bt_vendor: low_power_mode_cb
,08-16 08:17:02.574  3979  4198 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 08:17:02.574  3979  4198 I bt_vendor: epilog_cb
,08-16 08:17:02.575  3979  4198 I bt_hci  : epilog_finished_callback
,08-16 08:17:02.583  3979  4194 I bt_hci_h4: hal_close
,08-16 08:17:02.585  3979  4194 I bt_userial_vendor: device fd = 51 close
,08-16 08:17:02.704  3979  4191 D bt_stack_manager: event_shut_down_stack finished.
,08-16 08:17:02.705  3979  4190 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 08:17:02.713  3979  4190 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 08:17:02.713  3979  3979 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 08:17:02.714  3979  3979 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 08:17:02.715  3979  3979 D BtGatt.GattService: stop()
08-16 08:17:02.715  3979  3979 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 08:17:02.720  3979  3979 V BluetoothAdapterState: isTurningOff()=false
,08-16 08:17:02.720  3979  3979 V BluetoothAdapterState: isTurningOn()=false
08-16 08:17:02.721  3979  3979 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:02.721  3979  3979 V BluetoothAdapterState: isBleTurningOff()=true
08-16 08:17:02.722  3979  4190 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 08:17:02.725  3979  4190 D BluetoothAdapterProperties: Setting state to 10
,08-16 08:17:02.726  3979  4190 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 08:17:02.728  3979  4190 I BluetoothAdapterState: Entering OffState
,08-16 08:17:02.729   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 08:17:02.750  3979  3979 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 08:17:02.750  3979  3979 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 08:17:02.751  3979  4191 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-16 08:17:02.751  3979  3979 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 08:17:02.753  3979  4191 D bt_stack_manager: event_clean_up_stack finished.
,08-16 08:17:02.757  3979  3979 I art     : System.exit called, status: 0
08-16 08:17:02.757  3979  3979 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 08:17:02.824   873  2961 I ActivityManager: Process com.android.bluetooth (pid 3979) has died
,08-16 08:17:04.596  3540  3551 D Finsky  : [269] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-16 08:17:04.614  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:17:04.626  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:17:04.630  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:17:04.660  1511  2300 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-16 08:17:04.660  1511  2300 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.,
08-16 08:17:04.660  1511  2300 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 08:17:04.660  1511  2300 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:17:04.683  3540  3551 D Finsky  : [269] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-16 08:17:05.246  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:17:05.246  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:17:08.254  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:08.254  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce91803 added. We now have 6 listener(s)
,08-16 08:17:08.255  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:17:08.258  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 08:17:08.259  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9e25380 added. We now have 7 listener(s)
,08-16 08:17:08.259  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:17:08.260  3833  3884 I System.out: IsBluetoothEnabled
,08-16 08:17:08.272  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:08.326   873   890 I ActivityManager: Start proc 4239:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 08:17:08.452  4239  4239 D AdapterServiceConfig: Adding HeadsetService
,08-16 08:17:08.452  4239  4239 D AdapterServiceConfig: Adding A2dpService
08-16 08:17:08.453  4239  4239 D AdapterServiceConfig: Adding HidService
08-16 08:17:08.453  4239  4239 D AdapterServiceConfig: Adding HealthService
,08-16 08:17:08.453  4239  4239 D AdapterServiceConfig: Adding PanService
08-16 08:17:08.454  4239  4239 D AdapterServiceConfig: Adding GattService
,08-16 08:17:08.455  4239  4239 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 08:17:08.471  4239  4239 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 08:17:08.471   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ae4ac8:true
,08-16 08:17:08.476  4239  4239 I bt_bluedroid: init
,08-16 08:17:08.477  4239  4251 I BluetoothAdapterState: Entering OffState
,08-16 08:17:08.478  4239  4252 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 08:17:08.479  4239  4252 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 08:17:08.479  4239  4252 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 08:17:08.479  4239  4252 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 08:17:08.479  4239  4239 I bt_bluedroid: get_profile_interface socket
,08-16 08:17:08.483  4239  4239 I bt_bluedroid: get_profile_interface sdp
,08-16 08:17:08.483  4239  4255 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 08:17:08.485  4239  4255 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 08:17:08.487  4239  4250 I bt_bluedroid: config_hci_snoop_log
,08-16 08:17:08.490   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 08:17:08.501  4239  4251 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 08:17:08.501  4239  4251 D BluetoothAdapterProperties: Setting state to 14
08-16 08:17:08.502  4239  4251 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 08:17:08.506  4239  4251 D BluetoothBondStateMachine: make
,08-16 08:17:08.509  4239  4256 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 08:17:08.516  4239  4239 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 08:17:08.519  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:08.519  4239  4239 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 08:17:08.520  4239  4239 D BtGatt.GattService: Received start request. Starting profile...
,08-16 08:17:08.520  4239  4239 D BtGatt.GattService: start()
08-16 08:17:08.520  4239  4251 I BluetoothAdapterState: Entering PendingCommandState
,08-16 08:17:08.520  4239  4239 I bt_bluedroid: get_profile_interface gatt
08-16 08:17:08.521  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
08-16 08:17:08.521  4239  4239 D BtGatt.AdvertiseManager: advertise manager created
,08-16 08:17:08.527  4239  4239 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:08.527  4239  4239 V BluetoothAdapterState: isTurningOn()=false
,08-16 08:17:08.527  4239  4239 V BluetoothAdapterState: isBleTurningOn()=true
08-16 08:17:08.527  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 08:17:08.527  4239  4251 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 08:17:08.528  4239  4251 I bt_bluedroid: enable
,08-16 08:17:08.528  4239  4252 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 08:17:08.528  4239  4252 I bt_hci  : start_up
,08-16 08:17:08.533  4239  4252 I bt_vendor: alloc value 0xb39f0189
,08-16 08:17:08.533  4239  4252 I bt_vendor: init
08-16 08:17:08.533  4239  4252 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 08:17:08.533  4239  4252 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 08:17:08.641  4239  4252 D bt_hci  : start_up starting async portion
,08-16 08:17:08.641  4239  4259 I bt_hci  : event_finish_startup
08-16 08:17:08.642  4239  4259 I bt_hci_h4: hal_open
08-16 08:17:08.642  4239  4259 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 08:17:08.652  4239  4259 I bt_userial_vendor: device fd = 51 open
,08-16 08:17:08.683  4239  4259 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 08:17:08.714  4239  4259 D bt_hwcfg: Chipset BCM4354A2
,08-16 08:17:08.714  4239  4259 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 08:17:08.715  4239  4259 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 08:17:09.380  4239  4259 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 08:17:09.382  4239  4259 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 08:17:09.382  4239  4259 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 08:17:09.499  4239  4259 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 08:17:09.500  4239  4259 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 08:17:09.530  4239  4259 I bt_hwcfg: vendor lib fwcfg completed
,08-16 08:17:09.530  4239  4259 I bt_vendor: firmware callback
08-16 08:17:09.530  4239  4259 I bt_hci  : firmware_config_callback
,08-16 08:17:09.543  4239  4261 I bt_btu  : btu_task pending for preload complete event
,08-16 08:17:09.543  4239  4261 I bt_btu_task: Bluetooth chip preload is complete
08-16 08:17:09.543  4239  4261 I bt_btu  : btu_task received preload complete event
,08-16 08:17:09.555  4239  4261 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 08:17:09.555  4239  4261 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 08:17:09.556  4239  4261 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 08:17:09.556  4239  4261 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 08:17:09.556  4239  4261 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 08:17:09.557  4239  4261 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 08:17:09.557  4239  4261 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 08:17:09.558  4239  4261 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 08:17:09.558  4239  4261 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 08:17:09.559  4239  4261 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 08:17:09.560  4239  4261 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 08:17:09.560  4239  4261 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 08:17:09.561  4239  4261 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 08:17:09.562  4239  4261 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 08:17:09.562  4239  4261 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 08:17:09.695  4239  4261 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396dd9d
,08-16 08:17:09.696  4239  4261 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396dd9d 
,08-16 08:17:09.726  4239  4255 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 08:17:09.729  4239  4255 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 08:17:09.729  4239  4255 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 08:17:09.732  4239  4255 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 08:17:09.736  4239  4255 D BluetoothAdapterProperties: Scan Mode:20
,08-16 08:17:09.737  4239  4255 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 08:17:09.737  4239  4255 D bt_hci  : do_postload posting postload work item
,08-16 08:17:09.738  4239  4259 I bt_hci  : event_postload
,08-16 08:17:09.738  4239  4259 I bt_vendor: sco_config_cb,
08-16 08:17:09.738  4239  4259 I bt_hci  : sco_config_callback postload finished.
,08-16 08:17:09.740  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:09.741  4239  4255 D bt_bte_conf: Device ID record 1 : primary
,08-16 08:17:09.742  4239  4255 D bt_bte_conf:   vendorId            = 000f
08-16 08:17:09.743  4239  4255 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 08:17:09.743  4239  4255 D bt_bte_conf:   product             = 1200
08-16 08:17:09.743  4239  4255 D bt_bte_conf:   version             = 1436
08-16 08:17:09.743  4239  4255 D bt_bte_conf:   clientExecutableURL = 
08-16 08:17:09.743  4239  4255 D bt_bte_conf:   serviceDescription  = 
08-16 08:17:09.744  4239  4255 D bt_bte_conf:   documentationURL    = 
08-16 08:17:09.744  4239  4255 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 08:17:09.744  4239  4252 D bt_stack_manager: event_start_up_stack finished
08-16 08:17:09.746  4239  4259 I bt_vendor: low_power_mode_cb
08-16 08:17:09.746  4239  4251 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 08:17:09.747  4239  4251 D BluetoothAdapterProperties: Setting state to 15
08-16 08:17:09.747  4239  4251 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 08:17:09.748  4239  4251 I BluetoothAdapterState: Entering BleOnState
,08-16 08:17:09.750  4239  4251 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 08:17:09.751  4239  4251 D BluetoothAdapterProperties: Setting state to 11
08-16 08:17:09.751  4239  4251 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 08:17:09.756  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:09.758  4239  4239 D HeadsetService: Received start request. Starting profile...
08-16 08:17:09.761  4239  4239 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 08:17:09.761  4239  4239 D HeadsetStateMachine: make
08-16 08:17:09.764  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:09.774  4239  4239 D HeadsetStateMachine: max_hf_connections = 1
,08-16 08:17:09.775  4239  4239 I bt_bluedroid: get_profile_interface handsfree
,08-16 08:17:09.775  4239  4255 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 08:17:09.775  4239  4255 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-16 08:17:09.781  4239  4251 I BluetoothAdapterState: Entering PendingCommandState
,08-16 08:17:09.782  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
08-16 08:17:09.783  4239  4239 D A2dpService: Received start request. Starting profile...
08-16 08:17:09.783  4239  4239 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 08:17:09.784  4239  4239 I bt_bluedroid: get_profile_interface avrcp
,08-16 08:17:09.790  4239  4239 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 08:17:09.791  4239  4239 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 08:17:09.791  4239  4239 D A2dpStateMachine: make
,08-16 08:17:09.792  4239  4239 I bt_bluedroid: get_profile_interface a2dp
08-16 08:17:09.793  4239  4255 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 08:17:09.796  4239  4270 D A2dpStateMachine: Enter Disconnected: -2
,08-16 08:17:09.796  4239  4239 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 08:17:09.797  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:09.800  4239  4239 D HidService: Received start request. Starting profile...
,08-16 08:17:09.800  4239  4239 I bt_bluedroid: get_profile_interface hidhost
08-16 08:17:09.800  4239  4239 D HidService: setHidService(): set to: null
,08-16 08:17:09.801  4239  4255 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394f3e5
08-16 08:17:09.801  4239  4255 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 08:17:09.803  4239  4239 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 08:17:09.804  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:09.804  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:17:09.806  4239  4239 D HealthService: Received start request. Starting profile...
,08-16 08:17:09.807  4239  4239 I bt_bluedroid: get_profile_interface health
,08-16 08:17:09.808  4239  4239 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 08:17:09.809  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:09.810  4239  4239 D PanService: Received start request. Starting profile...
,08-16 08:17:09.810  4239  4239 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 08:17:09.810  4239  4239 I bt_bluedroid: get_profile_interface pan
,08-16 08:17:09.811  4239  4255 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 08:17:09.813  4239  4239 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:09.814  4239  4239 D BluetoothMapService: Received start request. Starting profile...
08-16 08:17:09.814  4239  4239 D BluetoothMapService: start()
,08-16 08:17:09.817  4239  4239 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 08:17:09.817  4239  4239 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 08:17:09.818  4239  4239 D BluetoothMapAppObserver: createReceiver()
,08-16 08:17:09.819  4239  4239 D BluetoothMapAppObserver: initObservers()
,08-16 08:17:09.819  4239  4239 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 08:17:09.825  4239  4239 V BluetoothAdapterState: isTurningOff()=false
,08-16 08:17:09.826  4239  4239 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:09.826  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:09.826  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:09.828  4239  4267 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 08:17:09.828  4239  4239 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:09.828  4239  4239 V BluetoothAdapterState: isTurningOn()=true
08-16 08:17:09.829  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:09.829  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:09.829  4239  4239 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:09.829  4239  4239 V BluetoothAdapterState: isTurningOn()=true
08-16 08:17:09.829  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:09.829  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:09.830  4239  4239 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:09.830  4239  4239 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:09.830  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:09.830  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:09.830  4239  4239 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:09.831  4239  4239 V BluetoothAdapterState: isTurningOn()=true
,08-16 08:17:09.831  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
08-16 08:17:09.831  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:09.831  4239  4239 V BluetoothAdapterState: isTurningOff()=false
08-16 08:17:09.831  4239  4239 V BluetoothAdapterState: isTurningOn()=true
08-16 08:17:09.831  4239  4239 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 08:17:09.832  4239  4239 V BluetoothAdapterState: isBleTurningOff()=false
08-16 08:17:09.832  4239  4251 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 08:17:09.832  4239  4251 D BluetoothAdapterProperties: ScanMode =  20
08-16 08:17:09.832  4239  4251 D BluetoothAdapterProperties: State =  11
08-16 08:17:09.833  4239  4255 D BluetoothAdapterProperties: Scan Mode:21
08-16 08:17:09.834  4239  4255 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 08:17:09.834  4239  4251 D BluetoothAdapterProperties: Setting state to 12
08-16 08:17:09.834  4239  4251 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 08:17:09.835  4239  4251 I BluetoothAdapterState: Entering OnState
08-16 08:17:09.836  3900  3912 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:17:09.842  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:17:09.843  3900  3911 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 08:17:09.844  3900  3900 D BluetoothA2dp: Proxy object connected
,08-16 08:17:09.845  1361  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 08:17:09.845  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:17:09.846  4239  4239 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 08:17:09.847  4239  4239 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 08:17:09.848  4239  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:17:09.850  1361  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 08:17:09.851  4239  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 08:17:09.851  1361  2021 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 08:17:09.852  4239  4239 D ObexServerSockets: Succeed to create listening sockets 
08-16 08:17:09.852  4239  4239 D ObexServerSockets0: startAccept()
08-16 08:17:09.852  4239  4239 D ObexServerSockets0: prepareForNewConnect()
,08-16 08:17:09.854  3900  4229 D BluetoothMap: onBluetoothStateChange: up=true
08-16 08:17:09.854  1361  1361 D BluetoothA2dp: Proxy object connected
,08-16 08:17:09.854  4239  4239 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 08:17:09.855  4239  4239 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 08:17:09.856  1361  1378 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 08:17:09.857  1361  1361 D BluetoothInputDevice: Proxy object connected
08-16 08:17:09.857  1361  1361 D HidProfile: Bluetooth service connected
08-16 08:17:09.857  4239  4276 D ObexServerSockets0: Accepting socket connection...
08-16 08:17:09.857  4239  4275 D ObexServerSockets0: Accepting socket connection...
08-16 08:17:09.858  3900  3900 D BluetoothMap: Proxy object connected
08-16 08:17:09.858  3900  3900 D MapProfile: Bluetooth service connected
,08-16 08:17:09.858  3900  3900 D BluetoothMap: getConnectedDevices()
,08-16 08:17:09.859  3900  3911 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 08:17:09.862   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 08:17:09.863   873   873 D BluetoothA2dp: Proxy object connected
,08-16 08:17:09.863  1361  1372 D BluetoothPan: onBluetoothStateChange on: true
,08-16 08:17:09.864  3900  3900 D BluetoothInputDevice: Proxy object connected
08-16 08:17:09.864  3900  3900 D HidProfile: Bluetooth service connected
,08-16 08:17:09.866   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 08:17:09.867  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 08:17:09.867   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 08:17:09.867  1361  1361 D PanProfile: Bluetooth service connected
,08-16 08:17:09.867  3900  3912 D BluetoothPan: onBluetoothStateChange on: true
08-16 08:17:09.870  3900  3900 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 08:17:09.871  3900  3900 D PanProfile: Bluetooth service connected
,08-16 08:17:09.871  1911  2037 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 08:17:09.872  1361  1378 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 08:17:09.876  1361  1361 D BluetoothMap: Proxy object connected
,08-16 08:17:09.876  1361  1361 D MapProfile: Bluetooth service connected
,08-16 08:17:09.876  1361  1361 D BluetoothMap: getConnectedDevices()
,08-16 08:17:09.878   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 08:17:09.878  3900  3911 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 08:17:09.889   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 08:17:09.890  4239  4239 D BluetoothMapService: onReceive
,08-16 08:17:09.890  4239  4239 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 08:17:09.890  4239  4239 D BluetoothMapService: STATE_ON
,08-16 08:17:09.895  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:09.899  3900  3900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 08:17:09.910  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 08:17:09.916  3900  3900 D DockEventReceiver: finishStartingService: stopping service
,08-16 08:17:09.926  1361  1361 D BluetoothPbap: Proxy object connected
,08-16 08:17:09.926  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-16 08:17:09.929  4239  4239 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 08:17:09.929  4239  4239 D ObexServerSockets0: prepareForNewConnect()
,08-16 08:17:09.932  3900  3900 D BluetoothPbap: Proxy object connected
,08-16 08:17:09.932  3900  3900 D PbapServerProfile: Bluetooth service connected
,08-16 08:17:09.940  4239  4282 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 08:17:09.947   873   873 D BluetoothHeadset: Proxy object connected
,08-16 08:17:09.947   873   873 D BluetoothHeadset: Proxy object connected
,08-16 08:17:09.948  3900  4229 D BluetoothHeadset: Proxy object connected
,08-16 08:17:09.948  1911  1925 D BluetoothHeadset: Proxy object connected
,08-16 08:17:09.948   873   873 D BluetoothHeadset: Proxy object connected
08-16 08:17:09.949  1361  1378 D BluetoothHeadset: Proxy object connected
08-16 08:17:09.949  1361  1361 D HeadsetProfile: Bluetooth service connected
08-16 08:17:09.949  3900  3900 D HeadsetProfile: Bluetooth service connected
08-16 08:17:09.950  1361  1372 D BluetoothHeadset: Proxy object connected
08-16 08:17:09.951  1361  1361 D HeadsetProfile: Bluetooth service connected
08-16 08:17:09.960  4239  4286 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 08:17:09.961  4239  4286 I BtOppRfcommListener: Accept thread started.
,08-16 08:17:09.967   873   890 D BluetoothHeadset: Proxy object connected
,08-16 08:17:09.967   873   890 D BluetoothHeadset: Proxy object connected
,08-16 08:17:09.971  1911  1926 D BluetoothHeadset: Proxy object connected
,08-16 08:17:09.979   873   890 D BluetoothHeadset: Proxy object connected
,08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:17:10.295  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:17:10.301  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:17:10.304  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 08:17:10.305  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fcebdb9 added. We now have 8 listener(s)
08-16 08:17:10.305  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:17:10.312   873   884 D WifiService: setWifiEnabled: false pid=3833, uid=10000
,08-16 08:17:10.312   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 08:17:10.324  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:10.325   873  1940 D WifiService: setWifiEnabled: true pid=3833, uid=10000
,08-16 08:17:10.325   873  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 08:17:10.336   873  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 08:17:10.360  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 08:17:10.364  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 08:17:10.369   873  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-16 08:17:10.370   873  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 08:17:10.371   873  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 08:17:10.372   873  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 08:17:10.373   873  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 08:17:10.373   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 08:17:10.373   873  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 08:17:10.389   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 08:17:10.391   373   871 D CommandListener: Setting iface cfg
,08-16 08:17:10.393   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 08:17:10.393   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 08:17:10.392   873  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.00 rxSuccessRate=1.13 delta 1000 -> 1000
,08-16 08:17:10.402   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 08:17:10.403   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 08:17:10.417   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 08:17:10.417   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 08:17:10.439   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 08:17:10.504   873  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 08:17:10.508  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 08:17:10.969  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 08:17:10.996  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 08:17:10.996  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 08:17:11.001   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 08:17:11.008   873  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 08:17:11.008   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 08:17:11.008   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 08:17:11.025   873  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 08:17:11.033   373   871 D CommandListener: Setting iface cfg
,08-16 08:17:11.034   873  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 08:17:11.044   873  4296 D DhcpClient: Receive thread started
,08-16 08:17:11.047   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 08:17:11.047   873  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 08:17:11.048   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 08:17:11.105  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:17:11.114  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:17:11.116  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 08:17:11.132   873  1305 E native  : do suspend false
,08-16 08:17:11.146   873  1852 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 08:17:11.155  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 08:17:11.155  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 08:17:11.155  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 08:17:11.155  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:17:11.159   873  4296 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-16 08:17:11.160   873  1852 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 08:17:11.163   873  1852 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 08:17:11.174   873  4296 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 08:17:11.175   873  1852 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 08:17:11.179   373   871 D CommandListener: Setting iface cfg
,08-16 08:17:11.184   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 08:17:11.191  3540  3540 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 08:17:11.191  3540  3540 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 08:17:11.191  3540  3540 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-16 08:17:11.194   873  1852 D DhcpClient: Scheduling renewal in 86399s
,08-16 08:17:11.199   873  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 08:17:11.200   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 08:17:11.201   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 08:17:11.203   873  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 08:17:11.209   873  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 08:17:11.260   873  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 08:17:11.261   873  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 08:17:11.261   873  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 08:17:11.262   873  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 08:17:11.263   873  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 08:17:11.269   873  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 08:17:11.273   873  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-16 08:17:11.274   873  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 08:17:11.274   873  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 08:17:11.274   873  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 08:17:11.274   873  1307 D ConnectivityService:    accepting network in place of null
08-16 08:17:11.274   873  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 08:17:11.275   873  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 08:17:11.280   873  4295 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145475, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 08:17:11.312   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:17:11.343  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:17:11.349   873  4294 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:805::200e
08-16 08:17:11.350  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:17:11.353  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 08:17:11.353  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 08:17:11.354   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 08:17:11.355  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@971e943 Bundle[{}]
,08-16 08:17:11.356  3833  3884 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 08:17:11.358  3833  3884 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 08:17:11.359  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 08:17:11.360  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 08:17:11.360  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 08:17:11.361  3833  3884 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 08:17:11.362   873  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 08:17:11.362   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 08:17:11.365  3833  3884 I System.out: Running OutgoingSocketThread
,08-16 08:17:11.368  3833  4304 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-16 08:17:11.371   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 08:17:11.377   873  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 08:17:11.380  3833  4304 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42735
08-16 08:17:11.380  3833  4304 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:17:11.382  3833  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 08:17:11.385  3833  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:17:11.392  1995  1995 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 08:17:11.399  1716  1716 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 08:17:11.403  1716  1716 D SystemUpdateService: onCreate
,08-16 08:17:11.406  1716  1716 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 08:17:11.427  1716  4307 I SystemUpdateService: active receiver: enabled
,08-16 08:17:11.428   873  4294 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 06:17:11 GMT], X-Android-Received-Millis=[1471328231427], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471328231399]}
,08-16 08:17:11.429   873  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 08:17:11.430  1716  1716 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 08:17:11.430   873  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 08:17:11.430   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 08:17:11.433   873  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 08:17:11.443  1716  1716 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 08:17:11.444  1716  1716 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 08:17:11.446  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 08:17:11.455  4018  4018 D SprintDMHelper: simOperator: 
,08-16 08:17:11.455  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 08:17:11.479  1716  4310 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 08:17:11.479  1716  4310 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 08:17:11.485  1716  4310 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 08:17:11.489  1716  2406 I iu.UploadsManager: num queued entries: 0
,08-16 08:17:11.493  1716  4307 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 08:17:11.497  1716  2406 I iu.UploadsManager: num updated entries: 0
,08-16 08:17:11.510  1716  2406 I iu.SyncManager: NEXT; no task
,08-16 08:17:11.514  1716  4307 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 08:17:11.514  1716  4307 I SystemUpdateService: now status is 0 (complete)
08-16 08:17:11.514  1716  4307 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 08:17:11.516  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 08:17:11.516  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 08:17:11.516  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 08:17:11.516  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:17:11.517  3134  4306 V KeepSync: Connecting to GoogleApiClient,
,08-16 08:17:11.517  1716  4307 I SystemUpdateService: file has been verified
,08-16 08:17:11.520   873  1389 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 08:17:11.521  1716  4307 I SystemUpdateService: OTA package size = 12249756
,08-16 08:17:11.541  1716  4310 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-16 08:17:11.549  1716  4307 I SystemUpdateService: showing system update notification
,08-16 08:17:11.579  1716  1716 D SystemUpdateService: onDestroy
,08-16 08:17:11.583  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 08:17:11.583  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 08:17:11.583  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 08:17:11.584  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:17:11.595  3952  4313 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-16 08:17:11.597  1716  4317 V BaseAuthAsyncOperation: access token request failed
08-16 08:17:11.598  3134  4306 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 08:17:11.652  1511  2980 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 08:17:11.653  1511  2980 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 08:17:11.653  1511  2980 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 08:17:11.653  1511  2980 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 08:17:11.685  3134  4306 E KeepSync: IOException
08-16 08:17:11.685  3134  4306 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 08:17:11.685  3134  4306 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 08:17:11.685  3134  4306 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 08:17:11.685  3134  4306 E KeepSync: 	... 10 more
,08-16 08:17:11.685  3134  4306 W KeepSync: Sync result 2
,08-16 08:17:11.691   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129722, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 08:17:11.728  1511  4319 I GCM     : Ack for not saved message 89
,08-16 08:17:12.361   873  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 08:17:12.368  3833  3884 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-16 08:17:12.369  3833  3884 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-16 08:17:12.378  3833  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-16 08:17:12.380  3833  3884 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 08:17:12.381  3833  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-16 08:17:12.391  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 08:17:12.391  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eeb55fe added. We now have 2 listener(s)
,08-16 08:17:12.399  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 08:17:12.399  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:17:12.399  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 08:17:12.399  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.400  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edb315f added. We now have 9 listener(s)
,08-16 08:17:12.400  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.400  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:17:12.403  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:17:12.410  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:17:12.413  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:17:12.414  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 08:17:12.414  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 08:17:12.414  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3947c75 added. We now have 3 listener(s)
08-16 08:17:12.416  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:17:12.416  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:17:12.416  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:17:12.417  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 08:17:12.417  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba2d40a added. We now have 10 listener(s)
08-16 08:17:12.417  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.417  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 08:17:12.417  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:17:12.417  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:17:12.417  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.417  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.417  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:17:12.417  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:17:12.418  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eeb55fe removed from the list
08-16 08:17:12.418  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:17:12.418  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edb315f removed from the list
,08-16 08:17:12.421  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:12.422  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:17:12.423  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.423  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.423  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.424  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:17:12.424  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.424  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.425  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edb315f not in the list
08-16 08:17:12.425  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.425  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.427  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.427  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:12.427  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:17:12.427  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:17:12.428  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba2d40a removed from the list
,08-16 08:17:12.428  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.428  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.428  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.429  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 08:17:12.429  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3947c75 removed from the list
08-16 08:17:12.431  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:17:12.431  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aab847b added. We now have 2 listener(s)
,08-16 08:17:12.437  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 08:17:12.437  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 08:17:12.438  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:17:12.438  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 08:17:12.439  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f871298 added. We now have 9 listener(s)
08-16 08:17:12.439  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.440  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 08:17:12.445  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:17:12.451  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:17:12.455  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:17:12.455  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 08:17:12.455  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:17:12.455  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a226d6 added. We now have 3 listener(s)
08-16 08:17:12.457  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:17:12.457  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:17:12.458  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 08:17:12.458  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.458  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@763ed57 added. We now have 10 listener(s)
08-16 08:17:12.458  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.458  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 08:17:12.458  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:17:12.459  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 08:17:12.459  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:17:12.459  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:17:12.461  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:12.463  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 08:17:12.463  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 08:17:12.471  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 08:17:12.471  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:12.472  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 08:17:12.472  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 08:17:12.480  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 08:17:12.480  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 08:17:12.481  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 08:17:12.482  3833  3884 D BluetoothAdapter: STATE_ON
,08-16 08:17:12.489  4239  4250 D BtGatt.GattService: registerClient() - UUID=469c7d57-b2f1-483f-920d-7e664a92addf
,08-16 08:17:12.491  4239  4255 D BtGatt.GattService: onClientRegistered() - UUID=469c7d57-b2f1-483f-920d-7e664a92addf, clientIf=5
,08-16 08:17:12.492  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 08:17:12.493  4239  4277 D BtGatt.GattService: start scan with filters
,08-16 08:17:12.499  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 08:17:12.499  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 08:17:12.499  4239  4258 D BtGatt.ScanManager: handling starting scan
,08-16 08:17:12.499  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 08:17:12.500  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 08:17:12.503  4239  4258 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67359a7
,08-16 08:17:12.507  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 08:17:12.508  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 08:17:12.508  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 08:17:12.509  4239  4255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 08:17:12.509  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.510  4239  4258 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 08:17:12.514  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 08:17:12.520  4239  4255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 08:17:12.520  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.521  4239  4258 D BtGatt.ScanManager: Starting BLE batch scan
08-16 08:17:12.521  4239  4258 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 08:17:12.523  3833  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 08:17:12.524  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 08:17:12.524  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 08:17:12.524  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.524  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 08:17:12.525  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 08:17:12.525  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 08:17:12.525  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 08:17:12.526  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 08:17:12.526  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 08:17:12.527  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 08:17:12.528  3833  3884 D BluetoothAdapter: STATE_ON
,08-16 08:17:12.530  4239  4250 D BtGatt.GattService: stopScan() - queue size =1
,08-16 08:17:12.530  4239  4249 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 08:17:12.531  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 08:17:12.531  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 08:17:12.531  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 08:17:12.531  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 08:17:12.531  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 08:17:12.532  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:17:12.532  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 08:17:12.532  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 08:17:12.532  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 08:17:12.534  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 08:17:12.535  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 08:17:12.535  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:17:12.535  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 08:17:12.538  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 08:17:12.539  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:17:12.539  4239  4255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 08:17:12.539  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:17:12.539  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.539  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.539  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.540  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:17:12.540  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:17:12.540  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aab847b removed from the list
08-16 08:17:12.540  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.540  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f871298 removed from the list
08-16 08:17:12.540  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:17:12.541  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.542  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.542  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:17:12.543  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:17:12.543  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.543  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:17:12.544  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f871298 not in the list
08-16 08:17:12.544  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 08:17:12.544  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.545  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.545  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:17:12.545  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:17:12.545  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@763ed57 removed from the list
08-16 08:17:12.545  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 08:17:12.545  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.545  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.545  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:17:12.545  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a226d6 removed from the list
08-16 08:17:12.546  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 08:17:12.546  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d007f3 added. We now have 2 listener(s)
,08-16 08:17:12.548  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:17:12.548  4239  4255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 08:17:12.548  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:17:12.548  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:17:12.548  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.548  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.548  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf19cb0 added. We now have 9 listener(s)
08-16 08:17:12.549  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.549  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 08:17:12.551  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:17:12.557  4239  4255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 08:17:12.557  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:17:12.557  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:17:12.557  4239  4258 D BtGatt.ScanManager: stopping BLe Batch
,08-16 08:17:12.559  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:17:12.559  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 08:17:12.560  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 08:17:12.560  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9973aae added. We now have 3 listener(s)
,08-16 08:17:12.562  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:12.564  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 08:17:12.564  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:17:12.564  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 08:17:12.564  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:12.564  4239  4255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 08:17:12.564  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.564  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.564  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d9304f added. We now have 10 listener(s)
08-16 08:17:12.564  4239  4258 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 08:17:12.564  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 08:17:12.565  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 08:17:12.566  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-16 08:17:12.566  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:17:12.566  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 08:17:12.567  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:17:12.567  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 08:17:12.570  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 08:17:12.570  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:17:12.571  4239  4255 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 08:17:12.571  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.574  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 08:17:12.575  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 08:17:12.575  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 08:17:12.579  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 08:17:12.579  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 08:17:12.579  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-16 08:17:12.579  3833  3884 D BluetoothAdapter: STATE_ON
,08-16 08:17:12.582  4239  4277 D BtGatt.GattService: registerClient() - UUID=86028c62-736c-4558-a44b-e9c615489733
,08-16 08:17:12.582  4239  4255 D BtGatt.GattService: onClientRegistered() - UUID=86028c62-736c-4558-a44b-e9c615489733, clientIf=5
,08-16 08:17:12.582  3833  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 08:17:12.583  4239  4250 D BtGatt.GattService: start scan with filters
,08-16 08:17:12.585  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 08:17:12.585  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 08:17:12.585  4239  4258 D BtGatt.ScanManager: handling starting scan
08-16 08:17:12.585  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 08:17:12.585  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 08:17:12.588  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 08:17:12.588  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:17:12.588  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 08:17:12.590  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 08:17:12.592  4239  4255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 08:17:12.592  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.592  4239  4258 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 08:17:12.593  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:17:12.593  3833  3884 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 08:17:12.593  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 08:17:12.594  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 08:17:12.594  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:17:12.594  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 08:17:12.594  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 08:17:12.594  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 08:17:12.594  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 08:17:12.595  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d007f3 removed from the list
08-16 08:17:12.595  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.595  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf19cb0 removed from the list
,08-16 08:17:12.595  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 08:17:12.595  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 08:17:12.595  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.595  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 08:17:12.596  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.596  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 08:17:12.596  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 08:17:12.597  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.597  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.597  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf19cb0 not in the list
,08-16 08:17:12.597  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 08:17:12.597  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 08:17:12.597  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 08:17:12.597  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 08:17:12.597  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 08:17:12.597  4239  4255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 08:17:12.598  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.598  4239  4258 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 08:17:12.598  4239  4258 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 08:17:12.598  3833  3884 D BluetoothAdapter: STATE_ON
,08-16 08:17:12.599  4239  4268 D BtGatt.GattService: stopScan() - queue size =1
08-16 08:17:12.599  4239  4249 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 08:17:12.599  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 08:17:12.600  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 08:17:12.600  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 08:17:12.600  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 08:17:12.600  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 08:17:12.601  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:17:12.601  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 08:17:12.601  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 08:17:12.601  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:17:12.601  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.602  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:17:12.603  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 08:17:12.603  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:17:12.603  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.603  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:17:12.603  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.603  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d9304f removed from the list
08-16 08:17:12.603  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.603  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.603  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.603  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:17:12.604  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9973aae removed from the list
,08-16 08:17:12.604  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:17:12.604  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2826b added. We now have 2 listener(s)
08-16 08:17:12.606  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:17:12.607  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 08:17:12.607  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 08:17:12.607  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.607  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b051c8 added. We now have 9 listener(s)
08-16 08:17:12.608  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.608  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 08:17:12.610  4239  4255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 08:17:12.611  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.610  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:17:12.615  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:17:12.616  4239  4255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 08:17:12.616  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.617  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:12.617  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 08:17:12.618  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 08:17:12.619  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@feff186 added. We now have 3 listener(s),
,08-16 08:17:12.620  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 08:17:12.621  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:17:12.621  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 08:17:12.621  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:17:12.622  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:12.622  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.622  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@864da47 added. We now have 10 listener(s),
08-16 08:17:12.622  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.622  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 08:17:12.622  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 08:17:12.623  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
,08-16 08:17:12.623  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 08:17:12.623  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 08:17:12.623  4239  4255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 08:17:12.624  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.624  4239  4258 D BtGatt.ScanManager: stopping BLe Batch,
08-16 08:17:12.627  3833  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 08:17:12.627  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 08:17:12.630  4239  4255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 08:17:12.631  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.631  4239  4258 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 08:17:12.631  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 08:17:12.632  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 08:17:12.632  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 08:17:12.635  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-16 08:17:12.635  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 08:17:12.636  3833  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 08:17:12.636  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:17:12.637  4239  4255 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 08:17:12.637  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.639  4239  4249 D BtGatt.GattService: registerClient() - UUID=ae3d5c69-1636-43b5-a1c1-6f3704fd0fe5
08-16 08:17:12.639  4239  4255 D BtGatt.GattService: onClientRegistered() - UUID=ae3d5c69-1636-43b5-a1c1-6f3704fd0fe5, clientIf=5
08-16 08:17:12.639  3833  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 08:17:12.639  4239  4268 D BtGatt.GattService: start scan with filters
,08-16 08:17:12.642  4239  4258 D BtGatt.ScanManager: handling starting scan
,08-16 08:17:12.642  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 08:17:12.643  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 08:17:12.643  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 08:17:12.643  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 08:17:12.646  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 08:17:12.646  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 08:17:12.646  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 08:17:12.648  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 08:17:12.649  4239  4255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 08:17:12.649  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.649  4239  4258 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 08:17:12.653  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 08:17:12.654  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 08:17:12.654  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 08:17:12.655  4239  4255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 08:17:12.655  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.655  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.655  4239  4258 D BtGatt.ScanManager: Starting BLE batch scan
08-16 08:17:12.655  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 08:17:12.655  4239  4258 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 08:17:12.655  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 08:17:12.655  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 08:17:12.655  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2826b removed from the list
08-16 08:17:12.655  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:17:12.655  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b051c8 removed from the list
08-16 08:17:12.656  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 08:17:12.656  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:17:12.656  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.656  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 08:17:12.656  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 08:17:12.656  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 08:17:12.657  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:17:12.658  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 08:17:12.658  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:17:12.658  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b051c8 not in the list
08-16 08:17:12.658  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 08:17:12.658  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 08:17:12.658  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 08:17:12.659  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 08:17:12.659  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 08:17:12.660  3833  3884 D BluetoothAdapter: STATE_ON
08-16 08:17:12.661  4239  4278 D BtGatt.GattService: stopScan() - queue size =1
08-16 08:17:12.662  4239  4249 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 08:17:12.663  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 08:17:12.663  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 08:17:12.663  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 08:17:12.663  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 08:17:12.664  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 08:17:12.665  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:17:12.666  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 08:17:12.666  3833  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 08:17:12.666  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 08:17:12.666  4239  4255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 08:17:12.666  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 08:17:12.666  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:17:12.667  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 08:17:12.667  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 08:17:12.667  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.668  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:17:12.668  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@864da47 removed from the list
,08-16 08:17:12.668  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.668  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.668  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:17:12.668  3833  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 08:17:12.668  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:17:12.668  3833  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 08:17:12.668  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@feff186 removed from the list
,08-16 08:17:12.669  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:17:12.669  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0ad3e3 added. We now have 2 listener(s)
08-16 08:17:12.671  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:17:12.671  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 08:17:12.671  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:17:12.671  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.672  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebd91e0 added. We now have 9 listener(s)
,08-16 08:17:12.672  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.672  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 08:17:12.672  4239  4255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 08:17:12.672  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.675  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 08:17:12.679  3833  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 08:17:12.680  4239  4255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 08:17:12.680  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.680  4239  4258 D BtGatt.ScanManager: stopping BLe Batch
,08-16 08:17:12.683  3833  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 08:17:12.684  3833  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 08:17:12.684  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 08:17:12.684  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91dab5e added. We now have 3 listener(s)
,08-16 08:17:12.686  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 08:17:12.686  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 08:17:12.686  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 08:17:12.687  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 08:17:12.687  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48ccb3f added. We now have 10 listener(s)
,08-16 08:17:12.687  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:12.687  3833  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 08:17:12.687  4239  4255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 08:17:12.687  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.687  3833  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 08:17:12.687  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 08:17:12.687  4239  4258 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 08:17:12.687  3833  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 08:17:12.687  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.687  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.687  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 08:17:12.687  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:17:12.687  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0ad3e3 removed from the list
08-16 08:17:12.688  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 08:17:12.688  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebd91e0 removed from the list
,08-16 08:17:12.690  3833  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 08:17:12.690  3833  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 08:17:12.690  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.691  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.691  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 08:17:12.692  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 08:17:12.692  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.692  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.692  3833  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebd91e0 not in the list
08-16 08:17:12.692  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 08:17:12.692  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.693  4239  4255 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 08:17:12.693  4239  4255 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 08:17:12.693  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 08:17:12.693  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 08:17:12.693  3833  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 08:17:12.694  3833  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48ccb3f removed from the list
08-16 08:17:12.694  3833  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 08:17:12.694  3833  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 08:17:12.694  3833  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 08:17:12.694  3833  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 08:17:12.694  3833  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91dab5e removed from the list
,08-16 08:17:12.695  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 08:17:12.695  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 08:17:12.695  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 08:17:12.695  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 08:17:12.695  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 08:17:12.695  3833  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 08:17:12.701  3833  4321 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,08-16 08:17:12.701  3833  4321 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
08-16 08:17:12.701  3833  4321 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 08:17:12.703  3833  4322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,08-16 08:17:12.703  3833  4322 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-16 08:17:12.703  3833  4322 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 08:17:12.705  3833  3884 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-16 08:17:12.705  3833  3884 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 08:17:12.705  3833  3884 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 08:17:12.705  3833  3884 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-16 08:17:12.705  3833  3884 D com.test.thalitest.ThaliTestRunner: Total duration: 22786 ms
,08-16 08:17:12.707  3833  3884 I jxcore-log: Total number of executed tests:  80
08-16 08:17:12.707  3833  3884 I jxcore-log: 
,08-16 08:17:12.707  3833  3884 I jxcore-log: Number of passed tests:  80
08-16 08:17:12.707  3833  3884 I jxcore-log: 
08-16 08:17:12.707  3833  3884 I jxcore-log: Number of failed tests:  0
08-16 08:17:12.707  3833  3884 I jxcore-log: 
,08-16 08:17:12.708  3833  3884 I jxcore-log: Number of ignored tests:  0
08-16 08:17:12.708  3833  3884 I jxcore-log: 
08-16 08:17:12.708  3833  3884 I jxcore-log: Total duration:  22786
08-16 08:17:12.708  3833  3884 I jxcore-log: 
08-16 08:17:12.709  3833  3884 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 08:17:12.709  3833  3884 I jxcore-log: 
,08-16 08:17:12.712  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.712  3833  3884 I jxcore-log: 
08-16 08:17:12.716  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.716  3833  3884 I jxcore-log: 
08-16 08:17:12.717  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.717  3833  3884 I jxcore-log: 
,08-16 08:17:12.718  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.718  3833  3884 I jxcore-log: 
,08-16 08:17:12.719  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.719  3833  3884 I jxcore-log: 
08-16 08:17:12.720  3833  3833 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 08:17:12.721  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.721  3833  3884 I jxcore-log: 
,08-16 08:17:12.724  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.724  3833  3884 I jxcore-log: 
,08-16 08:17:12.726  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:17:12.726  3833  3884 I jxcore-log: 
,08-16 08:17:12.726  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:17:12.726  3833  3884 I jxcore-log: 
,08-16 08:17:12.727  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.727  3833  3884 I jxcore-log: 
,08-16 08:17:12.728  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.728  3833  3884 I jxcore-log: 
,08-16 08:17:12.729  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 08:17:12.729  3833  3884 I jxcore-log: 
,08-16 08:17:12.730  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:17:12.730  3833  3884 I jxcore-log: 
,08-16 08:17:12.731  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 08:17:12.731  3833  3884 I jxcore-log: 
,08-16 08:17:12.732  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.732  3833  3884 I jxcore-log: 
,08-16 08:17:12.733  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.733  3833  3884 I jxcore-log: 
,08-16 08:17:12.734  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.734  3833  3884 I jxcore-log: 
,08-16 08:17:12.734  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.734  3833  3884 I jxcore-log: 
,08-16 08:17:12.735  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.735  3833  3884 I jxcore-log: 
,08-16 08:17:12.736  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.736  3833  3884 I jxcore-log: 
,08-16 08:17:12.737  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.737  3833  3884 I jxcore-log: 
,08-16 08:17:12.738  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.738  3833  3884 I jxcore-log: 
,08-16 08:17:12.739  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.739  3833  3884 I jxcore-log: 
,08-16 08:17:12.740  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 08:17:12.740  3833  3884 I jxcore-log: 
,08-16 08:17:12.741  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 08:17:12.741  3833  3884 I jxcore-log: 
,08-16 08:17:12.741  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.741  3833  3884 I jxcore-log: 
,08-16 08:17:12.742  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.742  3833  3884 I jxcore-log: 
08-16 08:17:12.742  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.742  3833  3884 I jxcore-log: 
,08-16 08:17:12.743  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.743  3833  3884 I jxcore-log: 
,08-16 08:17:12.743  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.743  3833  3884 I jxcore-log: 
,08-16 08:17:12.744  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.744  3833  3884 I jxcore-log: 
08-16 08:17:12.744  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 08:17:12.744  3833  3884 I jxcore-log: 
,08-16 08:17:13.036  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 08:17:13.039  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 08:17:13.039  3833  3884 I jxcore-log: 
,08-16 08:17:13.103  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 08:17:13.107  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 08:17:13.107  3833  3884 I jxcore-log: 
,08-16 08:17:13.168  3833  3833 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 08:17:13.171  3833  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 08:17:13.171  3833  3884 I jxcore-log: 
,08-16 08:17:13.433  4323  4323 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 08:17:13.438  4323  4323 D AndroidRuntime: CheckJNI is OFF
,08-16 08:17:13.481  4323  4323 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 08:17:13.529  4323  4323 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 08:17:13.551  4323  4323 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 08:17:13.563   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 08:17:13.564   873   886 I ActivityManager: Killing 3833:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 08:17:13.673   873   896 W PackageSettings: Skipping PackageSetting{1bed8f8 com.example.hello/10273} due to missing metadata
,08-16 08:17:13.698   873  2961 D GraphicsStats: Buffer count: 2
,08-16 08:17:13.699   873  1988 I WindowState: WIN DEATH: Window{4a77584 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 08:17:13.699   873  1306 D WifiService: Client connection lost with reason: 4
,08-16 08:17:13.707   873   896 I art     : Starting a blocking GC Explicit
,08-16 08:17:13.738   873   886 W ActivityManager: Force removing ActivityRecord{652d3d5 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-16 08:17:13.746   873  2961 W ActivityManager: Spurious death for ProcessRecord{123359a 0:com.test.thalitest/u0a0}, curProc for 3833: null
,08-16 08:17:13.764   873   896 I art     : Explicit concurrent mark sweep GC freed 24832(1560KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 996us total 56.086ms
,08-16 08:17:13.776   873  1940 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3833 uid 10000
,08-16 08:17:13.778  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-16 08:17:13.787   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 08:17:13.791  4323  4323 I art     : System.exit called, status: 0
08-16 08:17:13.791  4323  4323 I AndroidRuntime: VM exiting with result code 0.
,08-16 08:17:13.798   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 08:17:13.808  1995  1995 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-16 08:17:13.820  1855  1855 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 08:17:13.820  4239  4239 D BluetoothMapAppObserver: onReceive
08-16 08:17:13.820  4239  4239 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 08:17:13.826  3700  3700 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 08:17:13.827  2080  2234 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 08:17:13.851  1855  4336 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 08:17:13.851   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 08:17:13.857  1855  4336 I Decoder : createOrResetDecoder
,08-16 08:17:13.858  1995  4340 I MicroRecognitionRnrImpl: Starting detection.
,08-16 08:17:13.859  1995  4341 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@7697f11
,08-16 08:17:13.861   377  4343 I AudioFlinger: AudioFlinger's thread 0xb1cc0000 ready to run,
,08-16 08:17:13.869   377  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-16 08:17:13.870  1995  4341 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@7697f11
,08-16 08:17:13.879   873   884 I ActivityManager: Start proc 4345:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 08:17:13.880   377  4343 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-16 08:17:13.880   377  4343 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-16 08:17:13.880   377  4343 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-16 08:17:13.888  1911  1911 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-16 08:17:13.891   377  4343 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-16 08:17:13.928  1511  4337 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 08:17:13.928  1511  4337 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-16 08:17:13.930  1511  4337 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 08:17:13.930  1511  4337 E ClearcutLoggerIntentService: 	a,t java.lang.Thread.run(Thread.java:818)
,08-16 08:17:13.947  1511  1511 I ConfigService: onCreate
,08-16 08:17:13.951  4345  4345 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 08:17:13.965   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 08:17:13.971  1855  4336 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 08:17:13.973  1995  1995 I HotwordWorkerImpl: onReady
,08-16 08:17:13.986  1927  2012 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 08:17:13.987   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 08:17:13.987   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 08:17:13.987   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 08:17:13.987   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 08:17:13.987   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 08:17:13.987   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 08:17:13.987   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 08:17:13.987   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:17:13.987   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:13.987   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 08:17:13.991   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 08:17:13.991   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 08:17:13.991   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 08:17:13.991   873   886 E DropBoxManagerService: 	... 13 more
,08-16 08:17:13.999   873  2961 I ActivityManager: Start proc 4360:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-16 08:17:13.999  1927  2012 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 08:17:13.999  1927  2012 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1927
08-16 08:17:13.999  1927  2012 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:13.999  1927  2012 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 08:17:14.001   873  2959 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 08:17:14.005  1995  2009 W SearchService: Abort, client detached.
,08-16 08:17:14.006   873  4367 E DropBoxManagerService: Can't write: system_app_crash
08-16 08:17:14.006   873  4367 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 08:17:14.006   873  4367 E DropBoxManagerService: 	... 5 more
,08-16 08:17:14.007  1995  1995 I HotwordDetector: Closing mic,
08-16 08:17:14.007  1995  2312 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7697f11
08-16 08:17:14.007  1995  4341 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-16 08:17:14.016   873  4373 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-16 08:17:14.017  1855  4336 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 08:17:14.022  1855  4336 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 08:17:14.022  1855  4336 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 08:17:14.023  1855  4336 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 08:17:14.023  1855  4336 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 08:17:14.024  1855  4336 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 08:17:14.024  1855  4336 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-16 08:17:14.028  1855  4336 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-16 08:17:14.028  1855  4336 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 08:17:14.028  1855  4336 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-16 08:17:14.028  1855  4336 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-16 08:17:14.028  1855  4336 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 08:17:14.029  1855  4336 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon,
08-16 08:17:14.029  1995  4374 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-16 08:17:14.051  4345  4345 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 08:17:14.055   377  4343 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-16 08:17:14.056   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 08:17:14.057   377  4343 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-16 08:17:14.061   377  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-16 08:17:14.062  1995  2315 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-16 08:17:14.062  1995  4340 I MicroRecognitionRnrImpl: Detection finished
,08-16 08:17:14.065   873  4373 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 08:17:14.065   873  4373 I Adreno  : Build Date                       : 10/20/15
08-16 08:17:14.065   873  4373 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 08:17:14.065   873  4373 I Adreno  : Local Branch                     : M14
08-16 08:17:14.065   873  4373 I Adreno  : Remote Branch                    : 
08-16 08:17:14.065   873  4373 I Adreno  : Remote Branch                    : 
08-16 08:17:14.065   873  4373 I Adreno  : Reconstruct Branch               : 
,08-16 08:17:14.070   873  4373 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 08:17:14.083  4345  4380 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 08:17:14.090   873  1386 I ActivityManager: Start proc 4383:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 08:17:14.111   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,08-16 08:17:14.123  4383  4383 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 08:17:14.143  1716  4397 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 08:17:14.143  1716  4397 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 08:17:14.151  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-16 08:17:14.151  1511  1511 D AndroidRuntime: Shutting down VM
,08-16 08:17:14.152  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-16 08:17:14.152  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-16 08:17:14.152  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 08:17:14.152  1511  1511 E AndroidRuntime: 	... 8 more
,08-16 08:17:14.155   873  4400 E DropBoxManagerService: Can't write: system_app_crash
08-16 08:17:14.155   873  4400 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 08:17:14.155   873  4400 E DropBoxManagerService: 	... 5 more
,08-16 08:17:14.160  4345  4377 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:14.160  4345  4377 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:14.165  4345  4377 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 08:17:14.186  4345  4377 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 08:17:14.192  4345  4380 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:14.192  4345  4380 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 08:17:14.193  4345  4380 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 08:17:14.193  4345  4380 E AndroidRuntime: Process: android.process.acore, PID: 4345
08-16 08:17:14.193  4345  4380 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 08:17:14.193  4345  4380 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 08:17:14.195  4345  4377 I Process : Sending signal. PID: 4345 SIG: 9
,08-16 08:17:14.203   873  4402 E DropBoxManagerService: Can't write: system_app_crash
08-16 08:17:14.203   873  4402 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 08:17:14.203   873  4402 E DropBoxManagerService: 	... 5 more
,08-16 08:17:14.234   873  1940 I ActivityManager: Process android.process.acore (pid 4345) has died
,08-16 08:17:14.235   873  1940 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-16 08:17:14.270   873   891 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,08-16 08:17:14.314   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-16 08:17:14.314   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-16 08:17:14.314   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-16 08:17:14.314   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-16 08:17:14.314   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-16 08:17:14.314   281   281 E qdoverlay: MdpCtrl close error in unset

```
