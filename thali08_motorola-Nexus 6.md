#### Test 639107046ed3de5_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
03-24 16:45:39.856  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:45:40.139  3260  3260 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 16:45:40.144  3260  3260 D AndroidRuntime: CheckJNI is OFF
03-24 16:45:40.268  3260  3260 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 16:45:40.274   822  1320 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 16:45:40.289   822  1320 V WindowManager: addAppToken: AppWindowToken{2a7b727 token=Token{1af2b5e6 ActivityRecord{32698c41 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-24 16:45:40.296  1517  1517 I HotwordDetector: Closing mic
03-24 16:45:40.297  1517  1767 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1598496d
03-24 16:45:40.303  3260  3260 D AndroidRuntime: Shutting down VM
03-24 16:45:40.313   822   861 V WindowManager: Adding window Window{34689bbe u0 Starting com.test.thalitest} at 2 of 7 (after Window{239425c5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 16:45:40.340   822  2545 I ActivityManager: Start proc 3274:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-24 16:45:40.356   359  1773 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 16:45:40.358   359  1773 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 16:45:40.375   359  1018 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-24 16:45:40.379  1517  1769 I HotwordRecognitionRnr: Stopping hotword detection.
03-24 16:45:40.379  1517  1770 I HotwordRecognitionRnr: Hotword detection finished
03-24 16:45:40.461   822  1320 I art     : Explicit concurrent mark sweep GC freed 49528(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.545ms total 74.766ms
,03-24 16:45:40.540   822   840 I ActivityManager: Killing 2901:com.android.settings/1000 (adj 15): empty #17
,03-24 16:45:40.587   822  1254 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1703023891
03-24 16:45:40.587   822  1254 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 16:45:40.645   822   840 I ActivityManager: Killing 2866:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-24 16:45:40.673   878   878 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
03-24 16:45:40.673   878   878 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 16:45:40.714   878   878 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,03-24 16:45:40.715   878   878 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,03-24 16:45:40.858  3274  3274 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 16:45:40.874  3274  3274 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6410-6412)
03-24 16:45:40.874  3274  3274 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 16:45:40.902  3274  3274 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {390c4b3c}
03-24 16:45:40.903  3274  3274 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 16:45:40.903  3274  3274 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-24 16:45:40.919  3274  3274 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 16:45:40.920  3274  3274 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 16:45:40.921  3274  3274 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 16:45:40.929  3274  3299 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-24 16:45:40.937  3274  3274 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-24 16:45:40.944  3274  3274 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 16:45:40.944  3274  3274 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 16:45:40.944  3274  3274 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 16:45:41.035   822   860 D BluetoothManagerService: Message: 20
03-24 16:45:41.036   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a82930f:true
,03-24 16:45:41.071  3274  3274 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 16:45:41.081  3274  3274 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-24 16:45:41.094  3274  3274 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-24 16:45:41.100  3274  3274 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 16:45:41.100  3274  3274 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 16:45:41.172  3274  3321 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 16:45:41.175  3274  3274 D Atlas   : Validating map...
03-24 16:45:41.181   822  1326 V WindowManager: Adding window Window{2b45dff u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{34689bbe u0 Starting com.test.thalitest})
03-24 16:45:41.183  3274  3308 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-24 16:45:41.231  3274  3321 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 16:45:41.238  3274  3321 D OpenGLRenderer: Enabling debug mode 0
,03-24 16:45:41.306   822   861 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s2ms
,03-24 16:45:41.313  1236  1236 I Keyboard.Facilitator: onFinishInput()
,03-24 16:45:41.334  3274  3274 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3274
,03-24 16:45:41.453  3274  3274 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 16:45:41.558  3274  3322 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580586880
,03-24 16:45:41.562  3274  3322 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 16:45:41.562  3274  3322 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 16:45:41.562  3274  3322 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 16:45:41.562  3274  3322 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 16:45:41.562  3274  3322 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 16:45:41.562  3274  3322 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a221746 added. We now have 1 listener(s)
,03-24 16:45:41.563   822  1326 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:45:41.566  3274  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
03-24 16:45:41.567  3274  3322 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:45:41.568  3274  3322 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 16:45:41.568  3274  3322 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 16:45:41.572  3274  3322 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@764045d added. We now have 1 listener(s)
03-24 16:45:41.572  3274  3322 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-24 16:45:41.576   822  1025 D WifiService: New client listening to asynchronous messages
,03-24 16:45:41.578  3274  3322 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-24 16:45:41.580  3274  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-24 16:45:41.580  3274  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-24 16:45:41.580  3274  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-24 16:45:41.580  3274  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-24 16:45:41.583  3274  3322 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:45:41.583   822  2545 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:45:41.584  3274  3322 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 16:45:41.587  3274  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
03-24 16:45:41.587  3274  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-24 16:45:41.587  3274  3322 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-24 16:45:41.588  3274  3274 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 16:45:41.589  3274  3322 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-24 16:45:41.612  3274  3274 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 16:45:41.707   878   878 I kickstart: STATUS: Received file 'm9kefs2'
03-24 16:45:41.707   878   878 I kickstart: STATUS: 950272 bytes transferred in 0.992332 seconds
03-24 16:45:41.707   878   878 I kickstart: STATUS: Successfully downloaded files from target 
03-24 16:45:41.707   878   878 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 16:45:41.711   878   878 I kickstart: STATUS: Sahara protocol completed
,03-24 16:45:42.210  3274  3331 W jxcore-log: Initializing JXcore engine
03-24 16:45:42.210  3274  3331 W jxcore-log: JXcore engine is ready
,03-24 16:45:42.233  3331  3331 W Thread-351: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10987]" dev="sockfs" ino=10987 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-24 16:45:42.233  3331  3331 W Thread-351: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-24 16:45:42.233  3331  3331 W Thread-351: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11786]" dev="sockfs" ino=11786 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-24 16:45:42.233  3331  3331 W Thread-351: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20060]" dev="sockfs" ino=20060 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-24 16:45:42.256  3274  3331 W jxcore-log: Starting JXcore engine
,03-24 16:45:42.332  3274  3331 W jxcore-log: Platform android,
03-24 16:45:42.332  3274  3331 W jxcore-log: 
,03-24 16:45:42.333  3274  3331 W jxcore-log: Process ARCH arm
03-24 16:45:42.333  3274  3331 W jxcore-log: ,
,03-24 16:45:42.528  3274  3331 I jxcore-log: JXcore Cordova bridge is ready!
03-24 16:45:42.528  3274  3331 I jxcore-log: 
03-24 16:45:42.528  3274  3331 W jxcore-log: JXcore engine is started
,03-24 16:45:42.541  3274  3322 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 16:45:42.544  3274  3274 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 16:45:45.434  1349  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:45.463  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 16:45:45.463  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:45.463  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:45.463  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:45.466  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:45.476  2739  2739 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,03-24 16:45:45.476  2739  2739 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 16:45:45.476  2739  2739 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,03-24 16:45:47.436   822   863 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-24 16:45:47.455   822   863 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d,
,03-24 16:45:47.479   260   284 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (155 us)
,03-24 16:45:48.060   822   861 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-24 16:45:48.060   260   260 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-24 16:45:48.060   822   822 V ActivityManager: Display changed displayId=0
03-24 16:45:48.061   260   260 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,03-24 16:45:48.342   260   321 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0,
,03-24 16:45:48.347   260   260 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-24 16:45:48.348   822  1045 D SurfaceControl: Excessive delay in setPowerMode(): 287ms
,03-24 16:45:48.360   359  1019 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-24 16:45:48.360   359  1019 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
03-24 16:45:48.361   822   863 I DreamManagerService: Entering dreamland.
,03-24 16:45:48.363   822   858 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
03-24 16:45:48.363   822   863 I PowerManagerService: Dozing...
,03-24 16:45:48.370   822  1024 E WifiStateMachine: cancelDelayedScan -> 16
03-24 16:45:48.373   822  1024 E native  : do suspend false
,03-24 16:45:48.423  1236  1236 I Keyboard.Facilitator: onFinishInput()
,03-24 16:45:48.428   822  1024 E WifiStateMachine: cancelDelayedScan -> 18
,03-24 16:45:48.484   822  1024 E native  : do suspend true
,03-24 16:45:48.560   359   359 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-24 16:45:48.561   359   359 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-24 16:45:48.577   822  1024 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-24 16:45:48.857   822  1024 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-24 16:45:50.928  1137  1137 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-24 16:45:51.362  1137  1137 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-24 16:45:51.399  1137  1137 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-24 16:45:51.400  1137  1137 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-24 16:45:51.426   822  1024 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-24 16:45:51.426   822  1024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-24 16:45:51.427   822  1026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-24 16:45:51.433   822  1024 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,03-24 16:45:51.441   355   813 D CommandListener: Setting iface cfg
,03-24 16:45:51.448   822  1024 E WifiStateMachine: Start Dhcp Watchdog 1,
,03-24 16:45:51.451   822  1024 E WifiStateMachine:  WifiLinkLayerStats: 
03-24 16:45:51.451   822  1024 E WifiStateMachine:  my bss beacon rx: 1
03-24 16:45:51.451   822  1024 E WifiStateMachine:  RSSI mgmt: -41
03-24 16:45:51.451   822  1024 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=1
03-24 16:45:51.451   822  1024 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-24 16:45:51.451   822  1024 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-24 16:45:51.451   822  1024 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-24 16:45:51.451   822  1024 E WifiStateMachine:  on_time : 0 tx_time=60 rx_time=104 scan_time=0,
,03-24 16:45:51.545   822  1024 E native  : do suspend false,
,03-24 16:45:51.560   822  1024 E WifiStateMachine: scanCount==0 - aborting
,03-24 16:45:51.799  3343  3343 I dhcpcd  : version 5.5.6 starting
,03-24 16:45:51.889  3343  3343 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-24 16:45:51.984  3343  3343 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,03-24 16:45:52.019  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:45:52.019  3274  3331 I jxcore-log: 
,03-24 16:45:52.022  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:45:52.022  3274  3331 I jxcore-log: 
,03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-24 16:45:52.028  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-24 16:45:52.033  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,03-24 16:45:52.035  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:45:52.035  3274  3331 I jxcore-log: 
,03-24 16:45:52.037  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 16:45:52.037  3274  3331 I jxcore-log: 
,03-24 16:45:52.132  3343  3343 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds
,03-24 16:45:52.378   822  1024 E native  : do suspend true
,03-24 16:45:52.424   822  1026 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-24 16:45:52.424   822  1024 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-24 16:45:52.429   822  1026 D ConnectivityService: Adding iface wlan0 to network 100
,03-24 16:45:52.446   822  1026 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-24 16:45:52.446   822  1026 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-24 16:45:52.448   822  1026 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-24 16:45:52.449   822  1026 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-24 16:45:52.450   822  1026 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-24 16:45:52.457   822  1026 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-24 16:45:52.460   822  1026 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,03-24 16:45:52.460   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-24 16:45:52.460   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-24 16:45:52.461   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-24 16:45:52.461   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-24 16:45:52.461   822  1026 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 16:45:52.461   822  1026 D ConnectivityService:    accepting network in place of null
,03-24 16:45:52.463   822  1026 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} },
,03-24 16:45:52.464   822  1026 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-24 16:45:52.467   822  1026 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-24 16:45:52.468   822  1026 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-24 16:45:52.468  1068  1571 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 16:45:52.469   822  1026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-24 16:45:52.470   822  1026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-24 16:45:52.472   822   860 D Tethering: MasterInitialState.processMessage what=3
,03-24 16:45:52.478  2925  2925 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:45:52.479  3274  3274 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:45:52.481  3274  3274 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:45:52.482   822  1326 V BackupManagerService: Scheduling immediate backup pass
,03-24 16:45:52.485   822   822 V BackupManagerService: Running a backup pass
03-24 16:45:52.485  2925  2925 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-24 16:45:52.485   822  1044 V BackupManagerService: clearing pending backups
03-24 16:45:52.487  1517  1517 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-24 16:45:52.496   822  1044 V PerformBackupTask: Beginning backup of 14 targets
,03-24 16:45:52.499   822  1044 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-24 16:45:52.503   822  1044 V BackupServiceBinder: doBackup() invoked
,03-24 16:45:52.505   822  1044 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-24 16:45:52.514   822  1320 I ActivityManager: Start proc 3385:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-24 16:45:52.522   822  1044 I BackupRestoreController: Getting widget state for user: 0
03-24 16:45:52.524   371   371 I art     : Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.582ms total 10.003ms
,03-24 16:45:52.533   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 8.550ms
,03-24 16:45:52.545   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 10.728ms
,03-24 16:45:52.550  1284  1302 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-24 16:45:52.550  1284  1302 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,03-24 16:45:52.550   822   855 D TelephonyManager: getDataEnabled: retVal=false
,03-24 16:45:52.561   822   855 E GpsLocationProvider: No APN found to select.
,03-24 16:45:52.575  1834  1893 W GmsBackupTransport: Unknown package in backup request: @pm@
03-24 16:45:52.575  1834  1893 V GmsBackupTransport: starting performBackup for @pm@
03-24 16:45:52.579  1834  1893 V GmsBackupTransport: performBackup done for @pm@
,03-24 16:45:52.581   822  1260 D AlarmManagerService: Setting time of day to sec=1458834352
03-24 16:45:52.530   822  1260 W AlarmManagerService: Unable to set rtc to 1458834352: Invalid argument
,03-24 16:45:52.537  1349  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:52.566  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-24 16:45:52.566  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:52.566  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:52.566  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:52.566   822  3408 D GpsLocationProvider: NTP server returned: 1458834352574 (Thu Mar 24 16:45:52 GMT+01:00 2016) reference: 168155 certainty: 23 system time offset: 8
,03-24 16:45:52.569  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:52.597   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Mar 2016 15:45:52 GMT], X-Android-Received-Millis=[1458834352597], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458834352540]}
,03-24 16:45:52.598   822  3341 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-24 16:45:52.598   822  1026 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-24 16:45:52.598   822  1026 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-24 16:45:52.598   822  1026 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-24 16:45:52.598   822  1026 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-24 16:45:52.598   822  1026 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-24 16:45:52.599  1068  1571 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-24 16:45:52.599   822  1026 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-24 16:45:52.607  1349  1370 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 16:45:52.607  1349  1370 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 16:45:52.607  1349  1370 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 16:45:52.607  1349  1370 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 16:45:52.607  1349  1370 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 16:45:52.607  1349  1370 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 16:45:52.607  1349  1370 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 16:45:52.625  1834  1892 W GmsBackupTransport: Error sending final backup to server: 
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 16:45:52.625  1834  1892 W GmsBackupTransport: 	... 1 more
,03-24 16:45:52.626   822  1044 D BackupManagerService: Now staging backup of com.google.android.talk
,03-24 16:45:52.634   822  1044 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-24 16:45:52.636  1775  3407 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-24 16:45:52.640   822  1044 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-24 16:45:52.656   822  1044 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-24 16:45:52.658   822  1044 D BackupManagerService: Now staging backup of com.google.android.gm
,03-24 16:45:52.661   822  1044 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-24 16:45:52.663   822  1044 D BackupManagerService: Now staging backup of com.android.nfc
,03-24 16:45:52.666   822  1320 I ActivityManager: Start proc 3422:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-24 16:45:52.669   822  1044 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-24 16:45:52.671   822  1044 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-24 16:45:52.673   822  1044 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-24 16:45:52.678  3274  3331 I jxcore-log: Unit Test app is loaded
03-24 16:45:52.678  3274  3331 I jxcore-log: 
03-24 16:45:52.679   822  1044 D BackupManagerService: Now staging backup of com.google.android.calendar
,03-24 16:45:52.682   822  1044 D BackupManagerService: Now staging backup of com.android.vending
,03-24 16:45:52.686  3274  3274 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 16:45:52.687   822  1044 D BackupManagerService: Now staging backup of android
,03-24 16:45:52.688  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
03-24 16:45:52.688  3274  3331 I jxcore-log: 
,03-24 16:45:52.691  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:45:52.691  3274  3331 I jxcore-log: 
03-24 16:45:52.692   822  1044 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-24 16:45:52.697  3274  3331 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-24 16:45:52.698  3274  3331 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
03-24 16:45:52.698  3274  3331 I jxcore-log: 
03-24 16:45:52.700  3274  3331 I jxcore-log: My device name is: motorola-Nexus 6
03-24 16:45:52.700  3274  3331 I jxcore-log: 
,03-24 16:45:52.715  1349  1723 I art     : Explicit concurrent mark sweep GC freed 24339(1329KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 842us total 22.783ms
03-24 16:45:52.716  1834  1893 I GmsBackupTransport: Next backup will happen in 43199905 millis.
03-24 16:45:52.718   822  1044 I BackupManagerService: Backup pass finished.
,03-24 16:45:52.727  3422  3422 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-24 16:45:52.731  1775  3440 W DriveInitializer: Background init thread started
,03-24 16:45:52.737  3422  3422 D SprintDMHelper: simOperator:  IMSI: null
03-24 16:45:52.737  3422  3422 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-24 16:45:52.741  1775  1775 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-24 16:45:52.746  1775  1775 D SystemUpdateService: onCreate
,03-24 16:45:52.751  1775  1775 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-24 16:45:52.763  1775  3441 I SystemUpdateService: active receiver: enabled
,03-24 16:45:52.779  1775  3441 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-24 16:45:52.788  1775  3441 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
03-24 16:45:52.788  1775  3441 I SystemUpdateService: now status is 0 (complete)
03-24 16:45:52.788  1775  3441 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-24 16:45:52.788  1775  3441 I SystemUpdateService: file has been verified
,03-24 16:45:52.789  1775  3441 I SystemUpdateService: OTA package size = 25802302
,03-24 16:45:52.791  1775  3445 W DriveInitializer: Awaiting to be initialized
,03-24 16:45:52.797  1775  3441 I SystemUpdateService: showing system update notification
,03-24 16:45:52.817  1775  3452 I iu.SyncManager: SYNC; picasa accounts
,03-24 16:45:52.834   822   822 I ValidateNoPeople: skipping global notification
,03-24 16:45:52.840  1775  1775 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-24 16:45:52.844  1775  1775 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-24 16:45:52.861  1775  3452 I iu.UploadsManager: num queued entries: 0
,03-24 16:45:52.871  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 16:45:52.871  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:52.871  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:52.871  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:52.872  1775  1775 D SystemUpdateService: onDestroy
,03-24 16:45:52.873  1775  3452 I iu.UploadsManager: num updated entries: 0
,03-24 16:45:52.875  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:52.879  1775  3452 I iu.SyncManager: NEXT; no task
,03-24 16:45:52.886  3093  3421 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 16:45:52.886  3093  3421 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at blb.a(PG:3937)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at czp.a(PG:18188)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at czp.a(PG:9081)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:45:52.886  3093  3421 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	... 12 more
03-24 16:45:52.886  3093  3421 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at fal.a(PG:38)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:45:52.886  3093  3421 E HttpOperation: 	... 14 more
,03-24 16:45:52.913  1775  3440 W DriveInitializer: Background init thread ended
,03-24 16:45:52.931  1349  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 16:45:52.931  1349  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:52.931  1349  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:52.931  1349  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:52.934  1349  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:52.956   822   855 I ActivityManager: Start proc 3462:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-24 16:45:52.963  3093  3421 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 16:45:52.963  3093  3421 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at hec.a(PG:42)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at hee.a(PG:102)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at czr.a(PG:65)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at kka.a(PG:108)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at czp.a(PG:19176)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at czp.a(PG:9081)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:45:52.963  3093  3421 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	... 15 more
03-24 16:45:52.963  3093  3421 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at fal.a(PG:38)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:45:52.963  3093  3421 E HttpOperation: 	... 17 more
03-24 16:45:52.963  3093  3421 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 16:45:52.963  3093  3421 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at hec.a(PG:42)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at hee.a(PG:102)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at czr.a(PG:65)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at kka.a(PG:108)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	... 15 more
03-24 16:45:52.963  3093  3421 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at fal.a(PG:38)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 16:45:52.963  3093  3421 E ExperimentLoader: 	... 17 more
,03-24 16:45:53.050   822  1096 I art     : Explicit concurrent mark sweep GC freed 55257(2MB) AllocSpace objects, 6(96KB) LOS objects, 32% free, 33MB/49MB, paused 1.715ms total 75.015ms
,03-24 16:45:53.070  1775  1775 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-24 16:45:53.076  1775  1775 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-24 16:45:53.078   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 38653, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:45:53.113   822   841 I ActivityManager: Start proc 3486:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-24 16:45:53.136   822   855 I ActivityManager: Start proc 3502:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-24 16:45:53.164   822  1326 I ActivityManager: Killing 2436:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-24 16:45:53.215  1349  3482 D GCM     : Connected
,03-24 16:45:53.265  3159  3483 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-24 16:45:53.274   822   840 I ActivityManager: Killing 2986:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-24 16:45:53.279  1349  3482 D GCM     : Message class com.google.f.a.a.p
,03-24 16:45:53.340  3486  3486 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-24 16:45:53.340  3486  3486 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 16:45:53.340  3486  3486 I GAv4    :   adb logcat -s GAv4
,03-24 16:45:53.352  3486  3486 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 16:45:53.362  3486  3486 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 16:45:53.371  3486  3528 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 16:45:53.476  3462  3462 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-24 16:45:53.499  3502  3548 V KeepSync: Connecting to GoogleApiClient
,03-24 16:45:53.500  1349  1373 I art     : Explicit concurrent mark sweep GC freed 12029(667KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 814us total 19.672ms
,03-24 16:45:53.504  3462  3462 I BooksApp: Created application version: 3.6.8 (30608)
,03-24 16:45:53.570  1775  3552 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 16:45:53.573  3486  3486 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-24 16:45:53.575  1775  3552 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 16:45:53.592  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 16:45:53.592  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:53.592  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:53.592  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:53.594  3486  3486 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9180-9183)
,03-24 16:45:53.595  3486  3486 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-24 16:45:53.596  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: Handling authorization failure
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 16:45:53.608  1775  3552 E ClientConnectionOperation: 	... 7 more
,03-24 16:45:53.609  3486  3486 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f36aa93}
03-24 16:45:53.610  3486  3486 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-24 16:45:53.610  3486  3486 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-24 16:45:53.612  3502  3548 V KeepSync: GoogleApiClient failed to connect with error code: 4
03-24 16:45:53.613  3502  3548 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 16:45:53.618  3486  3486 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-24 16:45:53.619  3486  3486 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 16:45:53.621  3486  3486 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-24 16:45:53.624  3462  3554 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 16:45:53.631  3502  3548 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 16:45:53.632  3502  3548 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 16:45:53.633  3486  3486 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-24 16:45:53.637  3486  3486 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 16:45:53.637  3486  3486 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-24 16:45:53.637  3486  3486 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-24 16:45:53.675  3486  3571 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-24 16:45:53.684  3486  3486 I NSApplication: Starting up...
,03-24 16:45:53.722   822   841 I ActivityManager: Start proc 3577:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-24 16:45:53.749  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,03-24 16:45:53.749  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:53.749  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:53.749  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:53.752  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:53.783  3502  3548 E KeepSync: IOException
03-24 16:45:53.783  3502  3548 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 16:45:53.783  3502  3548 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 16:45:53.783  3502  3548 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 16:45:53.783  3502  3548 E KeepSync: 	... 10 more
03-24 16:45:53.783  3502  3548 W KeepSync: Sync result 2
,03-24 16:45:53.787   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38659, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:45:53.788   822  1415 I ActivityManager: Killing 3006:com.android.musicfx/u0a18 (adj 15): empty #17
,03-24 16:45:53.836  3462  3597 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 16:45:53.895  1349  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 16:45:53.896  1349  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:53.896  1349  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:53.896  1349  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:53.899  1349  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:53.941  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 16:45:53.942  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:53.942  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:53.942  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:53.944  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:53.954  3462  3597 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 16:45:53.955  3462  3554 E BooksSync: Soft error
03-24 16:45:53.955  3462  3554 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:45:53.955  3462  3554 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 16:45:53.955  3462  3554 E BooksSync: Sync error
03-24 16:45:53.955  3462  3554 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:45:53.955  3462  3554 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 16:45:53.955  3462  3554 I BooksSync: Finished books sync
,03-24 16:45:53.967   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38659, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:45:53.967   822  1154 I ActivityManager: Killing 3055:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-24 16:45:54.185   822  1096 I ActivityManager: Start proc 3604:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-24 16:45:54.186   822  1096 I ActivityManager: Killing 2776:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-24 16:45:54.295   822  1096 I ActivityManager: Killing 1416:android.process.acore/u0a5 (adj 15): empty #17
,03-24 16:45:55.281   822   841 I ActivityManager: Killing 2799:com.google.android.gm/u0a78 (adj 15): empty #17
,03-24 16:45:55.597   822  2543 I ActivityManager: Start proc 3622:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-24 16:45:55.655  3622  3622 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458834355655
03-24 16:45:55.655  3622  3622 D         : TimeServiceNative: User Time to be set is 1458834355655
03-24 16:45:55.655  3622  3622 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-24 16:45:55.655  3622  3622 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-24 16:45:55.655  3622  3622 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458834355655
03-24 16:45:55.655  3622  3622 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-24 16:45:55.655   374   881 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458834355655
03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458834355655, operation = 0
03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/10/70 11:57:38
,03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:Value read from RTC seconds = 19137458000
03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:new time 1458834355655 
03-24 16:45:55.656   374  3639 D QC-time-services: Daemon: delta 1439696897655 genoff 1439696897655 
03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897655 to memory
03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-24 16:45:55.656   374  3639 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 16:45:55.661   374  3639 D QC-time-services: Updating the TOD offset
,03-24 16:45:55.661   374  3639 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696897655 to memory
03-24 16:45:55.661   374  3639 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-24 16:45:55.661   374  3639 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-24 16:45:55.665   374  3639 E QC-time-services: Daemon:Update to modem bit set
,03-24 16:45:55.665   374  3639 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-24 16:45:55.665   374  3639 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142869555655
03-24 16:45:55.665  3622  3622 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-24 16:45:55.734   374   881 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-24 16:45:55.737   822  1415 I art     : Explicit concurrent mark sweep GC freed 24099(1105KB) AllocSpace objects, 4(104KB) LOS objects, 32% free, 33MB/49MB, paused 1.631ms total 64.489ms
,03-24 16:45:55.741   374   879 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-24 16:45:55.844   822  2545 I ActivityManager: Start proc 3644:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-24 16:45:55.851   822  1326 I ActivityManager: Killing 3027:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-24 16:45:55.999  3644  3644 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-24 16:45:55.999  3644  3644 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-24 16:45:55.999  3644  3644 I GAv4    :   adb logcat -s GAv4
,03-24 16:45:56.014  3644  3644 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-24 16:45:56.025  3644  3644 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-24 16:45:56.040  3644  3663 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-24 16:45:56.088   822   840 I ActivityManager: Killing 3132:com.android.providers.calendar/u0a3 (adj 15): empty #17
,03-24 16:45:56.402  1775  1775 V Herrevad: NQAS connected
,03-24 16:45:56.406  3159  3159 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 16:45:56.406  3159  3159 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 16:45:56.451  1775  3666 I art     : Explicit concurrent mark sweep GC freed 14621(1134KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.078ms total 44.475ms
,03-24 16:45:56.463   822  1025 D WifiService: New client listening to asynchronous messages
,03-24 16:45:56.490   822  1320 I ActivityManager: Start proc 3675:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,03-24 16:45:56.513  3675  3675 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-24 16:45:56.549  3675  3675 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2dbd692f(com.android.providers.calendar.CalendarProvider2@390c4b3c)
,03-24 16:45:56.567  1349  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 16:45:56.567  1349  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:56.567  1349  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:56.568  1349  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:56.571  1349  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:56.581  3159  3669 E Babel   : UserRecoverableAuthException.
03-24 16:45:56.581  3159  3669 E Babel   : eei: BadAuthentication
03-24 16:45:56.581  3159  3669 E Babel   : 	at eeg.a(Unknown Source)
03-24 16:45:56.581  3159  3669 E Babel   : 	at eeg.a(Unknown Source)
03-24 16:45:56.581  3159  3669 E Babel   : 	at eeg.a(Unknown Source)
03-24 16:45:56.581  3159  3669 E Babel   : 	at g.a(Unknown Source)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cae.a(SourceFile:3089)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cae.a(SourceFile:1131)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cws.a(SourceFile:4333)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cws.a(SourceFile:1419)
03-24 16:45:56.581  3159  3669 E Babel   : 	at crl.a(SourceFile:492)
03-24 16:45:56.581  3159  3669 E Babel   : 	at crl.a(SourceFile:1468)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cas.b(SourceFile:106)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cap.d(SourceFile:335)
03-24 16:45:56.581  3159  3669 E Babel   : 	at caq.run(SourceFile:81)
03-24 16:45:56.581  3159  3669 E Babel   : Error getting auth token
03-24 16:45:56.581  3159  3669 E Babel   : dvm
03-24 16:45:56.581  3159  3669 E Babel   : 	at g.a(Unknown Source)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cae.a(SourceFile:3089)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cae.a(SourceFile:1131)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cws.a(SourceFile:4333)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cws.a(SourceFile:1419)
03-24 16:45:56.581  3159  3669 E Babel   : 	at crl.a(SourceFile:492)
03-24 16:45:56.581  3159  3669 E Babel   : 	at crl.a(SourceFile:1468)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cas.b(SourceFile:106)
03-24 16:45:56.581  3159  3669 E Babel   : 	at cap.d(SourceFile:335)
03-24 16:45:56.581  3159  3669 E Babel   : 	at caq.run(SourceFile:81)
,03-24 16:45:56.584  3159  3669 E Babel   : Account registration failed 1-Redacted-21
,03-24 16:45:56.586  3159  3669 E Babel   : cyp: null -- null
03-24 16:45:56.586  3159  3669 E Babel   : 	at cae.a(SourceFile:3121)
03-24 16:45:56.586  3159  3669 E Babel   : 	at cae.a(SourceFile:1131)
03-24 16:45:56.586  3159  3669 E Babel   : 	at cws.a(SourceFile:4333)
03-24 16:45:56.586  3159  3669 E Babel   : 	at cws.a(SourceFile:1419)
03-24 16:45:56.586  3159  3669 E Babel   : 	at crl.a(SourceFile:492)
03-24 16:45:56.586  3159  3669 E Babel   : 	at crl.a(SourceFile:1468)
03-24 16:45:56.586  3159  3669 E Babel   : 	at cqu.a(SourceFile:4416)
03-24 16:45:56.586  3159  3669 E Babel   : 	at cas.b(SourceFile:106)
03-24 16:45:56.586  3159  3669 E Babel   : 	at cap.d(SourceFile:335)
03-24 16:45:56.586  3159  3669 E Babel   : 	at caq.run(SourceFile:81)
,03-24 16:45:56.594  3159  3669 I art     : Note: end time exceeds epoch: 
,03-24 16:45:56.609  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-24 16:45:56.609  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:45:56.609  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:45:56.609  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:45:56.612  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:45:56.626  1349  1373 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-24 16:45:56.637  3159  3697 E Babel   : Unexpected exception while authenticating.
03-24 16:45:56.637  3159  3697 E Babel   : eej: User intervention required. Notification has been pushed.
03-24 16:45:56.637  3159  3697 E Babel   : 	at eeg.b(Unknown Source)
03-24 16:45:56.637  3159  3697 E Babel   : 	at eeg.b(Unknown Source)
03-24 16:45:56.637  3159  3697 E Babel   : 	at g.a(Unknown Source)
03-24 16:45:56.637  3159  3697 E Babel   : 	at cae.b(SourceFile:1146)
03-24 16:45:56.637  3159  3697 E Babel   : 	at dcg.run(SourceFile:5617)
03-24 16:45:56.637  3159  3697 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:45:56.637  3159  3697 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:45:56.637  3159  3697 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-24 16:45:56.963  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-24 16:45:56.963  3274  3331 I jxcore-log: 
,03-24 16:45:57.310  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
03-24 16:45:57.310  3274  3331 I jxcore-log: 
,03-24 16:45:57.322  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-24 16:45:57.322  3274  3331 I jxcore-log: 
,03-24 16:45:57.326  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-24 16:45:57.326  3274  3331 I jxcore-log: 
,03-24 16:45:57.365  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-24 16:45:57.365  3274  3331 I jxcore-log: 
,03-24 16:45:57.381  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-24 16:45:57.381  3274  3331 I jxcore-log: 
,03-24 16:45:57.385  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-24 16:45:57.385  3274  3331 I jxcore-log: 
,03-24 16:45:57.559  3675  3699 E SQLiteLog: (284) automatic index on view_events(_id)
,03-24 16:45:57.607  3675  3675 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-24 16:45:57.608  3675  3675 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-24 16:45:58.489  3462  3539 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-24 16:45:59.374  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-24 16:45:59.374  3274  3331 I jxcore-log: 
,03-24 16:45:59.392  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-24 16:45:59.392  3274  3331 I jxcore-log: 
,03-24 16:45:59.400  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-24 16:45:59.400  3274  3331 I jxcore-log: 
,03-24 16:45:59.541  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-24 16:45:59.541  3274  3331 I jxcore-log: 
,03-24 16:45:59.596  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-24 16:45:59.596  3274  3331 I jxcore-log: 
,03-24 16:45:59.644  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-24 16:45:59.644  3274  3331 I jxcore-log: 
,03-24 16:45:59.781  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-24 16:45:59.781  3274  3331 I jxcore-log: 
,03-24 16:45:59.786  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-24 16:45:59.786  3274  3331 I jxcore-log: 
,03-24 16:45:59.792  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-24 16:45:59.792  3274  3331 I jxcore-log: 
,03-24 16:45:59.808  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-24 16:45:59.808  3274  3331 I jxcore-log: 
,03-24 16:45:59.827  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-24 16:45:59.827  3274  3331 I jxcore-log: 
,03-24 16:45:59.934  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-24 16:45:59.934  3274  3331 I jxcore-log: 
03-24 16:45:59.939  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-24 16:45:59.939  3274  3331 I jxcore-log: 
,03-24 16:45:59.967  3274  3331 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-24 16:45:59.967  3274  3331 I jxcore-log: 
,03-24 16:45:59.997  1349  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:00.109  1349  3706 I VacuumService: Vacuum at: now=1458834360109 tag=VacuumService
,03-24 16:46:00.145  3385  3705 V GoogleAuthProtoRequest: [340] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 16:46:00.310  1349  1349 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 16:46:00.342  1349  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 16:46:00.342  1349  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 16:46:00.342  1349  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:00.342  1349  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:00.347  1349  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:00.399  1349  1349 I art     : Explicit concurrent mark sweep GC freed 26987(1622KB) AllocSpace objects, 2(32KB) LOS objects, 37% free, 26MB/42MB, paused 1.365ms total 44.416ms
,03-24 16:46:00.409  3385  3705 W ExperimentUpdateService: [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 16:46:00.410  3385  3705 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 16:46:01.327  3274  3331 I jxcore-log: TAP version 13
03-24 16:46:01.327  3274  3331 I jxcore-log: 
,03-24 16:46:01.330  3274  3331 I jxcore-log: # setup
03-24 16:46:01.330  3274  3331 I jxcore-log: 
,03-24 16:46:01.444  1349  3722 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-24 16:46:01.471  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:01.500  1349  3707 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,03-24 16:46:01.516  3274  3331 I jxcore-log: # 1. calling createNativeListener directly rejects
03-24 16:46:01.516  3274  3331 I jxcore-log: 
,03-24 16:46:01.729  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:01.729  3274  3331 I jxcore-log: 
,03-24 16:46:01.735  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 35139
,03-24 16:46:01.735  3274  3331 I jxcore-log: 
,03-24 16:46:01.743  3274  3331 I jxcore-log: ok 1 Should throw
,03-24 16:46:01.743  3274  3331 I jxcore-log: 
,03-24 16:46:01.748  3274  3331 I jxcore-log: # teardown
,03-24 16:46:01.748  3274  3331 I jxcore-log: 
,03-24 16:46:01.891  3274  3331 I jxcore-log: # setup
03-24 16:46:01.891  3274  3331 I jxcore-log: 
,03-24 16:46:02.125  3274  3331 I jxcore-log: # 2. emits incomingConnectionState
,03-24 16:46:02.125  3274  3331 I jxcore-log: 
,03-24 16:46:02.159  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:02.304  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 16:46:02.304  3274  3331 I jxcore-log: 
,03-24 16:46:02.312  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 43823
,03-24 16:46:02.312  3274  3331 I jxcore-log: 
,03-24 16:46:02.325  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:02.325  3274  3331 I jxcore-log: 
,03-24 16:46:02.330  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:02.330  3274  3331 I jxcore-log: 
,03-24 16:46:02.340  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:02.340  3274  3331 I jxcore-log: 
,03-24 16:46:02.346  3274  3331 I jxcore-log: ok 2 initial connection state should be CONNECTED
03-24 16:46:02.346  3274  3331 I jxcore-log: 
,03-24 16:46:02.364  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:02.364  3274  3331 I jxcore-log: 
03-24 16:46:02.365  3274  3331 I jxcore-log: ok 3 final connection state should be DISCONNECTED
03-24 16:46:02.365  3274  3331 I jxcore-log: 
,03-24 16:46:02.373  3274  3331 I jxcore-log: # teardown
03-24 16:46:02.373  3274  3331 I jxcore-log: 
,03-24 16:46:02.383  1349  3722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 16:46:02.383  1349  3722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:02.383  1349  3722 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 16:46:02.384  1349  3722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:02.387  1349  3722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:02.412  1349  3722 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 16:46:02.412  1349  3722 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 16:46:02.412  1349  3722 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 16:46:02.565  1349  3722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 16:46:02.565  1349  3722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:02.566  1349  3722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:02.566  1349  3722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:02.580  1349  3722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 16:46:02.632  1349  3722 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 16:46:02.632  1349  3722 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 16:46:02.632  1349  3722 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 16:46:02.684  3274  3331 I jxcore-log: # setup
03-24 16:46:02.684  3274  3331 I jxcore-log: 
,03-24 16:46:02.794  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:03.099  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:03.346  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:03.429  3274  3331 I jxcore-log: # 3. emits routerPortConnectionFailed
03-24 16:46:03.429  3274  3331 I jxcore-log: 
,03-24 16:46:03.523  1349  3722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 16:46:03.523  1349  3722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:03.523  1349  3722 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 16:46:03.524  1349  3722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:03.534  1349  3722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:03.624   822  2543 I art     : Explicit concurrent mark sweep GC freed 19548(866KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.639ms total 81.421ms
,03-24 16:46:03.670  2739  2755 D Finsky  : [250] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,03-24 16:46:03.676  1349  3722 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 16:46:03.676  1349  3722 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 16:46:03.676  1349  3722 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 16:46:03.679  1349  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:03.701  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-24 16:46:03.701  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 16:46:03.701  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:03.701  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:03.705  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:03.715  2739  2755 D Finsky  : [250] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-24 16:46:03.768  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:03.768  3274  3331 I jxcore-log: 
,03-24 16:46:03.771  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 53656
,03-24 16:46:03.771  3274  3331 I jxcore-log: 
,03-24 16:46:03.781  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 16:46:03.781  3274  3331 I jxcore-log: 
,03-24 16:46:03.784  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 16:46:03.784  3274  3331 I jxcore-log: 
,03-24 16:46:03.788  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
,03-24 16:46:03.788  3274  3331 I jxcore-log: 
,03-24 16:46:03.828  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:03.828  3274  3331 I jxcore-log: 
,03-24 16:46:03.831  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:03.831  3274  3331 I jxcore-log: 
,03-24 16:46:03.837  3274  3331 I jxcore-log: DEBUG createNativeListener: 
03-24 16:46:03.837  3274  3331 I jxcore-log: 
,03-24 16:46:03.838  3274  3331 I jxcore-log: ok 4 tried to connect to right port
03-24 16:46:03.838  3274  3331 I jxcore-log: 
,03-24 16:46:03.839  3274  3331 I jxcore-log: ok 5 failed due to refused connection
03-24 16:46:03.839  3274  3331 I jxcore-log: 
03-24 16:46:03.840  3274  3331 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
03-24 16:46:03.840  3274  3331 I jxcore-log: 
03-24 16:46:03.841  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:03.845  3274  3331 I jxcore-log: # teardown
03-24 16:46:03.845  3274  3331 I jxcore-log: 
,03-24 16:46:03.847  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:03.847  3274  3331 I jxcore-log: 
,03-24 16:46:03.994  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:04.027  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
,03-24 16:46:04.027  3274  3331 I jxcore-log: 
,03-24 16:46:04.034  3274  3331 I jxcore-log: # setup
,03-24 16:46:04.034  3274  3331 I jxcore-log: 
,03-24 16:46:04.035  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:04.035  3274  3331 I jxcore-log: 
,03-24 16:46:04.108  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:04.227  3274  3331 I jxcore-log: # 4. native server connections all up
03-24 16:46:04.227  3274  3331 I jxcore-log: 
,03-24 16:46:04.232  1349  3722 W Uploader:  no longer exists, so no auth token.
,03-24 16:46:04.354  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:04.354  3274  3331 I jxcore-log: 
,03-24 16:46:04.363  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 41241
03-24 16:46:04.363  3274  3331 I jxcore-log: 
,03-24 16:46:04.370  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:04.370  3274  3331 I jxcore-log: 
,03-24 16:46:04.371  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:04.371  3274  3331 I jxcore-log: 
,03-24 16:46:04.373  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:04.373  3274  3331 I jxcore-log: 
,03-24 16:46:04.404  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:04.404  3274  3331 I jxcore-log: 
,03-24 16:46:04.407  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:04.407  3274  3331 I jxcore-log: 
,03-24 16:46:04.410  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: ,
03-24 16:46:04.410  3274  3331 I jxcore-log: ,
03-24 16:46:04.412  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 16:46:04.412  3274  3331 I jxcore-log: 
,03-24 16:46:04.418  1349  3722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-24 16:46:04.419  1349  3722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 16:46:04.419  1349  3722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:04.419  1349  3722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:04.429  1349  3722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:04.439  3274  3331 I jxcore-log: ok 7 Send/recvd #1 should be equal length,
03-24 16:46:04.439  3274  3331 I jxcore-log: 
03-24 16:46:04.440  3274  3331 I jxcore-log: ok 8 Send/recvd #1 should be same
03-24 16:46:04.440  3274  3331 I jxcore-log: 
,03-24 16:46:04.443  3274  3331 I jxcore-log: ok 9 Send/recvd #2 should be equal length
03-24 16:46:04.443  3274  3331 I jxcore-log: 
,03-24 16:46:04.443  3274  3331 I jxcore-log: ok 10 Send/recvd #2 should be same
03-24 16:46:04.443  3274  3331 I jxcore-log: 
,03-24 16:46:04.481  3274  3331 I jxcore-log: ok 11 Should be exactly 2 client sockets
03-24 16:46:04.481  3274  3331 I jxcore-log: 
,03-24 16:46:04.490  3274  3331 I jxcore-log: # teardown
03-24 16:46:04.490  3274  3331 I jxcore-log: 
,03-24 16:46:04.498  1349  3722 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 16:46:04.498  1349  3722 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 16:46:04.498  1349  3722 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 16:46:04.630  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:04.630  3274  3331 I jxcore-log: 
,03-24 16:46:04.634  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:04.634  3274  3331 I jxcore-log: 
,03-24 16:46:04.638  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:04.638  3274  3331 I jxcore-log: 
,03-24 16:46:04.643  3274  3331 I jxcore-log: # setup
,03-24 16:46:04.643  3274  3331 I jxcore-log: 
03-24 16:46:04.644  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:04.644  3274  3331 I jxcore-log: 
,03-24 16:46:04.692  1349  3722 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-24 16:46:04.693  1349  3722 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:04.693  1349  3722 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:04.693  1349  3722 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:04.699  1349  3722 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:04.740  1349  3722 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 16:46:04.740  1349  3722 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-24 16:46:04.740  1349  3722 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-24 16:46:04.992  3274  3331 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
03-24 16:46:04.992  3274  3331 I jxcore-log: 
,03-24 16:46:05.120  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:05.141  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 16:46:05.141  3274  3331 I jxcore-log: 
,03-24 16:46:05.150  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 54371
,03-24 16:46:05.150  3274  3331 I jxcore-log: 
,03-24 16:46:05.162  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 16:46:05.162  3274  3331 I jxcore-log: 
,03-24 16:46:05.164  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:05.164  3274  3331 I jxcore-log: 
,03-24 16:46:05.169  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:05.169  3274  3331 I jxcore-log: 
,03-24 16:46:05.201  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
,03-24 16:46:05.201  3274  3331 I jxcore-log: 
,03-24 16:46:05.207  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 16:46:05.207  3274  3331 I jxcore-log: 
,03-24 16:46:05.227  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
,03-24 16:46:05.227  3274  3331 I jxcore-log: 
,03-24 16:46:05.243  3274  3331 I jxcore-log: ok 12 socket shouldn't close until after stream
,03-24 16:46:05.243  3274  3331 I jxcore-log: 
03-24 16:46:05.243  3274  3331 I jxcore-log: ok 13 incoming remains open
03-24 16:46:05.243  3274  3331 I jxcore-log: 
03-24 16:46:05.249  3274  3331 I jxcore-log: # teardown,
03-24 16:46:05.249  3274  3331 I jxcore-log: 
,03-24 16:46:05.280  1349  3722 W Uploader: No account for auth token provided
,03-24 16:46:05.384  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:05.384  3274  3331 I jxcore-log: 
,03-24 16:46:05.390  3274  3331 I jxcore-log: # setup
03-24 16:46:05.390  3274  3331 I jxcore-log: 
,03-24 16:46:05.392  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:05.392  3274  3331 I jxcore-log: 
,03-24 16:46:05.570  3274  3331 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
03-24 16:46:05.570  3274  3331 I jxcore-log: 
,03-24 16:46:05.857  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:05.857  3274  3331 I jxcore-log: 
,03-24 16:46:05.866  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 46430
03-24 16:46:05.866  3274  3331 I jxcore-log: 
,03-24 16:46:05.879  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:05.879  3274  3331 I jxcore-log: 
,03-24 16:46:05.884  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:05.884  3274  3331 I jxcore-log: 
,03-24 16:46:05.886  1349  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:05.888  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:05.888  3274  3331 I jxcore-log: 
,03-24 16:46:05.911  3274  3331 I jxcore-log: ok 14 we should not have gotten an error
03-24 16:46:05.911  3274  3331 I jxcore-log: 
,03-24 16:46:05.917  1349  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
03-24 16:46:05.917  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:05.917  3274  3331 I jxcore-log: 
03-24 16:46:05.917  1349  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:05.917  1349  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:05.917  1349  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:05.923  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:05.923  3274  3331 I jxcore-log: 
03-24 16:46:05.923  1349  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:05.934  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:05.934  3274  3331 I jxcore-log: 
,03-24 16:46:05.937  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:05.937  3274  3331 I jxcore-log: 
,03-24 16:46:05.945  3274  3331 I jxcore-log: ok 15 socket shouldn't close until after incoming
03-24 16:46:05.945  3274  3331 I jxcore-log: 
,03-24 16:46:05.945  3274  3331 I jxcore-log: ok 16 incoming is cleaned up
03-24 16:46:05.945  3274  3331 I jxcore-log: 
,03-24 16:46:05.951  2739  2739 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
03-24 16:46:05.951  2739  2739 D Finsky  : [1] 5.onFinished: Installation state replication failed.
03-24 16:46:05.951  2739  2739 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
03-24 16:46:05.952  3274  3331 I jxcore-log: # teardown
03-24 16:46:05.952  3274  3331 I jxcore-log: 
,03-24 16:46:06.093  3274  3331 I jxcore-log: # setup
03-24 16:46:06.093  3274  3331 I jxcore-log: 
,03-24 16:46:06.272  3274  3331 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
03-24 16:46:06.272  3274  3331 I jxcore-log: 
,03-24 16:46:06.442  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:06.442  3274  3331 I jxcore-log: 
,03-24 16:46:06.452  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 44413
03-24 16:46:06.452  3274  3331 I jxcore-log: 
,03-24 16:46:06.458  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:06.458  3274  3331 I jxcore-log: 
,03-24 16:46:06.460  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:06.460  3274  3331 I jxcore-log: 
,03-24 16:46:06.463  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:06.463  3274  3331 I jxcore-log: 
,03-24 16:46:06.474  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:06.474  3274  3331 I jxcore-log: 
,03-24 16:46:06.477  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:06.477  3274  3331 I jxcore-log: 
,03-24 16:46:06.492  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:06.492  3274  3331 I jxcore-log: 
,03-24 16:46:06.502  3274  3331 I jxcore-log: ok 17 stream was closed
,03-24 16:46:06.502  3274  3331 I jxcore-log: 
03-24 16:46:06.502  3274  3331 I jxcore-log: ok 18 incoming should survive
03-24 16:46:06.502  3274  3331 I jxcore-log: 
03-24 16:46:06.503  3274  3331 I jxcore-log: ok 19 mux should have no streams
03-24 16:46:06.503  3274  3331 I jxcore-log: 
,03-24 16:46:06.511  3274  3331 I jxcore-log: # teardown
03-24 16:46:06.511  3274  3331 I jxcore-log: 
,03-24 16:46:06.707  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:06.707  3274  3331 I jxcore-log: 
,03-24 16:46:06.716  3274  3331 I jxcore-log: # setup
03-24 16:46:06.716  3274  3331 I jxcore-log: ,
,03-24 16:46:06.717  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:06.717  3274  3331 I jxcore-log: 
,03-24 16:46:06.854  3274  3331 I jxcore-log: # 8. native server - closing the whole server cleans everything up
03-24 16:46:06.854  3274  3331 I jxcore-log: 
,03-24 16:46:07.315  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:07.315  3274  3331 I jxcore-log: 
,03-24 16:46:07.323  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 39242
03-24 16:46:07.323  3274  3331 I jxcore-log: 
,03-24 16:46:07.332  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:07.332  3274  3331 I jxcore-log: 
,03-24 16:46:07.335  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:07.335  3274  3331 I jxcore-log: 
,03-24 16:46:07.339  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:07.339  3274  3331 I jxcore-log: 
,03-24 16:46:07.362  3274  3331 I jxcore-log: ok 20 we should not have gotten an error
03-24 16:46:07.362  3274  3331 I jxcore-log: 
,03-24 16:46:07.368  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:07.368  3274  3331 I jxcore-log: 
,03-24 16:46:07.370  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:07.370  3274  3331 I jxcore-log: 
,03-24 16:46:07.380  3274  3331 I jxcore-log: ok 21 Buffers are identical
03-24 16:46:07.380  3274  3331 I jxcore-log: 
,03-24 16:46:07.383  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:07.383  3274  3331 I jxcore-log: 
,03-24 16:46:07.387  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:07.387  3274  3331 I jxcore-log: 
,03-24 16:46:07.390  3274  3331 I jxcore-log: ok 22 native server is nulled out
03-24 16:46:07.390  3274  3331 I jxcore-log: 
,03-24 16:46:07.391  3274  3331 I jxcore-log: ok 23 native server should be closed
03-24 16:46:07.391  3274  3331 I jxcore-log: 
,03-24 16:46:07.391  3274  3331 I jxcore-log: ok 24 incoming has been removed
03-24 16:46:07.391  3274  3331 I jxcore-log: 
03-24 16:46:07.392  3274  3331 I jxcore-log: ok 25 Incoming should be done
03-24 16:46:07.392  3274  3331 I jxcore-log: 
03-24 16:46:07.392  3274  3331 I jxcore-log: ok 26 The mux object should be closed
03-24 16:46:07.392  3274  3331 I jxcore-log: 
,03-24 16:46:07.392  3274  3331 I jxcore-log: ok 27 The mux stream should be closed
03-24 16:46:07.392  3274  3331 I jxcore-log: 
03-24 16:46:07.393  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:07.393  3274  3331 I jxcore-log: 
,03-24 16:46:07.410  3274  3331 I jxcore-log: # teardown
03-24 16:46:07.410  3274  3331 I jxcore-log: 
,03-24 16:46:07.504  3274  3331 I jxcore-log: # setup
03-24 16:46:07.504  3274  3331 I jxcore-log: 
,03-24 16:46:07.900  3274  3331 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
03-24 16:46:07.900  3274  3331 I jxcore-log: 
,03-24 16:46:08.135  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:08.135  3274  3331 I jxcore-log: 
,03-24 16:46:08.143  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 40709
03-24 16:46:08.143  3274  3331 I jxcore-log: 
,03-24 16:46:08.163  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:08.163  3274  3331 I jxcore-log: ,
03-24 16:46:08.165  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.165  3274  3331 I jxcore-log: 
,03-24 16:46:08.166  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.166  3274  3331 I jxcore-log: 
,03-24 16:46:08.170  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 16:46:08.170  3274  3331 I jxcore-log: 
03-24 16:46:08.171  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.171  3274  3331 I jxcore-log: 
03-24 16:46:08.172  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.172  3274  3331 I jxcore-log: 
,03-24 16:46:08.175  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:08.175  3274  3331 I jxcore-log: 
,03-24 16:46:08.176  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.176  3274  3331 I jxcore-log: 
03-24 16:46:08.177  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.177  3274  3331 I jxcore-log: 
,03-24 16:46:08.181  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:08.181  3274  3331 I jxcore-log: 
,03-24 16:46:08.182  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.182  3274  3331 I jxcore-log: 
03-24 16:46:08.183  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.183  3274  3331 I jxcore-log: 
,03-24 16:46:08.186  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:08.186  3274  3331 I jxcore-log: 
,03-24 16:46:08.186  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.186  3274  3331 I jxcore-log: 
,03-24 16:46:08.187  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.187  3274  3331 I jxcore-log: 
,03-24 16:46:08.193  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:08.193  3274  3331 I jxcore-log: 
,03-24 16:46:08.194  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.194  3274  3331 I jxcore-log: 
,03-24 16:46:08.195  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.195  3274  3331 I jxcore-log: 
,03-24 16:46:08.198  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:08.198  3274  3331 I jxcore-log: 
03-24 16:46:08.198  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.198  3274  3331 I jxcore-log: 
03-24 16:46:08.199  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.199  3274  3331 I jxcore-log: 
,03-24 16:46:08.202  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 16:46:08.202  3274  3331 I jxcore-log: 
03-24 16:46:08.202  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.202  3274  3331 I jxcore-log: 
03-24 16:46:08.203  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.203  3274  3331 I jxcore-log: 
,03-24 16:46:08.205  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket,
03-24 16:46:08.205  3274  3331 I jxcore-log: 
03-24 16:46:08.206  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.206  3274  3331 I jxcore-log: 
,03-24 16:46:08.206  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux,
03-24 16:46:08.206  3274  3331 I jxcore-log: 
03-24 16:46:08.208  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:08.208  3274  3331 I jxcore-log: 
03-24 16:46:08.208  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:08.208  3274  3331 I jxcore-log: 
03-24 16:46:08.209  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:08.209  3274  3331 I jxcore-log: 
,03-24 16:46:08.297  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.297  3274  3331 I jxcore-log: 
,03-24 16:46:08.300  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.300  3274  3331 I jxcore-log: 
,03-24 16:46:08.302  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.302  3274  3331 I jxcore-log: 
,03-24 16:46:08.304  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.304  3274  3331 I jxcore-log: 
,03-24 16:46:08.305  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.305  3274  3331 I jxcore-log: 
03-24 16:46:08.306  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.306  3274  3331 I jxcore-log: 
,03-24 16:46:08.308  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.308  3274  3331 I jxcore-log: 
,03-24 16:46:08.310  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.310  3274  3331 I jxcore-log: 
,03-24 16:46:08.313  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.313  3274  3331 I jxcore-log: 
,03-24 16:46:08.314  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.314  3274  3331 I jxcore-log: 
,03-24 16:46:08.315  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.315  3274  3331 I jxcore-log: 
,03-24 16:46:08.317  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.317  3274  3331 I jxcore-log: 
,03-24 16:46:08.318  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.318  3274  3331 I jxcore-log: 
,03-24 16:46:08.320  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.320  3274  3331 I jxcore-log: 
,03-24 16:46:08.321  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.321  3274  3331 I jxcore-log: 
,03-24 16:46:08.322  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.322  3274  3331 I jxcore-log: 
,03-24 16:46:08.325  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.325  3274  3331 I jxcore-log: 
,03-24 16:46:08.326  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.326  3274  3331 I jxcore-log: 
,03-24 16:46:08.327  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.327  3274  3331 I jxcore-log: 
,03-24 16:46:08.331  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.331  3274  3331 I jxcore-log: 
,03-24 16:46:08.333  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.333  3274  3331 I jxcore-log: 
,03-24 16:46:08.334  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.334  3274  3331 I jxcore-log: 
,03-24 16:46:08.336  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.336  3274  3331 I jxcore-log: 
,03-24 16:46:08.337  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.337  3274  3331 I jxcore-log: 
,03-24 16:46:08.339  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.339  3274  3331 I jxcore-log: 
,03-24 16:46:08.340  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.340  3274  3331 I jxcore-log: 
,03-24 16:46:08.341  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.341  3274  3331 I jxcore-log: 
,03-24 16:46:08.343  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.343  3274  3331 I jxcore-log: 
03-24 16:46:08.344  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.344  3274  3331 I jxcore-log: 
,03-24 16:46:08.345  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.345  3274  3331 I jxcore-log: 
,03-24 16:46:08.346  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.346  3274  3331 I jxcore-log: 
,03-24 16:46:08.348  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.348  3274  3331 I jxcore-log: 
,03-24 16:46:08.349  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.349  3274  3331 I jxcore-log: 
,03-24 16:46:08.351  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.351  3274  3331 I jxcore-log: 
,03-24 16:46:08.352  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.352  3274  3331 I jxcore-log: 
,03-24 16:46:08.353  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.353  3274  3331 I jxcore-log: 
,03-24 16:46:08.354  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.354  3274  3331 I jxcore-log: 
,03-24 16:46:08.356  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.356  3274  3331 I jxcore-log: 
,03-24 16:46:08.357  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.357  3274  3331 I jxcore-log: 
,03-24 16:46:08.358  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.358  3274  3331 I jxcore-log: 
,03-24 16:46:08.360  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.360  3274  3331 I jxcore-log: 
,03-24 16:46:08.362  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.362  3274  3331 I jxcore-log: 
,03-24 16:46:08.363  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.363  3274  3331 I jxcore-log: 
,03-24 16:46:08.364  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.364  3274  3331 I jxcore-log: 
,03-24 16:46:08.365  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.365  3274  3331 I jxcore-log: 
,03-24 16:46:08.367  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.367  3274  3331 I jxcore-log: 
,03-24 16:46:08.368  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.368  3274  3331 I jxcore-log: 
,03-24 16:46:08.369  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.369  3274  3331 I jxcore-log: 
,03-24 16:46:08.377  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.377  3274  3331 I jxcore-log: 
,03-24 16:46:08.378  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.378  3274  3331 I jxcore-log: 
,03-24 16:46:08.379  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.379  3274  3331 I jxcore-log: 
,03-24 16:46:08.381  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.381  3274  3331 I jxcore-log: 
,03-24 16:46:08.382  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.382  3274  3331 I jxcore-log: 
,03-24 16:46:08.383  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.383  3274  3331 I jxcore-log: 
,03-24 16:46:08.384  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.384  3274  3331 I jxcore-log: 
,03-24 16:46:08.385  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.385  3274  3331 I jxcore-log: 
,03-24 16:46:08.388  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.388  3274  3331 I jxcore-log: 
,03-24 16:46:08.389  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.389  3274  3331 I jxcore-log: 
,03-24 16:46:08.390  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.390  3274  3331 I jxcore-log: 
,03-24 16:46:08.391  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.391  3274  3331 I jxcore-log: 
,03-24 16:46:08.392  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.392  3274  3331 I jxcore-log: 
,03-24 16:46:08.394  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.394  3274  3331 I jxcore-log: 
,03-24 16:46:08.395  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.395  3274  3331 I jxcore-log: 
,03-24 16:46:08.396  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.396  3274  3331 I jxcore-log: 
,03-24 16:46:08.397  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.397  3274  3331 I jxcore-log: 
,03-24 16:46:08.399  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.399  3274  3331 I jxcore-log: 
,03-24 16:46:08.400  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.400  3274  3331 I jxcore-log: 
,03-24 16:46:08.401  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.401  3274  3331 I jxcore-log: 
,03-24 16:46:08.402  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.402  3274  3331 I jxcore-log: 
,03-24 16:46:08.403  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.403  3274  3331 I jxcore-log: 
,03-24 16:46:08.404  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.404  3274  3331 I jxcore-log: 
,03-24 16:46:08.406  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.406  3274  3331 I jxcore-log: 
,03-24 16:46:08.407  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.407  3274  3331 I jxcore-log: 
,03-24 16:46:08.409  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.409  3274  3331 I jxcore-log: 
,03-24 16:46:08.410  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.410  3274  3331 I jxcore-log: 
,03-24 16:46:08.411  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.411  3274  3331 I jxcore-log: 
,03-24 16:46:08.412  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.412  3274  3331 I jxcore-log: 
03-24 16:46:08.413  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.413  3274  3331 I jxcore-log: 
,03-24 16:46:08.414  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:08.414  3274  3331 I jxcore-log: 
,03-24 16:46:08.415  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:08.415  3274  3331 I jxcore-log: 
,03-24 16:46:08.488  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.488  3274  3331 I jxcore-log: 
,03-24 16:46:08.490  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.490  3274  3331 I jxcore-log: 
,03-24 16:46:08.492  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.492  3274  3331 I jxcore-log: 
,03-24 16:46:08.493  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.493  3274  3331 I jxcore-log: 
,03-24 16:46:08.494  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.494  3274  3331 I jxcore-log: 
,03-24 16:46:08.496  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.496  3274  3331 I jxcore-log: 
,03-24 16:46:08.497  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.497  3274  3331 I jxcore-log: 
03-24 16:46:08.497  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.497  3274  3331 I jxcore-log: 
,03-24 16:46:08.498  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.498  3274  3331 I jxcore-log: 
,03-24 16:46:08.499  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.499  3274  3331 I jxcore-log: 
,03-24 16:46:08.502  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.502  3274  3331 I jxcore-log: 
,03-24 16:46:08.503  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.503  3274  3331 I jxcore-log: 
03-24 16:46:08.504  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.504  3274  3331 I jxcore-log: 
,03-24 16:46:08.505  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.505  3274  3331 I jxcore-log: 
,03-24 16:46:08.507  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.507  3274  3331 I jxcore-log: 
,03-24 16:46:08.508  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.508  3274  3331 I jxcore-log: 
,03-24 16:46:08.509  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.509  3274  3331 I jxcore-log: 
03-24 16:46:08.510  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.510  3274  3331 I jxcore-log: 
,03-24 16:46:08.511  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.511  3274  3331 I jxcore-log: 
,03-24 16:46:08.512  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.512  3274  3331 I jxcore-log: 
03-24 16:46:08.513  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.513  3274  3331 I jxcore-log: 
03-24 16:46:08.513  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.513  3274  3331 I jxcore-log: 
03-24 16:46:08.514  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.514  3274  3331 I jxcore-log: 
03-24 16:46:08.515  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.515  3274  3331 I jxcore-log: 
03-24 16:46:08.516  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.516  3274  3331 I jxcore-log: 
,03-24 16:46:08.517  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.517  3274  3331 I jxcore-log: 
03-24 16:46:08.518  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.518  3274  3331 I jxcore-log: 
03-24 16:46:08.518  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.518  3274  3331 I jxcore-log: 
,03-24 16:46:08.519  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.519  3274  3331 I jxcore-log: 
03-24 16:46:08.520  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.520  3274  3331 I jxcore-log: 
03-24 16:46:08.521  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.521  3274  3331 I jxcore-log: 
,03-24 16:46:08.522  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.522  3274  3331 I jxcore-log: 
03-24 16:46:08.523  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.523  3274  3331 I jxcore-log: 
03-24 16:46:08.523  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.523  3274  3331 I jxcore-log: 
,03-24 16:46:08.524  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.524  3274  3331 I jxcore-log: 
03-24 16:46:08.525  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.525  3274  3331 I jxcore-log: 
03-24 16:46:08.526  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.526  3274  3331 I jxcore-log: 
,03-24 16:46:08.527  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.527  3274  3331 I jxcore-log: 
03-24 16:46:08.527  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.527  3274  3331 I jxcore-log: 
,03-24 16:46:08.528  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.528  3274  3331 I jxcore-log: 
03-24 16:46:08.529  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.529  3274  3331 I jxcore-log: 
,03-24 16:46:08.530  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.530  3274  3331 I jxcore-log: 
,03-24 16:46:08.531  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.531  3274  3331 I jxcore-log: 
,03-24 16:46:08.532  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.532  3274  3331 I jxcore-log: 
,03-24 16:46:08.532  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.532  3274  3331 I jxcore-log: 
03-24 16:46:08.533  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.533  3274  3331 I jxcore-log: 
03-24 16:46:08.534  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.534  3274  3331 I jxcore-log: 
,03-24 16:46:08.535  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.535  3274  3331 I jxcore-log: 
03-24 16:46:08.535  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:08.535  3274  3331 I jxcore-log: 
03-24 16:46:08.536  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:08.536  3274  3331 I jxcore-log: 
,03-24 16:46:08.539  3274  3331 I jxcore-log: ok 28 native server is nulled out
03-24 16:46:08.539  3274  3331 I jxcore-log: 
03-24 16:46:08.539  3274  3331 I jxcore-log: ok 29 native server should be closed
03-24 16:46:08.539  3274  3331 I jxcore-log: 
03-24 16:46:08.540  3274  3331 I jxcore-log: ok 30 incoming has been removed
03-24 16:46:08.540  3274  3331 I jxcore-log: ,
03-24 16:46:08.541  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.541  3274  3331 I jxcore-log: 
03-24 16:46:08.542  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.542  3274  3331 I jxcore-log: 
03-24 16:46:08.542  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.542  3274  3331 I jxcore-log: 
,03-24 16:46:08.542  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.542  3274  3331 I jxcore-log: 
03-24 16:46:08.543  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.543  3274  3331 I jxcore-log: 
03-24 16:46:08.543  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.543  3274  3331 I jxcore-log: 
,03-24 16:46:08.543  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.543  3274  3331 I jxcore-log: 
03-24 16:46:08.544  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.544  3274  3331 I jxcore-log: 
03-24 16:46:08.544  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.544  3274  3331 I jxcore-log: 
,03-24 16:46:08.544  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:08.544  3274  3331 I jxcore-log: 
,03-24 16:46:08.648  3274  3331 I jxcore-log: # teardown
03-24 16:46:08.648  3274  3331 I jxcore-log: 
,03-24 16:46:09.503   822  1096 I ActivityManager: Killing 1517:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-24 16:46:09.715   822  1096 E libprocessgroup: failed to kill 1 processes for processgroup 1517
,03-24 16:46:09.724   822  1025 D WifiService: Client connection lost with reason: 4,
,03-24 16:46:10.005  3274  3331 I jxcore-log: # setup
03-24 16:46:10.005  3274  3331 I jxcore-log: 
,03-24 16:46:10.243  3274  3331 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
03-24 16:46:10.243  3274  3331 I jxcore-log: 
,03-24 16:46:11.759  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:11.759  3274  3331 I jxcore-log: 
,03-24 16:46:11.765  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 58746
03-24 16:46:11.765  3274  3331 I jxcore-log: 
,03-24 16:46:11.771  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:11.771  3274  3331 I jxcore-log: 
,03-24 16:46:11.772  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:11.772  3274  3331 I jxcore-log: 
,03-24 16:46:11.775  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:11.775  3274  3331 I jxcore-log: 
,03-24 16:46:11.783  3274  3331 I jxcore-log: ok 31 we should not have gotten an error
03-24 16:46:11.783  3274  3331 I jxcore-log: 
,03-24 16:46:11.786  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:11.786  3274  3331 I jxcore-log: 
,03-24 16:46:11.789  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
,03-24 16:46:11.789  3274  3331 I jxcore-log: 
,03-24 16:46:11.797  3274  3331 I jxcore-log: ok 32 Buffers are identical
03-24 16:46:11.797  3274  3331 I jxcore-log: 
,03-24 16:46:11.798  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:11.798  3274  3331 I jxcore-log: 
,03-24 16:46:11.800  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:11.800  3274  3331 I jxcore-log: 
,03-24 16:46:11.812  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:11.812  3274  3331 I jxcore-log: 
,03-24 16:46:11.812  3274  3331 I jxcore-log: ok 33 server should be fine
03-24 16:46:11.812  3274  3331 I jxcore-log: 
,03-24 16:46:11.813  3274  3331 I jxcore-log: ok 34 server should be open
03-24 16:46:11.813  3274  3331 I jxcore-log: 
03-24 16:46:11.813  3274  3331 I jxcore-log: ok 35 incoming has been removed
03-24 16:46:11.813  3274  3331 I jxcore-log: 
03-24 16:46:11.813  3274  3331 I jxcore-log: ok 36 The mux object should be closed
03-24 16:46:11.813  3274  3331 I jxcore-log: 
,03-24 16:46:11.814  3274  3331 I jxcore-log: ok 37 The mux stream should be closed
03-24 16:46:11.814  3274  3331 I jxcore-log: 
,03-24 16:46:11.821  3274  3331 I jxcore-log: # teardown
03-24 16:46:11.821  3274  3331 I jxcore-log: 
,03-24 16:46:11.919  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,03-24 16:46:12.040  3274  3331 I jxcore-log: # setup
03-24 16:46:12.040  3274  3331 I jxcore-log: 
,03-24 16:46:12.546  3274  3331 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
03-24 16:46:12.546  3274  3331 I jxcore-log: 
,03-24 16:46:13.396  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:13.396  3274  3331 I jxcore-log: 
,03-24 16:46:13.404  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 51299
,03-24 16:46:13.404  3274  3331 I jxcore-log: 
,03-24 16:46:13.410  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:46:13.410  3274  3331 I jxcore-log: 
,03-24 16:46:13.411  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:46:13.411  3274  3331 I jxcore-log: 
,03-24 16:46:13.412  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:46:13.412  3274  3331 I jxcore-log: 
,03-24 16:46:13.418  3274  3331 I jxcore-log: ok 38 we should not have gotten an error
03-24 16:46:13.418  3274  3331 I jxcore-log: 
,03-24 16:46:13.422  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:46:13.422  3274  3331 I jxcore-log: 
,03-24 16:46:13.424  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:46:13.424  3274  3331 I jxcore-log: 
,03-24 16:46:13.431  3274  3331 I jxcore-log: ok 39 Buffers are identical
03-24 16:46:13.431  3274  3331 I jxcore-log: 
,03-24 16:46:13.436  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
03-24 16:46:13.436  3274  3331 I jxcore-log: 
,03-24 16:46:13.437  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:46:13.437  3274  3331 I jxcore-log: 
,03-24 16:46:13.439  3274  3331 I jxcore-log: DEBUG createNativeListener: mux close
03-24 16:46:13.439  3274  3331 I jxcore-log: 
,03-24 16:46:13.444  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:46:13.444  3274  3331 I jxcore-log: 
,03-24 16:46:13.444  3274  3331 I jxcore-log: ok 40 server should be fine
03-24 16:46:13.444  3274  3331 I jxcore-log: 
,03-24 16:46:13.445  3274  3331 I jxcore-log: ok 41 server should be open
03-24 16:46:13.445  3274  3331 I jxcore-log: 
03-24 16:46:13.445  3274  3331 I jxcore-log: ok 42 incoming has been removed
03-24 16:46:13.445  3274  3331 I jxcore-log: 
03-24 16:46:13.446  3274  3331 I jxcore-log: ok 43 The mux object should be closed
03-24 16:46:13.446  3274  3331 I jxcore-log: 
,03-24 16:46:13.446  3274  3331 I jxcore-log: ok 44 The mux stream should be closed
03-24 16:46:13.446  3274  3331 I jxcore-log: 
,03-24 16:46:13.455  3274  3331 I jxcore-log: # teardown
03-24 16:46:13.455  3274  3331 I jxcore-log: 
,03-24 16:46:13.605  3274  3331 I jxcore-log: # setup
03-24 16:46:13.605  3274  3331 I jxcore-log: 
,03-24 16:46:14.354  3274  3331 I jxcore-log: # 12. closeAll can close even when connections open
03-24 16:46:14.354  3274  3331 I jxcore-log: 
,03-24 16:46:15.224  3274  3331 I jxcore-log: ok 45 not possible to connect to the server anymore
03-24 16:46:15.224  3274  3331 I jxcore-log: 
,03-24 16:46:15.229  3274  3331 I jxcore-log: # teardown
03-24 16:46:15.229  3274  3331 I jxcore-log: 
,03-24 16:46:15.404  3274  3331 I jxcore-log: # setup
03-24 16:46:15.404  3274  3331 I jxcore-log: 
,03-24 16:46:16.060  3274  3331 I jxcore-log: # 13. closeAll with promise
03-24 16:46:16.060  3274  3331 I jxcore-log: 
,03-24 16:46:17.520  3274  3331 I jxcore-log: ok 46 not possible to connect to the server anymore
03-24 16:46:17.520  3274  3331 I jxcore-log: 
,03-24 16:46:17.524  3274  3331 I jxcore-log: # teardown
03-24 16:46:17.524  3274  3331 I jxcore-log: 
,03-24 16:46:19.114  3274  3331 I jxcore-log: # setup
03-24 16:46:19.114  3274  3331 I jxcore-log: 
,03-24 16:46:21.344  3274  3331 I jxcore-log: # 14. multiplex can send data
03-24 16:46:21.344  3274  3331 I jxcore-log: 
,03-24 16:46:23.536  3274  3331 I jxcore-log: ok 47 String should be length:200
03-24 16:46:23.536  3274  3331 I jxcore-log: 
,03-24 16:46:23.545  3274  3331 I jxcore-log: # teardown
03-24 16:46:23.545  3274  3331 I jxcore-log: 
,03-24 16:46:25.250  3274  3331 I jxcore-log: # setup
03-24 16:46:25.250  3274  3331 I jxcore-log: 
,03-24 16:46:26.678  3274  3331 I jxcore-log: # 15. enqueue and run in order
,03-24 16:46:26.678  3274  3331 I jxcore-log: 
,03-24 16:46:28.330  3274  3331 I jxcore-log: ok 48 firstPromise setTimeout
03-24 16:46:28.330  3274  3331 I jxcore-log: 
,03-24 16:46:28.334  3274  3331 I jxcore-log: ok 49 firstPromise result,
,03-24 16:46:28.334  3274  3331 I jxcore-log: 
,03-24 16:46:28.336  3274  3331 I jxcore-log: ok 50 firstPromise testValue,
03-24 16:46:28.336  3274  3331 I jxcore-log: 
,03-24 16:46:28.442  3274  3331 I jxcore-log: ok 51 secondPromise setTimeout
03-24 16:46:28.442  3274  3331 I jxcore-log: 
,03-24 16:46:28.447  3274  3331 I jxcore-log: ok 52 secondPromise result
03-24 16:46:28.447  3274  3331 I jxcore-log: 
,03-24 16:46:28.448  3274  3331 I jxcore-log: ok 53 secondPromise testValue
03-24 16:46:28.448  3274  3331 I jxcore-log: 
,03-24 16:46:28.453  3274  3331 I jxcore-log: ok 54 thirdPromise in promise
03-24 16:46:28.453  3274  3331 I jxcore-log: 
,03-24 16:46:28.457  3274  3331 I jxcore-log: ok 55 thirdPromise result
03-24 16:46:28.457  3274  3331 I jxcore-log: 
,03-24 16:46:28.460  3274  3331 I jxcore-log: ok 56 thirdPromise testValue
03-24 16:46:28.460  3274  3331 I jxcore-log: 
,03-24 16:46:28.474  3274  3331 I jxcore-log: # teardown
03-24 16:46:28.474  3274  3331 I jxcore-log: 
,03-24 16:46:28.642  3274  3331 I jxcore-log: # setup
03-24 16:46:28.642  3274  3331 I jxcore-log: 
,03-24 16:46:28.827  3274  3331 I jxcore-log: # 16. enqueueAtTop and run backwards
03-24 16:46:28.827  3274  3331 I jxcore-log: 
,03-24 16:46:28.984  3274  3331 I jxcore-log: ok 57 thirdPromise - first to run
03-24 16:46:28.984  3274  3331 I jxcore-log: 
,03-24 16:46:28.988  3274  3331 I jxcore-log: ok 58 thirdPromise - in resolve
03-24 16:46:28.988  3274  3331 I jxcore-log: 
,03-24 16:46:28.993  3274  3331 I jxcore-log: ok 59 secondPromise - second to run
03-24 16:46:28.993  3274  3331 I jxcore-log: 
,03-24 16:46:28.994  3274  3331 I jxcore-log: ok 60 secondPromise - in catch
03-24 16:46:28.994  3274  3331 I jxcore-log: 
,03-24 16:46:28.995  3274  3331 I jxcore-log: ok 61 firstPromise - third to run
03-24 16:46:28.995  3274  3331 I jxcore-log: 
,03-24 16:46:28.996  3274  3331 I jxcore-log: ok 62 firstPromise - in then
03-24 16:46:28.996  3274  3331 I jxcore-log: 
03-24 16:46:28.997  3274  3331 I jxcore-log: ok 63 testing promises
03-24 16:46:28.997  3274  3331 I jxcore-log: 
,03-24 16:46:29.000  3274  3331 I jxcore-log: # teardown
03-24 16:46:29.000  3274  3331 I jxcore-log: 
,03-24 16:46:29.148  3274  3331 I jxcore-log: # setup
03-24 16:46:29.148  3274  3331 I jxcore-log: 
,03-24 16:46:29.327  3274  3331 I jxcore-log: # 17. mix enqueue and enqueueAtTop
03-24 16:46:29.327  3274  3331 I jxcore-log: 
,03-24 16:46:29.578  3274  3331 I jxcore-log: ok 64 fourth
03-24 16:46:29.578  3274  3331 I jxcore-log: 
,03-24 16:46:29.582  3274  3331 I jxcore-log: ok 65 fourth
03-24 16:46:29.582  3274  3331 I jxcore-log: 
03-24 16:46:29.585  3274  3331 I jxcore-log: ok 66 second
03-24 16:46:29.585  3274  3331 I jxcore-log: 
,03-24 16:46:29.587  3274  3331 I jxcore-log: ok 67 secondPromise - in then
03-24 16:46:29.587  3274  3331 I jxcore-log: 
,03-24 16:46:29.692  3274  3331 I jxcore-log: ok 68 first
03-24 16:46:29.692  3274  3331 I jxcore-log: 
,03-24 16:46:29.697  3274  3331 I jxcore-log: ok 69 firstPromise - in catch
03-24 16:46:29.697  3274  3331 I jxcore-log: 
,03-24 16:46:29.701  3274  3331 I jxcore-log: ok 70 third
03-24 16:46:29.701  3274  3331 I jxcore-log: 
,03-24 16:46:29.705  3274  3331 I jxcore-log: ok 71 thirdPromise - in then
03-24 16:46:29.705  3274  3331 I jxcore-log: 
,03-24 16:46:29.709  3274  3331 I jxcore-log: ok 72 testingPromises
03-24 16:46:29.709  3274  3331 I jxcore-log: 
,03-24 16:46:29.723  3274  3331 I jxcore-log: # teardown
03-24 16:46:29.723  3274  3331 I jxcore-log: 
,03-24 16:46:29.871  3274  3331 I jxcore-log: # setup
03-24 16:46:29.871  3274  3331 I jxcore-log: 
,03-24 16:46:30.033  3274  3331 I jxcore-log: # 18. queues handled independently
03-24 16:46:30.033  3274  3331 I jxcore-log: 
,03-24 16:46:30.200  3274  3331 I jxcore-log: ok 73 all short operations completed before the long resolves
03-24 16:46:30.200  3274  3331 I jxcore-log: 
,03-24 16:46:30.205  3274  3331 I jxcore-log: # teardown
03-24 16:46:30.205  3274  3331 I jxcore-log: 
,03-24 16:46:30.327  3274  3331 I jxcore-log: # setup
03-24 16:46:30.327  3274  3331 I jxcore-log: 
,03-24 16:46:30.495  3274  3331 I jxcore-log: # 19. basic
03-24 16:46:30.495  3274  3331 I jxcore-log: 
,03-24 16:46:30.644  3274  3331 I jxcore-log: ok 74 sane
03-24 16:46:30.644  3274  3331 I jxcore-log: 
,03-24 16:46:30.652  3274  3331 I jxcore-log: # teardown
03-24 16:46:30.652  3274  3331 I jxcore-log: 
,03-24 16:46:30.822  3274  3331 I jxcore-log: # setup
03-24 16:46:30.822  3274  3331 I jxcore-log: 
,03-24 16:46:30.989  3274  3331 I jxcore-log: # 20. another
03-24 16:46:30.989  3274  3331 I jxcore-log: 
,03-24 16:46:31.212  3274  3331 I jxcore-log: ok 75 sane
03-24 16:46:31.212  3274  3331 I jxcore-log: 
,03-24 16:46:31.220  3274  3331 I jxcore-log: # teardown
03-24 16:46:31.220  3274  3331 I jxcore-log: 
,03-24 16:46:31.357  3274  3331 I jxcore-log: # setup
03-24 16:46:31.357  3274  3331 I jxcore-log: 
,03-24 16:46:31.465  3274  3331 I jxcore-log: # 21. can pass data in setup
03-24 16:46:31.465  3274  3331 I jxcore-log: 
,03-24 16:46:31.605  3274  3331 I jxcore-log: ok 76 test participant has uuid
03-24 16:46:31.605  3274  3331 I jxcore-log: 
,03-24 16:46:31.607  3274  3331 I jxcore-log: ok 77 participant data matches
03-24 16:46:31.607  3274  3331 I jxcore-log: 
,03-24 16:46:31.609  3274  3331 I jxcore-log: ok 78 test participant has uuid
03-24 16:46:31.609  3274  3331 I jxcore-log: 
,03-24 16:46:31.612  3274  3331 I jxcore-log: ok 79 participant data matches
03-24 16:46:31.612  3274  3331 I jxcore-log: 
,03-24 16:46:31.612  3274  3331 I jxcore-log: ok 80 test participant has uuid
03-24 16:46:31.612  3274  3331 I jxcore-log: 
,03-24 16:46:31.613  3274  3331 I jxcore-log: ok 81 participant data matches
03-24 16:46:31.613  3274  3331 I jxcore-log: 
,03-24 16:46:31.615  3274  3331 I jxcore-log: # teardown
03-24 16:46:31.615  3274  3331 I jxcore-log: 
,03-24 16:46:31.754  3274  3331 I jxcore-log: # setup
03-24 16:46:31.754  3274  3331 I jxcore-log: 
,03-24 16:46:31.890  3274  3331 I jxcore-log: # 22. #startListeningForAdvertisements should fail if start not called
03-24 16:46:31.890  3274  3331 I jxcore-log: 
,03-24 16:46:32.022  3274  3331 I jxcore-log: ok 82 specific error should be returned
03-24 16:46:32.022  3274  3331 I jxcore-log: 
,03-24 16:46:32.024  3274  3331 I jxcore-log: # teardown
03-24 16:46:32.024  3274  3331 I jxcore-log: 
,03-24 16:46:32.143  3274  3331 I jxcore-log: ok 83 error should be null
03-24 16:46:32.143  3274  3331 I jxcore-log: 
,03-24 16:46:32.144  3274  3331 I jxcore-log: ok 84 error should be null
03-24 16:46:32.144  3274  3331 I jxcore-log: 
,03-24 16:46:32.145  3274  3331 I jxcore-log: # setup
03-24 16:46:32.145  3274  3331 I jxcore-log: 
,03-24 16:46:32.251  3274  3331 I jxcore-log: # 23. #startUpdateAdvertisingAndListening should fail if start not called
03-24 16:46:32.251  3274  3331 I jxcore-log: 
,03-24 16:46:32.824  3274  3331 I jxcore-log: ok 85 specific error should be returned
03-24 16:46:32.824  3274  3331 I jxcore-log: 
,03-24 16:46:32.825  3274  3331 I jxcore-log: # teardown
03-24 16:46:32.825  3274  3331 I jxcore-log: 
,03-24 16:46:32.942  3274  3331 I jxcore-log: ok 86 error should be null
03-24 16:46:32.942  3274  3331 I jxcore-log: 
,03-24 16:46:32.942  3274  3331 I jxcore-log: ok 87 error should be null
03-24 16:46:32.942  3274  3331 I jxcore-log: 
,03-24 16:46:32.944  3274  3331 I jxcore-log: # setup
03-24 16:46:32.944  3274  3331 I jxcore-log: 
,03-24 16:46:33.042  3274  3331 I jxcore-log: # 24. should be able to call #stopListeningForAdvertisements many times
03-24 16:46:33.042  3274  3331 I jxcore-log: 
,03-24 16:46:33.286  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:33.286  3274  3331 I jxcore-log: 
,03-24 16:46:33.287  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 57332
03-24 16:46:33.287  3274  3331 I jxcore-log: 
03-24 16:46:33.290  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:46:33.290  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:46:33.290  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:33.294  3274  3331 I jxcore-log: ok 88 error should be null
03-24 16:46:33.294  3274  3331 I jxcore-log: 
,03-24 16:46:33.294  3274  3331 I jxcore-log: ok 89 error should be null
03-24 16:46:33.294  3274  3331 I jxcore-log: 
03-24 16:46:33.295  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:46:33.296  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:46:33.296  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:46:33.297  3274  3331 I jxcore-log: ok 90 error should be null
03-24 16:46:33.297  3274  3331 I jxcore-log: 
03-24 16:46:33.297  3274  3331 I jxcore-log: ok 91 error should be null
03-24 16:46:33.297  3274  3331 I jxcore-log: 
,03-24 16:46:33.301  3274  3331 I jxcore-log: # teardown
03-24 16:46:33.301  3274  3331 I jxcore-log: 
,03-24 16:46:33.466  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:46:33.466  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:46:33.466  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:33.469  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:46:33.469  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:46:33.469  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:33.474  3274  3331 I jxcore-log: ok 92 error should be null
03-24 16:46:33.474  3274  3331 I jxcore-log: 
,03-24 16:46:33.474  3274  3331 I jxcore-log: ok 93 error should be null
03-24 16:46:33.474  3274  3331 I jxcore-log: 
,03-24 16:46:33.481  3274  3331 I jxcore-log: # setup
03-24 16:46:33.481  3274  3331 I jxcore-log: 
,03-24 16:46:33.674  3274  3331 I jxcore-log: # 25. should be able to call #startListeningForAdvertisements many times
03-24 16:46:33.674  3274  3331 I jxcore-log: 
,03-24 16:46:33.872  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:33.872  3274  3331 I jxcore-log: 
,03-24 16:46:33.874  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 45950
03-24 16:46:33.874  3274  3331 I jxcore-log: 
,03-24 16:46:33.886  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
03-24 16:46:33.886  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:46:33.886  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:46:33.886  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 16:46:33.886  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:46:33.886  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:46:33.895  3274  3331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:46:33.896   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:46:33.905  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:46:33.913  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 16:46:33.913  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:46:33.913  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:46:33.918  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:46:33.930  2150  2167 D BtGatt.GattService: registerClient() - UUID=da789dfb-2f50-4a2e-809b-f3e2b04e360c
,03-24 16:46:33.933  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=da789dfb-2f50-4a2e-809b-f3e2b04e360c, clientIf=5,
,03-24 16:46:33.934  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
,03-24 16:46:33.937  2150  2957 D BtGatt.GattService: start scan with filters
,03-24 16:46:33.940  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:46:33.940  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
03-24 16:46:33.940  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 16:46:33.940  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:46:33.940  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:46:33.940  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 16:46:33.941  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:46:33.941  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:46:33.941   822  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:46:33.944  2150  2222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@359080c5
,03-24 16:46:33.948  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:46:33.948  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 16:46:33.952  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 16:46:33.952  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:46:33.953  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:46:33.953  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:46:33.959  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:46:33.959  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:46:33.963  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 16:46:33.963  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:46:33.965  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:46:33.965  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:46:33.968  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 16:46:33.968  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:33.969  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:46:33.970  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 16:46:33.974  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 16:46:33.974  3274  3331 I jxcore-log: 
,03-24 16:46:33.976  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 16:46:33.976  3274  3331 I jxcore-log: 
,03-24 16:46:33.979  3274  3331 I jxcore-log: ok 94 error should be null,
03-24 16:46:33.979  3274  3331 I jxcore-log: 
,03-24 16:46:33.981  3274  3331 I jxcore-log: ok 95 error should be null
03-24 16:46:33.981  3274  3331 I jxcore-log: 
,03-24 16:46:33.987  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,03-24 16:46:33.988  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:46:33.988  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:46:33.988  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:46:33.988  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:46:33.991  3274  3331 I jxcore-log: ok 96 error should be null
03-24 16:46:33.991  3274  3331 I jxcore-log: 
,03-24 16:46:33.991  3274  3331 I jxcore-log: ok 97 error should be null
03-24 16:46:33.991  3274  3331 I jxcore-log: 
,03-24 16:46:33.997  3274  3331 I jxcore-log: # teardown
,03-24 16:46:33.997  3274  3331 I jxcore-log: 
,03-24 16:46:34.262  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:46:34.262  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,03-24 16:46:34.262  3274  3331 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 16:46:34.262  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:46:34.262  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:46:34.262  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:46:34.262  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,03-24 16:46:34.263  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,03-24 16:46:34.263  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:46:34.265  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:46:34.266  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:46:34.267  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:46:34.267  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:46:34.267  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:46:34.267  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 16:46:34.267  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 16:46:34.267  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:46:34.268  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 16:46:34.268  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:46:34.268  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:46:34.268  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:46:34.268  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 16:46:34.268  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 16:46:34.269  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:46:34.270  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:46:34.270  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:46:34.270  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:46:34.270  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:46:34.271  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 16:46:34.271  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:34.272  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:46:34.273  3274  3331 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 16:46:34.273  3274  3331 I jxcore-log: 
03-24 16:46:34.275  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 16:46:34.275  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:34.283  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 16:46:34.284   822  1326 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:46:34.295  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:46:34.296  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:46:34.296  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:46:34.302  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:46:34.302  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 16:46:34.302  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:46:34.303  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:46:34.307  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:46:34.308  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:46:34.308  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:34.313  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:46:34.313  3274  3331 I jxcore-log: 
,03-24 16:46:34.316  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:46:34.316  3274  3331 I jxcore-log: 
,03-24 16:46:34.324  3274  3331 I jxcore-log: ok 98 error should be null
03-24 16:46:34.324  3274  3331 I jxcore-log: 
,03-24 16:46:34.325  3274  3331 I jxcore-log: ok 99 error should be null
03-24 16:46:34.325  3274  3331 I jxcore-log: 
,03-24 16:46:34.335  3274  3331 I jxcore-log: # setup
,03-24 16:46:34.335  3274  3331 I jxcore-log: 
,03-24 16:46:34.587  3274  3331 I jxcore-log: # 26. should be able to call #startUpdateAdvertisingAndListening many times
03-24 16:46:34.587  3274  3331 I jxcore-log: 
,03-24 16:46:34.781  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 16:46:34.781  3274  3331 I jxcore-log: 
,03-24 16:46:34.784  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 34822
,03-24 16:46:34.784  3274  3331 I jxcore-log: 
,03-24 16:46:34.801  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 34822, start advertisements: true
,03-24 16:46:34.801  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:46:34.801  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 16:46:34.801  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:46:34.806  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 16:46:34.806  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:46:34.806  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:46:34.806  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:46:34.811  2150  2167 D BtGatt.GattService: registerClient() - UUID=4ee036fc-94c9-490e-935f-a24fae053e83,
03-24 16:46:34.812  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=4ee036fc-94c9-490e-935f-a24fae053e83, clientIf=5
03-24 16:46:34.813  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:46:34.813  2150  2957 D BtGatt.GattService: start scan with filters
,03-24 16:46:34.815  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 16:46:34.815  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:46:34.815  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:46:34.815  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:46:34.815  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,03-24 16:46:34.815  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:46:34.815  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
,03-24 16:46:34.815  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:46:34.816  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:46:34.817  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61,
03-24 16:46:34.818  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 16:46:34.818  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:34.820  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 16:46:34.820  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:46:34.821  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:46:34.821  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:46:34.824  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:46:34.824  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:34.825  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:46:34.825  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:46:34.826  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:34.826  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:46:34.827  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:46:34.834  2150  2166 D BtGatt.GattService: registerClient() - UUID=374207b6-f4fe-4c3c-8830-2a527faedf65
,03-24 16:46:34.835  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=374207b6-f4fe-4c3c-8830-2a527faedf65, clientIf=6
03-24 16:46:34.835  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:46:34.839  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:46:34.844  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:46:34.848  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:46:34.851  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 16:46:34.853  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:46:34.853  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 16:46:34.854   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:46:34.857  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:46:34.857  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
03-24 16:46:34.857  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 16:46:34.857  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:46:34.858  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 16:46:34.859  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 16:46:34.859  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:46:34.859  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 16:46:34.859  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:46:34.859  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 16:46:34.860  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 16:46:34.861  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:46:34.861  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 16:46:34.861  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:46:34.861  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:46:34.861  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:46:34.861  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:46:34.861  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:46:34.861  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
03-24 16:46:34.861  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:46:34.862  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:46:34.868   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:46:34.870  3274  3734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:46:34.870  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 16:46:34.870  3274  3331 I jxcore-log: 
03-24 16:46:34.872  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 16:46:34.872  3274  3331 I jxcore-log: 
,03-24 16:46:34.873  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:46:34.873  3274  3331 I jxcore-log: 
03-24 16:46:34.874  3274  3734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 16:46:34.875  3274  3331 I jxcore-log: ok 100 error should be null
,03-24 16:46:34.875  3274  3331 I jxcore-log: 
03-24 16:46:34.875  3274  3331 I jxcore-log: ok 101 error should be null
03-24 16:46:34.875  3274  3331 I jxcore-log: 
,03-24 16:46:34.883  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 34822, start advertisements: true
03-24 16:46:34.883  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:46:34.883  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:46:34.883  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:46:34.883  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:46:34.892  3274  3331 I jxcore-log: ok 102 error should be null
03-24 16:46:34.892  3274  3331 I jxcore-log: 
,03-24 16:46:34.892  3274  3331 I jxcore-log: ok 103 error should be null
03-24 16:46:34.892  3274  3331 I jxcore-log: 
,03-24 16:46:34.898  3274  3331 I jxcore-log: # teardown
,03-24 16:46:34.898  3274  3331 I jxcore-log: 
,03-24 16:46:35.296  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:46:35.296  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 16:46:35.296  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:46:35.296  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 16:46:35.296  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:46:35.297  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:46:35.297  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:46:35.297  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 16:46:35.297  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:46:35.297  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:46:35.297  3274  3734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 16:46:35.297  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:46:35.297  3274  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:46:35.297  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 16:46:35.297  3274  3734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 16:46:35.300  2150  2167 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:46:35.301  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:46:35.307  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:46:35.307  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:46:35.307  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 16:46:35.308  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:46:35.308  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:35.308  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:46:35.308  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 16:46:35.308  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:46:35.308  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:46:35.308  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 16:46:35.311  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:46:35.312  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:35.312  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:46:35.313  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:46:35.313  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:46:35.315  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,03-24 16:46:35.315  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:35.315  2150  2212 D BtGatt.GattService: current time is 210904926221
,03-24 16:46:35.315  2150  2212 D BtGatt.GattService: Batch record : [106, 67, -15, -33, 89, 87, 1, -128, -62, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 6, 0, 0, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 16:46:35.316  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:46:35.317  2150  2212 D BtGatt.GattService: ScanRecord : []
03-24 16:46:35.317  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:46:35.317  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 16:46:35.317  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:46:35.320  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:46:35.321  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:46:35.321  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:46:35.322  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 16:46:35.322  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 16:46:35.322  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:46:35.322  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:46:35.323  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:46:35.323  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 16:46:35.324  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:46:35.324  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:46:35.324  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:46:35.324  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:46:35.324  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:46:35.342  3274  3331 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 16:46:35.342  3274  3331 I jxcore-log: 
,03-24 16:46:35.344  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:46:35.344   822  1326 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:46:35.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:46:35.372  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 16:46:35.372  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:46:35.375  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 16:46:35.375  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 16:46:35.375  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 16:46:35.375  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:46:35.375  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:46:35.375  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:46:35.376  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:46:35.376  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:46:35.377  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:46:35.377  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:46:35.377  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:46:35.378  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:46:35.378  3274  3331 I jxcore-log: 
03-24 16:46:35.379  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:46:35.379  3274  3331 I jxcore-log: 
03-24 16:46:35.379  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:46:35.379  3274  3331 I jxcore-log: 
,03-24 16:46:35.384  3274  3331 I jxcore-log: ok 104 error should be null
03-24 16:46:35.384  3274  3331 I jxcore-log: ,
,03-24 16:46:35.385  3274  3331 I jxcore-log: ok 105 error should be null
03-24 16:46:35.385  3274  3331 I jxcore-log: 
,03-24 16:46:35.391  3274  3331 I jxcore-log: # setup
03-24 16:46:35.391  3274  3331 I jxcore-log: 
,03-24 16:46:35.503  3385  3735 V GoogleAuthProtoRequest: [341] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 16:46:35.560  1349  1597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 16:46:35.560  1349  1597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:35.560  1349  1597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:35.560  1349  1597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:35.565  1349  1597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:35.583  3385  3735 W ExperimentUpdateService: [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 16:46:35.584  3385  3735 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 16:46:35.616  3274  3331 I jxcore-log: # 27. should be able to call #stopAdvertisingAndListening many times
03-24 16:46:35.616  3274  3331 I jxcore-log: 
,03-24 16:46:35.802  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:35.802  3274  3331 I jxcore-log: 
,03-24 16:46:35.805  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 54965
03-24 16:46:35.805  3274  3331 I jxcore-log: 
,03-24 16:46:35.809  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:46:35.809  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:46:35.809  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:35.813  3274  3331 I jxcore-log: ok 106 error should be null
03-24 16:46:35.813  3274  3331 I jxcore-log: 
,03-24 16:46:35.813  3274  3331 I jxcore-log: ok 107 error should be null
03-24 16:46:35.813  3274  3331 I jxcore-log: 
,03-24 16:46:35.816  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:46:35.816  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:46:35.816  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:35.818  3274  3331 I jxcore-log: ok 108 error should be null
03-24 16:46:35.818  3274  3331 I jxcore-log: 
03-24 16:46:35.819  3274  3331 I jxcore-log: ok 109 error should be null
03-24 16:46:35.819  3274  3331 I jxcore-log: 
,03-24 16:46:35.825  3274  3331 I jxcore-log: # teardown
03-24 16:46:35.825  3274  3331 I jxcore-log: 
,03-24 16:46:37.034  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:46:37.034  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
03-24 16:46:37.034  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:46:37.035  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:46:37.035  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:46:37.035  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:37.041  3274  3331 I jxcore-log: ok 110 error should be null
,03-24 16:46:37.041  3274  3331 I jxcore-log: 
03-24 16:46:37.042  3274  3331 I jxcore-log: ok 111 error should be null
03-24 16:46:37.042  3274  3331 I jxcore-log: 
,03-24 16:46:37.047  3274  3331 I jxcore-log: # setup
03-24 16:46:37.047  3274  3331 I jxcore-log: 
,03-24 16:46:37.946  3274  3331 I jxcore-log: # 28. #start should fail if called twice in a row
,03-24 16:46:37.946  3274  3331 I jxcore-log: 
,03-24 16:46:38.158  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 16:46:38.158  3274  3331 I jxcore-log: 
03-24 16:46:38.160  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 46533
03-24 16:46:38.160  3274  3331 I jxcore-log: 
,03-24 16:46:38.164  3274  3331 I jxcore-log: ok 112 first call should succeed
,03-24 16:46:38.164  3274  3331 I jxcore-log: 
03-24 16:46:38.164  3274  3331 I jxcore-log: ok 113 first call should succeed
03-24 16:46:38.164  3274  3331 I jxcore-log: 
,03-24 16:46:38.167  3274  3331 I jxcore-log: ok 114 specific error should be returned
03-24 16:46:38.167  3274  3331 I jxcore-log: 
,03-24 16:46:38.169  3274  3331 I jxcore-log: # teardown
03-24 16:46:38.169  3274  3331 I jxcore-log: 
,03-24 16:46:39.962  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:46:40.664  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:46:40.664  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:46:40.664  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:46:40.666  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:46:40.666  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:46:40.666  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:46:40.671  3274  3331 I jxcore-log: ok 115 error should be null
03-24 16:46:40.671  3274  3331 I jxcore-log: 
,03-24 16:46:40.672  3274  3331 I jxcore-log: ok 116 error should be null
03-24 16:46:40.672  3274  3331 I jxcore-log: 
03-24 16:46:40.676  3274  3331 I jxcore-log: # setup
03-24 16:46:40.676  3274  3331 I jxcore-log: 
,03-24 16:46:42.051  3274  3331 I jxcore-log: # 29. does not emit duplicate discoveryAdvertisingStateUpdate
03-24 16:46:42.051  3274  3331 I jxcore-log: 
,03-24 16:46:42.454  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:46:42.454  3274  3331 I jxcore-log: 
,03-24 16:46:42.456  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 36721
03-24 16:46:42.456  3274  3331 I jxcore-log: 
,03-24 16:46:42.467  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 34822, start advertisements: false
03-24 16:46:42.467  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:46:42.467  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:46:42.467  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 16:46:42.472  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:46:42.472  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:46:42.472  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:46:42.478  2150  2957 D BtGatt.GattService: registerClient() - UUID=7ba21768-ec2b-44c9-a160-e10b709432c3
,03-24 16:46:42.479  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=7ba21768-ec2b-44c9-a160-e10b709432c3, clientIf=5
03-24 16:46:42.480  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:46:42.480  2150  2166 D BtGatt.GattService: start scan with filters
03-24 16:46:42.482  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:46:42.482  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:46:42.482  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:46:42.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:46:42.483  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:46:42.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:46:42.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:46:42.483  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:46:42.484   822  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:46:42.490  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 16:46:42.490  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:46:42.493  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 16:46:42.493  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:42.493  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:46:42.494  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:46:42.495  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:46:42.496  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:46:42.496  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:46:42.496  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:46:42.496  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:46:42.497  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:46:42.499  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:46:42.499  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:46:42.502  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:46:42.502  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:46:42.505  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:46:42.505  3274  3331 I jxcore-log: 
,03-24 16:46:42.506  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 16:46:42.506  3274  3331 I jxcore-log: 
,03-24 16:46:42.518  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 36721, start advertisements: true
,03-24 16:46:42.518  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:46:42.518  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:46:42.518  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:46:42.523  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 16:46:42.523  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,03-24 16:46:42.523  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:46:42.523  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:46:42.523  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:46:42.523  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:46:42.524  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:46:42.524  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:46:42.528  2150  2166 D BtGatt.GattService: registerClient() - UUID=c883c209-a2dd-4748-a582-cec21ee30914
03-24 16:46:42.529  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=c883c209-a2dd-4748-a582-cec21ee30914, clientIf=6
03-24 16:46:42.529  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:46:42.532  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:46:42.535  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:46:42.538  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:46:42.541  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:46:42.542  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:46:42.542  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:46:42.542  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:46:42.542  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:46:42.542  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:46:42.542  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:46:42.542   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:46:42.542  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 16:46:42.549  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-24 16:46:42.549  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:46:42.550  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:46:42.551  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,03-24 16:46:42.551  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 16:46:42.552  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 16:46:42.552  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 16:46:42.552  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:46:42.552  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 16:46:42.552  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:46:42.552  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:46:42.552  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:46:42.553  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:46:42.555   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 16:46:42.558  3274  3738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:46:42.561  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:46:42.561  3274  3331 I jxcore-log: 
03-24 16:46:42.562  3274  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 16:46:42.567  3274  3331 I jxcore-log: ok 117 called only once
03-24 16:46:42.567  3274  3331 I jxcore-log: 
,03-24 16:46:42.567  3274  3331 I jxcore-log: ok 118 discovery state matches
03-24 16:46:42.567  3274  3331 I jxcore-log: 
,03-24 16:46:42.568  3274  3331 I jxcore-log: ok 119 advertising state matches
03-24 16:46:42.568  3274  3331 I jxcore-log: 
,03-24 16:46:42.577  3274  3331 I jxcore-log: # teardown
03-24 16:46:42.577  3274  3331 I jxcore-log: 
,03-24 16:46:43.182  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:46:43.182  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 16:46:43.182  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:46:43.182  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
03-24 16:46:43.182  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:46:43.182  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:46:43.183  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,03-24 16:46:43.183  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:46:43.183  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:46:43.183  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:46:43.183  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:46:43.183  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:46:43.183  3274  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:46:43.183  3274  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
,03-24 16:46:43.184  3274  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 16:46:43.185  2150  2167 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:46:43.187  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:46:43.187  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:46:43.187  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:46:43.187  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 16:46:43.188  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:46:43.188  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:43.188  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:46:43.188  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 16:46:43.188  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:46:43.188  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:46:43.188  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 16:46:43.191  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:46:43.191  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:46:43.191  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:43.192  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:46:43.192  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:46:43.195  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:46:43.195  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:46:43.196  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:46:43.196  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:46:43.197  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:46:43.197  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:46:43.197  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 16:46:43.197  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:46:43.197  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:46:43.197  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:46:43.197  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:46:43.197  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:46:43.198  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 16:46:43.198  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:46:43.198  2150  2212 D BtGatt.GattService: current time is 218787508457
03-24 16:46:43.198  2150  2212 D BtGatt.GattService: Batch record : [-73, 71, 12, 87, 77, 93, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 16:46:43.198  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:46:43.198  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:46:43.198  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:46:43.199  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
03-24 16:46:43.199  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:46:43.199  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:46:43.208  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 16:46:43.209   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:46:43.220  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:46:43.221  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:46:43.221  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:46:43.221  3274  3331 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
03-24 16:46:43.221  3274  3331 I jxcore-log: 
03-24 16:46:43.222  3274  3331 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 16:46:43.222  3274  3331 I jxcore-log: 
,03-24 16:46:43.224  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 16:46:43.224  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:46:43.225  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:46:43.225  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:46:43.225  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:46:43.225  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:46:43.225  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:46:43.225  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 16:46:43.226  3274  3331 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 16:46:43.226  3274  3331 I jxcore-log: 
03-24 16:46:43.229  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:46:43.229  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:46:43.229  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:46:43.230  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:46:43.230  3274  3331 I jxcore-log: 
,03-24 16:46:43.231  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:46:43.231  3274  3331 I jxcore-log: 
,03-24 16:46:43.232  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:46:43.232  3274  3331 I jxcore-log: 
,03-24 16:46:43.236  3274  3331 I jxcore-log: ok 120 error should be null
03-24 16:46:43.236  3274  3331 I jxcore-log: 
,03-24 16:46:43.237  3274  3331 I jxcore-log: ok 121 error should be null
03-24 16:46:43.237  3274  3331 I jxcore-log: 
,03-24 16:46:43.243  3274  3331 I jxcore-log: # setup,
03-24 16:46:43.243  3274  3331 I jxcore-log: 
,03-24 16:46:44.622  3274  3331 I jxcore-log: # 30. does not send duplicate availability changes
03-24 16:46:44.622  3274  3331 I jxcore-log: 
,03-24 16:46:45.888  3274  3331 I jxcore-log: ok 122 should be called once,
03-24 16:46:45.888  3274  3331 I jxcore-log: 
03-24 16:46:45.889  3274  3331 I jxcore-log: ok 123 should not have been called more than once
03-24 16:46:45.889  3274  3331 I jxcore-log: 
03-24 16:46:45.892  3274  3331 I jxcore-log: # teardown
03-24 16:46:45.892  3274  3331 I jxcore-log: 
,03-24 16:46:47.283  3274  3331 I jxcore-log: ok 124 error should be null
03-24 16:46:47.283  3274  3331 I jxcore-log: 
03-24 16:46:47.284  3274  3331 I jxcore-log: ok 125 error should be null
03-24 16:46:47.284  3274  3331 I jxcore-log: 
03-24 16:46:47.286  3274  3331 I jxcore-log: # setup
03-24 16:46:47.286  3274  3331 I jxcore-log: 
,03-24 16:46:48.411  1236  1479 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-24 16:46:48.411  1236  1479 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-24 16:46:48.454  1349  1349 I ConfigService: onCreate
,03-24 16:46:48.604  3274  3331 I jxcore-log: # 31. can get the network status
03-24 16:46:48.604  3274  3331 I jxcore-log: 
,03-24 16:46:48.830  3274  3331 I jxcore-log: ok 126 network status should have certain non-empty properties
,03-24 16:46:48.830  3274  3331 I jxcore-log: 
,03-24 16:46:48.834  3274  3331 I jxcore-log: # teardown
,03-24 16:46:48.834  3274  3331 I jxcore-log: 
,03-24 16:46:50.815  3274  3331 I jxcore-log: ok 127 error should be null
03-24 16:46:50.815  3274  3331 I jxcore-log: 
,03-24 16:46:50.816  3274  3331 I jxcore-log: ok 128 error should be null
03-24 16:46:50.816  3274  3331 I jxcore-log: 
,03-24 16:46:50.824  3274  3331 I jxcore-log: # setup
03-24 16:46:50.824  3274  3331 I jxcore-log: 
,03-24 16:46:52.656  3462  3741 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 16:46:52.698  3462  3744 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 16:46:52.740  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-24 16:46:52.740  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:52.740  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:52.740  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
03-24 16:46:52.743  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:52.761  1349  1597 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
03-24 16:46:52.762  1349  1597 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 16:46:52.763  1349  1597 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:52.763  1349  1597 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:52.770  1349  1597 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:52.797  3093  3743 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 16:46:52.797  3093  3743 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at blb.a(PG:3937)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at czp.a(PG:18188)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at czp.a(PG:9087)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:46:52.797  3093  3743 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	... 12 more
03-24 16:46:52.797  3093  3743 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at fal.a(PG:38)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:46:52.797  3093  3743 E HttpOperation: 	... 14 more
,03-24 16:46:52.850  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 16:46:52.851  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:52.851  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:52.851  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:52.858  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 16:46:52.877  3462  3744 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 16:46:52.878  3462  3741 E BooksSync: Soft error
03-24 16:46:52.878  3462  3741 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:46:52.878  3462  3741 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 16:46:52.878  3462  3741 E BooksSync: Sync error
03-24 16:46:52.878  3462  3741 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:46:52.878  3462  3741 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 16:46:52.878  3462  3741 I BooksSync: Finished books sync
,03-24 16:46:52.883   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 200142, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:46:52.912  3502  3748 V KeepSync: Connecting to GoogleApiClient
,03-24 16:46:52.929  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 16:46:52.930  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:52.930  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:52.930  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:52.934  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:52.955  3093  3747 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 16:46:52.955  3093  3747 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at blb.a(PG:3937)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at czp.a(PG:18188)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at czp.a(PG:9081)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:46:52.955  3093  3747 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	... 12 more
03-24 16:46:52.955  3093  3747 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at fal.a(PG:38)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:46:52.955  3093  3747 E HttpOperation: 	... 14 more
,03-24 16:46:52.965  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 16:46:52.965  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:52.965  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:52.965  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:52.968  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: Handling authorization failure
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 16:46:52.986  1775  3749 E ClientConnectionOperation: 	... 7 more
,03-24 16:46:52.988  3502  3748 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 16:46:52.993  3502  3748 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 16:46:53.001  3502  3748 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 16:46:53.001  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-24 16:46:53.002  3502  3748 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-24 16:46:53.002  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:53.002  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:53.002  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:53.006  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 16:46:53.021  3093  3747 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 16:46:53.021  3093  3747 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at hec.a(PG:42)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at hee.a(PG:102)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at czr.a(PG:65)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at kka.a(PG:108)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at czp.a(PG:19176)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at czp.a(PG:9081)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:46:53.021  3093  3747 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	... 15 more
03-24 16:46:53.021  3093  3747 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at fal.a(PG:38)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:46:53.021  3093  3747 E HttpOperation: 	... 17 more
,03-24 16:46:53.022  3093  3747 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 16:46:53.022  3093  3747 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at hec.a(PG:42)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at hee.a(PG:102)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at czr.a(PG:65)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at kka.a(PG:108)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	... 15 more
03-24 16:46:53.022  3093  3747 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at fal.a(PG:38)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 16:46:53.022  3093  3747 E ExperimentLoader: 	... 17 more,
,03-24 16:46:53.084  1349  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 16:46:53.084  1349  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:46:53.084  1349  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:46:53.084  1349  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:46:53.090  1349  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:46:53.182   822  1154 I art     : Explicit concurrent mark sweep GC freed 30461(1342KB) AllocSpace objects, 5(362KB) LOS objects, 31% free, 34MB/50MB, paused 2.378ms total 85.757ms
,03-24 16:46:53.200   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 168669, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:46:53.249  3502  3748 E KeepSync: IOException
03-24 16:46:53.249  3502  3748 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 16:46:53.249  3502  3748 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 16:46:53.249  3502  3748 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 16:46:53.249  3502  3748 E KeepSync: 	... 10 more
03-24 16:46:53.249  3502  3748 W KeepSync: Sync result 2
,03-24 16:46:53.256   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 200958, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:46:53.511  1349  1349 I ConfigService: onDestroy
,03-24 16:46:54.011  3274  3331 I jxcore-log: # 32. wifi peer is marked unavailable if announcements stop
03-24 16:46:54.011  3274  3331 I jxcore-log: 
,03-24 16:46:57.016  3274  3331 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
03-24 16:46:57.016  3274  3331 I jxcore-log: 
,03-24 16:46:57.043  3274  3331 I jxcore-log: ok 129 host address should match
,03-24 16:46:57.043  3274  3331 I jxcore-log: 
03-24 16:46:57.043  3274  3331 I jxcore-log: ok 130 port should match
03-24 16:46:57.043  3274  3331 I jxcore-log: 
,03-24 16:46:59.029  3274  3331 I jxcore-log: ok 131 host address should be null
03-24 16:46:59.029  3274  3331 I jxcore-log: 
,03-24 16:46:59.031  3274  3331 I jxcore-log: ok 132 port should should be null
03-24 16:46:59.031  3274  3331 I jxcore-log: 
,03-24 16:46:59.053  3274  3331 I jxcore-log: # teardown
03-24 16:46:59.053  3274  3331 I jxcore-log: 
,03-24 16:47:00.373  3274  3331 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
03-24 16:47:00.373  3274  3331 I jxcore-log: 
,03-24 16:47:00.376  3274  3331 I jxcore-log: ok 133 error should be null
03-24 16:47:00.376  3274  3331 I jxcore-log: 
,03-24 16:47:00.376  3274  3331 I jxcore-log: ok 134 error should be null
03-24 16:47:00.376  3274  3331 I jxcore-log: 
,03-24 16:47:00.378  3274  3331 I jxcore-log: # setup
03-24 16:47:00.378  3274  3331 I jxcore-log: 
,03-24 16:47:01.618  3274  3331 I jxcore-log: # 33. Can call start/stopListeningForAdvertisements
03-24 16:47:01.618  3274  3331 I jxcore-log: 
,03-24 16:47:03.138  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 36721, start advertisements: false
03-24 16:47:03.138  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:47:03.138  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:47:03.138  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 16:47:03.146  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:47:03.146  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:47:03.146  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:47:03.154  2150  2167 D BtGatt.GattService: registerClient() - UUID=8cd73bd1-1ec3-4a5d-859f-ddb3da5464bb,
03-24 16:47:03.155  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=8cd73bd1-1ec3-4a5d-859f-ddb3da5464bb, clientIf=5
,03-24 16:47:03.156  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:47:03.156  2150  2957 D BtGatt.GattService: start scan with filters
,03-24 16:47:03.158  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:47:03.158  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:47:03.158  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:47:03.158  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:47:03.158  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:47:03.159  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:47:03.159  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:47:03.159  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:47:03.160   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:47:03.173  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,03-24 16:47:03.173  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:03.174  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:47:03.174  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:47:03.174  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:47:03.174  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:47:03.174  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:47:03.175  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:47:03.176  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:47:03.176  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:03.176  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:47:03.177  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:47:03.179  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:47:03.180  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:03.180  3274  3331 I jxcore-log: ok 135 Can call startListeningForAdvertisements without error
03-24 16:47:03.180  3274  3331 I jxcore-log: 
,03-24 16:47:03.182  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:47:03.182  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:03.183  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:47:03.183  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:47:03.183  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 16:47:03.183  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 16:47:03.187  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
03-24 16:47:03.189  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:47:03.190  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:47:03.190  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:03.190  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:47:03.191  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 16:47:03.191  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:47:03.191  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:47:03.191  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,03-24 16:47:03.191  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 16:47:03.192  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:47:03.192  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:47:03.192  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:47:03.192  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:47:03.195  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:47:03.195  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:03.195  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:47:03.195  3274  3331 I jxcore-log: 
03-24 16:47:03.195  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:47:03.197  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:47:03.197  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:03.202  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:47:03.202  3274  3331 I jxcore-log: 
,03-24 16:47:03.206  3274  3331 I jxcore-log: ok 136 Can call stopListeningForAdvertisements without error
03-24 16:47:03.206  3274  3331 I jxcore-log: 
,03-24 16:47:03.214  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:47:03.214  3274  3331 I jxcore-log: 
,03-24 16:47:03.216  3274  3331 I jxcore-log: # teardown
03-24 16:47:03.216  3274  3331 I jxcore-log: 
,03-24 16:47:05.788  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:47:05.789  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:47:05.789  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:47:05.794  3274  3331 I jxcore-log: ok 137 Should be able to call stopListeningForAdvertisments in teardown
03-24 16:47:05.794  3274  3331 I jxcore-log: ,
03-24 16:47:05.795  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:47:05.795  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:47:05.795  3274  3331 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 16:47:05.795  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:47:05.795  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:47:05.795  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:47:05.795  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:47:05.795  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
03-24 16:47:05.797  3274  3331 D BluetoothLeScanner: could not find callback wrapper
03-24 16:47:05.797  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:47:05.798  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:47:05.798  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 16:47:05.799  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-24 16:47:05.800  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 16:47:05.801  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:47:05.801  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:47:05.801  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:47:05.801  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,03-24 16:47:05.811  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,03-24 16:47:05.811   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:47:05.822  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 16:47:05.824  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:47:05.824  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:47:05.830  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 16:47:05.830  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:47:05.830  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:47:05.833  3274  3331 I jxcore-log: ok 138 Should be able to call stopAdvertisingAndListening in teardown
,03-24 16:47:05.833  3274  3331 I jxcore-log: 
,03-24 16:47:05.845  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:47:05.845  3274  3331 I jxcore-log: ,
03-24 16:47:05.847  3274  3331 I jxcore-log: # setup
03-24 16:47:05.847  3274  3331 I jxcore-log: 
,03-24 16:47:08.285  3274  3331 I jxcore-log: # 34. Calling startListeningForAdvertisements twice is NOT an error
03-24 16:47:08.285  3274  3331 I jxcore-log: 
,03-24 16:47:09.706  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 36721, start advertisements: false
03-24 16:47:09.706  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:47:09.706  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 16:47:09.706  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 16:47:09.711  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:47:09.711  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:47:09.711  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:47:09.718  2150  2167 D BtGatt.GattService: registerClient() - UUID=68723fa3-3084-4770-be09-9bba625bbc39
,03-24 16:47:09.718  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=68723fa3-3084-4770-be09-9bba625bbc39, clientIf=5
03-24 16:47:09.719  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:47:09.719  2150  2957 D BtGatt.GattService: start scan with filters
,03-24 16:47:09.721  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:47:09.721  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:47:09.721  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:47:09.721  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:47:09.722  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:47:09.722  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:47:09.722  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:47:09.722  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:47:09.722   822  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:47:09.725  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:47:09.725  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:47:09.726  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 16:47:09.726  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:47:09.726  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:47:09.726  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:47:09.728  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:47:09.728  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:09.730  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:47:09.730  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:09.731  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:47:09.731  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:47:09.731  3274  3331 I jxcore-log: ok 139 Can call startListeningForAdvertisements without error,
03-24 16:47:09.731  3274  3331 I jxcore-log: 
03-24 16:47:09.733  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:47:09.733  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:09.735  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:47:09.735  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:09.739  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 36721, start advertisements: false
,03-24 16:47:09.739  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:47:09.739  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:47:09.739  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:47:09.739  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:47:09.743  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:47:09.743  3274  3331 I jxcore-log: 
,03-24 16:47:09.746  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:47:09.746  3274  3331 I jxcore-log: 
,03-24 16:47:09.749  3274  3331 I jxcore-log: ok 140 Can call startListeningForAdvertisements twice without error
03-24 16:47:09.749  3274  3331 I jxcore-log: 
,03-24 16:47:09.763  3274  3331 I jxcore-log: # teardown
03-24 16:47:09.763  3274  3331 I jxcore-log: 
,03-24 16:47:10.746  2150  2150 D BtGatt.ScanManager: awakened up at time 246335,
03-24 16:47:10.748  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:47:10.755  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 16:47:10.755  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:11.772  2150  2150 D BtGatt.ScanManager: awakened up at time 247361
,03-24 16:47:11.773  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:47:11.779  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 16:47:11.779  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:12.317  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:47:12.317  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:47:12.318  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 16:47:12.318  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 16:47:12.324  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:47:12.328  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 16:47:12.328  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:47:12.328  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:12.329  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:47:12.328  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 16:47:12.329  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:47:12.329  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:47:12.330  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 16:47:12.330  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 16:47:12.330  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:47:12.331  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:47:12.331  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:47:12.331  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:47:12.332  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:47:12.332  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:12.332  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:47:12.334  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:47:12.334  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:12.336  3274  3331 I jxcore-log: ok 141 Should be able to call stopListeningForAdvertisments in teardown
03-24 16:47:12.336  3274  3331 I jxcore-log: 
,03-24 16:47:12.338  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:47:12.338  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:47:12.338  3274  3331 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 16:47:12.338  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 16:47:12.338  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:47:12.338  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:47:12.338  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:47:12.339  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:47:12.341  3274  3331 D BluetoothLeScanner: could not find callback wrapper
,03-24 16:47:12.341  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:47:12.342  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:47:12.342  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 16:47:12.342  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:47:12.343  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:47:12.343  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:47:12.344  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:47:12.344  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:47:12.344  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:47:12.346  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:47:12.346  3274  3331 I jxcore-log: 
,03-24 16:47:12.363  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 16:47:12.363   822  1326 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:47:12.367  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:47:12.368  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:47:12.368  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:47:12.371  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:47:12.371  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:47:12.371  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:47:12.372  3274  3331 I jxcore-log: ok 142 Should be able to call stopAdvertisingAndListening in teardown
03-24 16:47:12.372  3274  3331 I jxcore-log: 
03-24 16:47:12.378  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:47:12.378  3274  3331 I jxcore-log: 
,03-24 16:47:12.381  3274  3331 I jxcore-log: # setup
03-24 16:47:12.381  3274  3331 I jxcore-log: 
,03-24 16:47:13.872  3274  3331 I jxcore-log: # 35. Can call start/stopUpdateAdvertisingAndListening
03-24 16:47:13.872  3274  3331 I jxcore-log: 
,03-24 16:47:16.683  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 16:47:16.683  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:47:16.684  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 16:47:16.684  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:47:16.688  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 16:47:16.688  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:47:16.688  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:47:16.688  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:47:16.692  2150  2166 D BtGatt.GattService: registerClient() - UUID=5dff1ba1-156e-4268-a268-2be1dc919a8a
03-24 16:47:16.692  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=5dff1ba1-156e-4268-a268-2be1dc919a8a, clientIf=5
,03-24 16:47:16.693  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:47:16.694  2150  2167 D BtGatt.GattService: start scan with filters
,03-24 16:47:16.696  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:47:16.697  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:47:16.698  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:47:16.698  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:47:16.699  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 16:47:16.699  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:47:16.701  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:47:16.701  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 16:47:16.702  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:47:16.702  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 16:47:16.702  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:47:16.702  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:47:16.702  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 16:47:16.703  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:47:16.703  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:16.705  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:47:16.705  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:16.706  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:47:16.706  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:47:16.708  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:47:16.708  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:16.709  2150  2957 D BtGatt.GattService: registerClient() - UUID=3a0c8d9b-a727-4c3d-8f87-c3a8db39d795,
03-24 16:47:16.709  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=3a0c8d9b-a727-4c3d-8f87-c3a8db39d795, clientIf=6
03-24 16:47:16.710  3274  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:47:16.711  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
03-24 16:47:16.711  2150  2221 D BtGatt.AdvertiseManager: message : 0
03-24 16:47:16.711  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:16.714  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:47:16.724  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 16:47:16.726  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 16:47:16.727  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:47:16.727  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 16:47:16.727   822  1326 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:47:16.730  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:47:16.730  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:47:16.730  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
03-24 16:47:16.730  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:47:16.731  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 16:47:16.731  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 16:47:16.731  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
03-24 16:47:16.731  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 16:47:16.731  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:47:16.732  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 16:47:16.732  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:47:16.732  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
03-24 16:47:16.732  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:47:16.732  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:47:16.732  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true,
03-24 16:47:16.732  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:47:16.732  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:47:16.732  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:47:16.732  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:47:16.732  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:47:16.732  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:47:16.734   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:47:16.736  3274  3757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:47:16.738  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:47:16.738  3274  3331 I jxcore-log: 
03-24 16:47:16.739  3274  3331 I jxcore-log: ok 143 Can call startUpdateAdvertisingAndListening without error
03-24 16:47:16.739  3274  3331 I jxcore-log: ,
,03-24 16:47:16.739  3274  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 16:47:16.740  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:47:16.740  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 16:47:16.740  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,03-24 16:47:16.740  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 16:47:16.740  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:47:16.740  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:47:16.741  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:47:16.741  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:47:16.741  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:47:16.741  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:47:16.741  3274  3757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:47:16.741  3274  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:47:16.741  3274  3757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
03-24 16:47:16.741  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:47:16.741  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:47:16.742  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:47:16.743  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:47:16.744  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:47:16.744  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:47:16.745  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:47:16.745  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:47:16.745  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:47:16.745  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:47:16.745  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 16:47:16.745  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:47:16.745  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 16:47:16.745  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 16:47:16.747  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:47:16.747  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:47:16.747  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:47:16.748  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 16:47:16.748  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:47:16.749  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:47:16.750  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:47:16.751  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:47:16.751  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:47:16.754  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:47:16.754  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:47:16.754  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
03-24 16:47:16.754  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:47:16.754  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 16:47:16.754  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:47:16.754  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:47:16.754  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:47:16.754  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:47:16.756  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:47:16.756  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:47:16.756  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:47:16.756  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:47:16.756  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:47:16.760  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:47:16.761   822  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:47:16.763  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:47:16.763  3274  3331 I jxcore-log: 
,03-24 16:47:16.765  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 16:47:16.766  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:47:16.766  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 16:47:16.766  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:47:16.766  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:47:16.767  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:47:16.767  3274  3331 I jxcore-log: 
03-24 16:47:16.770  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:47:16.770  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:47:16.770  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:47:16.770  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:47:16.770  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:47:16.770  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,03-24 16:47:16.772  3274  3331 I jxcore-log: ok 144 Can call stopAdvertisingAndListening without error
03-24 16:47:16.772  3274  3331 I jxcore-log: 
,03-24 16:47:16.778  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:47:16.778  3274  3331 I jxcore-log: 
,03-24 16:47:16.779  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:47:16.779  3274  3331 I jxcore-log: 
,03-24 16:47:16.781  3274  3331 I jxcore-log: # teardown
03-24 16:47:16.781  3274  3331 I jxcore-log: 
,03-24 16:47:16.784  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:47:16.784  3274  3331 I jxcore-log: 
,03-24 16:47:22.643  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:47:22.643  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:47:22.643  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:47:22.654  3274  3331 I jxcore-log: ok 145 Should be able to call stopListeningForAdvertisments in teardown
03-24 16:47:22.654  3274  3331 I jxcore-log: 
,03-24 16:47:22.656  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:47:22.656  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:47:22.656  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:47:22.659  3274  3331 I jxcore-log: ok 146 Should be able to call stopAdvertisingAndListening in teardown
03-24 16:47:22.659  3274  3331 I jxcore-log: 
,03-24 16:47:22.666  3274  3331 I jxcore-log: # setup
03-24 16:47:22.666  3274  3331 I jxcore-log: 
,03-24 16:47:28.514  3274  3331 I jxcore-log: # 36. Calling startUpdateAdvertisingAndListening twice is NOT an error
03-24 16:47:28.514  3274  3331 I jxcore-log: 
,03-24 16:47:35.664  3385  3760 V GoogleAuthProtoRequest: [342] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 16:47:35.774  1349  1349 I art     : Explicit concurrent mark sweep GC freed 71630(4MB) AllocSpace objects, 12(1081KB) LOS objects, 36% free, 28MB/44MB, paused 1.854ms total 59.607ms
,03-24 16:47:35.804  1349  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 16:47:35.804  1349  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:47:35.804  1349  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:47:35.804  1349  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:47:35.818  1349  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:47:35.838  3385  3760 W ExperimentUpdateService: [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 16:47:35.839  3385  3760 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 16:47:52.939  1349  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 16:47:52.939  1349  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:47:52.939  1349  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 16:47:52.939  1349  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:47:52.949  1349  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:47:52.981  3093  3765 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 16:47:52.981  3093  3765 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at blb.a(PG:3937)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at czp.a(PG:18188)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at czp.a(PG:9081)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:47:52.981  3093  3765 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	... 12 more
03-24 16:47:52.981  3093  3765 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at fal.a(PG:38)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:47:52.981  3093  3765 E HttpOperation: 	... 14 more
,03-24 16:47:53.048  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 16:47:53.049  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:47:53.049  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:47:53.049  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:47:53.057  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:47:53.082  3093  3765 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 16:47:53.082  3093  3765 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at hec.a(PG:42)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at hee.a(PG:102)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at czr.a(PG:65)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at kka.a(PG:108)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at czp.a(PG:19176)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at czp.a(PG:9081)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:47:53.082  3093  3765 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	... 15 more
03-24 16:47:53.082  3093  3765 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at fal.a(PG:38)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:47:53.082  3093  3765 E HttpOperation: 	... 17 more
,03-24 16:47:53.083  3093  3765 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-24 16:47:53.083  3093  3765 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at hec.a(PG:42)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at hee.a(PG:102)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at czr.a(PG:65)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at kka.a(PG:108)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	... 15 more
03-24 16:47:53.083  3093  3765 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at fal.a(PG:38)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 16:47:53.083  3093  3765 E ExperimentLoader: 	... 17 more
,03-24 16:47:53.227   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 259406, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:48:00.379  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
03-24 16:48:00.380  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:48:00.380  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:00.380  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:48:00.388  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 16:48:00.389  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:00.389  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:00.389  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:00.399  2150  2167 D BtGatt.GattService: registerClient() - UUID=1b18efb1-ab2f-429e-9f6c-75b3d961ac05
03-24 16:48:00.400  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=1b18efb1-ab2f-429e-9f6c-75b3d961ac05, clientIf=5
,03-24 16:48:00.401  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:48:00.402  2150  2166 D BtGatt.GattService: start scan with filters
03-24 16:48:00.404  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:48:00.405  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:00.405  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:48:00.405  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 16:48:00.405  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:00.405  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:00.406  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 16:48:00.407  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:00.407  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:00.407  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:00.408  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:00.409  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:00.409  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:00.425  2150  2957 D BtGatt.GattService: registerClient() - UUID=65b307db-c23c-43e2-b97b-fa1b1764deaf
,03-24 16:48:00.425  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:00.426  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:00.426  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=65b307db-c23c-43e2-b97b-fa1b1764deaf, clientIf=6
03-24 16:48:00.427  3274  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:48:00.429  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:00.429  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:00.430  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:00.430  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 16:48:00.431  2150  2221 D BtGatt.AdvertiseManager: message : 0
03-24 16:48:00.434  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 16:48:00.434  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:00.436  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:00.437  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:00.442  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:00.447  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:00.451  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:00.452  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:00.452  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:00.453   822  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:00.462  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:48:00.462  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:48:00.462  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:00.462  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:00.464  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 16:48:00.465  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,03-24 16:48:00.465  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:48:00.465  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 16:48:00.465  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:00.465  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:00.466  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:00.467  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:00.467  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 16:48:00.467  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:48:00.467  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:48:00.467  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:00.468  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:00.468  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 16:48:00.468  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:00.469  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:48:00.469  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:00.470  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:00.470  3274  3331 I jxcore-log: 
,03-24 16:48:00.471   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:00.476  3274  3331 I jxcore-log: ok 147 Can call startUpdateAdvertisingAndListening without error
03-24 16:48:00.476  3274  3331 I jxcore-log: 
,03-24 16:48:00.486  3274  3768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 16:48:00.489  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 4243, start advertisements: true
,03-24 16:48:00.489  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:00.489  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:00.489  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:00.491  3274  3768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 16:48:00.491  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:48:00.495  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:00.495  3274  3331 I jxcore-log: 
,03-24 16:48:00.498  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:00.498  3274  3331 I jxcore-log: 
,03-24 16:48:00.501  3274  3331 I jxcore-log: ok 148 Can call startUpdateAdvertisingAndListening twice without error
03-24 16:48:00.501  3274  3331 I jxcore-log: 
,03-24 16:48:00.512  3274  3331 I jxcore-log: # teardown
03-24 16:48:00.512  3274  3331 I jxcore-log: 
,03-24 16:48:01.088  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:01.089  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 16:48:01.089  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 16:48:01.089  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 16:48:01.095  2150  2167 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:01.099  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
03-24 16:48:01.099  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:01.099  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:01.100  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:01.100  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 16:48:01.101  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:01.101  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:48:01.101  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 16:48:01.102  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:48:01.102  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 16:48:01.103  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:01.103  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 16:48:01.103  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:48:01.105  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:01.105  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:01.105  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:01.109  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 16:48:01.109  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:01.109  3274  3331 I jxcore-log: ok 149 Should be able to call stopListeningForAdvertisments in teardown
03-24 16:48:01.109  3274  3331 I jxcore-log: 
03-24 16:48:01.110  2150  2212 D BtGatt.GattService: current time is 296699249938
03-24 16:48:01.110  2150  2212 D BtGatt.GattService: Batch record : [-37, -41, 0, -127, 82, 85, 1, -128, -64, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -62, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 16:48:01.111  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:01.111  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:48:01.111  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:01.112  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,03-24 16:48:01.112  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:01.112  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 16:48:01.112  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:01.112  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:48:01.113  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:48:01.113  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 16:48:01.113  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:01.113  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:01.113  3274  3768 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:48:01.113  3274  3768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,03-24 16:48:01.113  3274  3768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 16:48:01.114  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:48:01.116  3274  3331 D BluetoothLeScanner: could not find callback wrapper
03-24 16:48:01.116  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:01.116  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 16:48:01.120  2150  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 16:48:01.121  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:48:01.124  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:01.124  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:01.125  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:01.125  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:01.126  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:01.126  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:48:01.126  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 16:48:01.126  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:48:01.126  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:48:01.126  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:48:01.127  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:48:01.128  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:01.128  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:48:01.128  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:01.128  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:01.128  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:48:01.132  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:01.132  3274  3331 I jxcore-log: 
,03-24 16:48:01.134  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 16:48:01.134   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:01.139  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
03-24 16:48:01.140  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,03-24 16:48:01.140  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 16:48:01.140  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:48:01.140  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:01.143  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:01.143  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:01.143  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:01.143  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:01.144  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:48:01.145  3274  3331 I jxcore-log: ok 150 Should be able to call stopAdvertisingAndListening in teardown
,03-24 16:48:01.145  3274  3331 I jxcore-log: 
,03-24 16:48:01.157  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 16:48:01.157  3274  3331 I jxcore-log: 
03-24 16:48:01.158  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 16:48:01.158  3274  3331 I jxcore-log: 
,03-24 16:48:01.162  3274  3331 I jxcore-log: # setup
,03-24 16:48:01.162  3274  3331 I jxcore-log: 
,03-24 16:48:01.296  3274  3331 I jxcore-log: # 37. peerAvailabilityChange is called
03-24 16:48:01.296  3274  3331 I jxcore-log: 
,03-24 16:48:01.813  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: true
,03-24 16:48:01.813  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:48:01.814  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 16:48:01.814  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:48:01.823  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 16:48:01.824  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:01.824  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:48:01.824  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:01.835  2150  2167 D BtGatt.GattService: registerClient() - UUID=76ba50ed-9125-4d38-99e8-4dc2164a6246
,03-24 16:48:01.836  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=76ba50ed-9125-4d38-99e8-4dc2164a6246, clientIf=5
03-24 16:48:01.837  3274  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:01.837  2150  2957 D BtGatt.GattService: start scan with filters
,03-24 16:48:01.839  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:01.840  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:01.841  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:01.841  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 16:48:01.844  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 16:48:01.844  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:01.846  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 16:48:01.846  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:01.847  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 16:48:01.847  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 16:48:01.847  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:01.848  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:01.848  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 16:48:01.852  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:01.852  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:01.854  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:01.855  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:01.855  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:01.855  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:48:01.859  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:01.859  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:01.862  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:01.862  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:01.862  2150  2166 D BtGatt.GattService: registerClient() - UUID=bd91062e-185a-4ccf-b8c2-81f52fc0ba0d
03-24 16:48:01.863  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=bd91062e-185a-4ccf-b8c2-81f52fc0ba0d, clientIf=6
03-24 16:48:01.863  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:01.866  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:01.871  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:01.875  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 16:48:01.878  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:01.879  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:01.879  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 16:48:01.879   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:01.887  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
03-24 16:48:01.887  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:48:01.887  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:01.887  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 16:48:01.889  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 16:48:01.889  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-24 16:48:01.889  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:48:01.889  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 16:48:01.890  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:01.890  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:01.890  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 16:48:01.891  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:01.891  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:48:01.891  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:48:01.891  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:48:01.891  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:01.891  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:01.891  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:01.891  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:01.892  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:48:01.892   822  2545 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:01.892  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:01.894  3274  3769 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:01.895  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:01.895  3274  3331 I jxcore-log: 
,03-24 16:48:01.898  3274  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 16:48:01.899  3274  3331 I jxcore-log: ok 151 Can call startUpdateAdvertisingAndListeningwithout error
03-24 16:48:01.899  3274  3331 I jxcore-log: 
,03-24 16:48:01.905  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 4242, start advertisements: false,
03-24 16:48:01.905  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started,
03-24 16:48:01.905  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 16:48:01.905  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:01.905  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:01.907  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:01.907  3274  3331 I jxcore-log: 
03-24 16:48:01.909  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:01.909  3274  3331 I jxcore-log: 
,03-24 16:48:01.922  3274  3331 I jxcore-log: ok 152 Can call startListeningForAdvertisements without error
,03-24 16:48:01.922  3274  3331 I jxcore-log: 
,03-24 16:48:02.870  2150  2150 D BtGatt.ScanManager: awakened up at time 298459
,03-24 16:48:02.872  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:02.883  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 16:48:02.883  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:02.883  2150  2212 D BtGatt.GattService: current time is 298472945093
03-24 16:48:02.884  2150  2212 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -56, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -56, 125, -46, -66, -22, 125, 1, -128, -71, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 16:48:02.884  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:02.885  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:02.893  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 16:48:02.894  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 16:48:02.895  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
,03-24 16:48:02.896  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
03-24 16:48:02.899  3274  3331 I jxcore-log: ok 153 peers must be an array
03-24 16:48:02.899  3274  3331 I jxcore-log: 
,03-24 16:48:02.901  3274  3331 I jxcore-log: ok 154 peers must not be zero-length
,03-24 16:48:02.901  3274  3331 I jxcore-log: 
03-24 16:48:02.902  3274  3331 I jxcore-log: ok 155 peer must have peerIdentifier
03-24 16:48:02.902  3274  3331 I jxcore-log: 
03-24 16:48:02.903  3274  3331 I jxcore-log: ok 156 peerIdentifier must be a string
03-24 16:48:02.903  3274  3331 I jxcore-log: 
,03-24 16:48:02.905  3274  3331 I jxcore-log: ok 157 peer must have peerAvailable
03-24 16:48:02.905  3274  3331 I jxcore-log: 
03-24 16:48:02.906  3274  3331 I jxcore-log: ok 158 peer must have pleaseConnect
03-24 16:48:02.906  3274  3331 I jxcore-log: ,
,03-24 16:48:02.921  3274  3331 I jxcore-log: # teardown
,03-24 16:48:02.921  3274  3331 I jxcore-log: 
,03-24 16:48:03.896  2150  2150 D BtGatt.ScanManager: awakened up at time 299485,
,03-24 16:48:03.898  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:03.907  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 16:48:03.907  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:03.908  2150  2212 D BtGatt.GattService: current time is 299497261864
03-24 16:48:03.908  2150  2212 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -56, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -56, 125, -46, -66, -22, 125, 1, -128, -71, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 16:48:03.909  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:03.909  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:03.913  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 16:48:03.914  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
,03-24 16:48:04.075  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:04.076  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 16:48:04.076  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 16:48:04.076  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 16:48:04.081  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:04.083  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:04.083  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:04.083  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:04.084  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:48:04.084  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 16:48:04.084  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:48:04.084  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 16:48:04.084  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:04.084  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 16:48:04.085  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:04.086  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:04.086  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:04.087  3274  3331 I jxcore-log: ok 159 Should be able to call stopListeningForAdvertisments in teardown
03-24 16:48:04.087  3274  3331 I jxcore-log: 
03-24 16:48:04.087  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:04.088  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:48:04.088  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 16:48:04.088  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:04.088  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 16:48:04.088  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:04.089  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:48:04.089  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:48:04.089  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,03-24 16:48:04.089  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:04.089  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:04.089  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:48:04.089  3274  3769 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:48:04.089  3274  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:48:04.089  3274  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 16:48:04.090  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:04.090  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:04.091  3274  3331 D BluetoothLeScanner: could not find callback wrapper
03-24 16:48:04.091  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:04.091  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 16:48:04.093  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:04.093  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:04.095  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:48:04.095  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 16:48:04.096  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:04.096  2150  2212 D BtGatt.GattService: current time is 299685541395
03-24 16:48:04.096  2150  2212 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -55, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, -56, 125, -46, -66, -22, 125, 1, -128, -72, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 16:48:04.097  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:04.098  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:04.100  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 16:48:04.100  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:04.101  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:04.102  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:04.102  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:04.102  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:48:04.102  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 16:48:04.102  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:48:04.102  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:04.102  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:48:04.102  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:48:04.103  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:04.103  3274  3331 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 16:48:04.103  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
03-24 16:48:04.103  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:04.103  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:04.103  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:48:04.104  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:04.104  3274  3331 I jxcore-log: 
03-24 16:48:04.113  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:48:04.113   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:04.118  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:48:04.119  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:04.119  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:04.122  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
03-24 16:48:04.122  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:48:04.122  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:48:04.122  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:04.122  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:04.122  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:48:04.122  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:48:04.123  3274  3331 I jxcore-log: ok 160 Should be able to call stopAdvertisingAndListening in teardown
03-24 16:48:04.123  3274  3331 I jxcore-log: 
,03-24 16:48:04.128  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:04.128  3274  3331 I jxcore-log: 
,03-24 16:48:04.129  3274  3331 I jxcore-log: # setup
03-24 16:48:04.129  3274  3331 I jxcore-log: 
,03-24 16:48:04.130  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:04.130  3274  3331 I jxcore-log: 
,03-24 16:48:06.547  3274  3331 I jxcore-log: # 38. Can connect to a remote peer
03-24 16:48:06.547  3274  3331 I jxcore-log: 
,03-24 16:48:07.146  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 33257, start advertisements: true
03-24 16:48:07.147  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:48:07.147  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,03-24 16:48:07.147  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
03-24 16:48:07.152  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser,
03-24 16:48:07.152  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:07.152  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:48:07.152  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:07.157  2150  2166 D BtGatt.GattService: registerClient() - UUID=52614296-d7a9-41e2-bbcc-c711a49f4938
03-24 16:48:07.157  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=52614296-d7a9-41e2-bbcc-c711a49f4938, clientIf=5
03-24 16:48:07.158  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:48:07.158  2150  2957 D BtGatt.GattService: start scan with filters
03-24 16:48:07.159  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:07.159  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:48:07.159  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:48:07.159  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 16:48:07.159  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:07.159  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:07.159  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:07.159  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:07.159  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:07.160  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 16:48:07.160  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:07.160  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:07.160  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:07.169  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 16:48:07.169  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:07.171  2150  2957 D BtGatt.GattService: registerClient() - UUID=c0ba00d9-ef41-4fed-8659-121a8a9c2882
03-24 16:48:07.172  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 16:48:07.172  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:07.172  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:48:07.172  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=c0ba00d9-ef41-4fed-8659-121a8a9c2882, clientIf=6
03-24 16:48:07.172  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 16:48:07.173  3274  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:07.174  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:07.176  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 16:48:07.176  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:07.178  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:07.178  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:07.191  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:07.194  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:07.197  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:07.197  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:07.198  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:07.198   822  1281 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:07.202  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:48:07.202  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:48:07.202  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:07.202  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:07.203  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 16:48:07.204  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 16:48:07.204  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:48:07.204  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
03-24 16:48:07.204  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:07.205  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:07.205  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:07.205  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 16:48:07.205  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 16:48:07.205  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:48:07.205  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:07.205  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:07.205  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:07.205  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:07.205  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:07.206  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:48:07.206  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:48:07.207   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:07.208  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:07.208  3274  3331 I jxcore-log: 
03-24 16:48:07.209  3274  3771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 16:48:07.212  3274  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 16:48:07.213  3274  3331 I jxcore-log: ok 161 Can call startUpdateAdvertisingAndListening without error
03-24 16:48:07.213  3274  3331 I jxcore-log: 
,03-24 16:48:07.217  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 33257, start advertisements: false,
03-24 16:48:07.217  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:07.217  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 16:48:07.217  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:07.217  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:48:07.228  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:07.228  3274  3331 I jxcore-log: 
,03-24 16:48:07.233  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:07.233  3274  3331 I jxcore-log: 
,03-24 16:48:07.235  3274  3331 I jxcore-log: ok 162 Can call startListeningForAdvertisements without error
03-24 16:48:07.235  3274  3331 I jxcore-log: 
,03-24 16:48:08.185  2150  2150 D BtGatt.ScanManager: awakened up at time 303774
,03-24 16:48:08.186  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:08.195  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,03-24 16:48:08.195  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:08.195  2150  2212 D BtGatt.GattService: current time is 303785123685
03-24 16:48:08.196  2150  2212 D BtGatt.GattService: Batch record : [-73, -72, 103, -47, -114, 97, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -57, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
,03-24 16:48:08.196  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:08.197  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:08.199  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 16:48:08.199  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
,03-24 16:48:08.199  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 16:48:08.200  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 16:48:08.208  3274  3331 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"pleaseConnect":false}]
03-24 16:48:08.208  3274  3331 I jxcore-log: 
,03-24 16:48:08.224  3274  3331 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,03-24 16:48:08.224  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:08.227  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address F8:95:C7:87:3C:51,
,03-24 16:48:08.228  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 16:48:08.228  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 16:48:08.228  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null F8:95:C7:87:3C:51
03-24 16:48:08.228  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address F8:95:C7:87:3C:51
03-24 16:48:08.228  3274  3331 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-24 16:48:08.229  3274  3773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 358)
03-24 16:48:08.229  3274  3773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:08.230  3274  3331 I jxcore-log: INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"pleaseConnect":false}]
03-24 16:48:08.230  3274  3331 I jxcore-log: 
03-24 16:48:08.233  2150  2167 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 16:48:08.926  2150  2223 W bt-btif : info:x10
03-24 16:48:08.927  2150  2212 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
03-24 16:48:08.927  2150  2212 E BluetoothRemoteDevices: aclStateChangeCallback: Device is NULL
,03-24 16:48:08.975  2150  2223 W bt-sdp  : process_service_search_attr_rsp
,03-24 16:48:09.514  2150  2212 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 16:48:09.523  2150  2212 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-24 16:48:09.524  2150  2212 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 16:48:09.531  2150  2213 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,03-24 16:48:09.531  2150  2213 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 16:48:09.611   822   856 I ActivityManager: Start proc 3775:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,03-24 16:48:09.696   822   860 D BluetoothManagerService: Message: 20
03-24 16:48:09.696   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e85b1d7:true
,03-24 16:48:09.918  2150  2212 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 16:48:09.919  2150  2213 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 16:48:09.923  2150  2213 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 16:48:09.955  2150  2213 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 16:48:10.938  2150  2223 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 16:48:10.938  2150  2223 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 16:48:10.938  2150  2223 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 16:48:10.939  3274  3773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 358)
,03-24 16:48:10.939  3274  3773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 358)
,03-24 16:48:10.943  3274  3773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 359)
,03-24 16:48:10.943  3274  3773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 359)
03-24 16:48:10.943  3274  3773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 358)
,03-24 16:48:10.946  3274  3795 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 359)
,03-24 16:48:11.285  3274  3795 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 359)
,03-24 16:48:11.289  3274  3795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51],
03-24 16:48:11.289  3274  3795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 358)
03-24 16:48:11.289  3274  3795 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 358)
,03-24 16:48:11.291  3274  3795 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 359)
,03-24 16:48:11.291  3274  3274 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 16:48:11.292  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:11.292  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 16:48:11.296  3274  3274 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,03-24 16:48:11.296  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
,03-24 16:48:11.297  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:11.297  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:11.297  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:11.297  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:48:11.297  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:11.297  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 16:48:11.303  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:11.304  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:11.312  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 16:48:11.312  2150  2212 D BtGatt.GattService: Client app is not null!
,03-24 16:48:11.315  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:11.316  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:48:11.316  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:11.317  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 16:48:11.317  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:11.317  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:11.317  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 16:48:11.318  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:11.318  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:11.318  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:11.330  2150  2166 D BtGatt.GattService: registerClient() - UUID=e2ed94ec-6be0-4483-b598-f96c5d72ef5f
,03-24 16:48:11.331  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=e2ed94ec-6be0-4483-b598-f96c5d72ef5f, clientIf=6
03-24 16:48:11.332  3274  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:11.335  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:11.342  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:11.347  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:11.351  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:11.352  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:11.355  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:11.357  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:11.358  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:11.358  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 16:48:11.358  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:11.359  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:11.359  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:11.359  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:11.359  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:11.359  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:11.359  2150  2222 D BtGatt.ScanManager: stopping BLe Batch,
03-24 16:48:11.361  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:11.362  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.362  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:11.365  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 16:48:11.365  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.365  2150  2212 D BtGatt.GattService: current time is 306954808319
03-24 16:48:11.366  2150  2212 D BtGatt.GattService: Batch record : [-73, -72, 103, -47, -114, 97, 1, -128, -72, 63, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 16:48:11.366  2150  2957 D BtGatt.GattService: registerClient() - UUID=c23c1e22-c3a7-4814-a84f-f562ee96db91
,03-24 16:48:11.367  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:11.368  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=c23c1e22-c3a7-4814-a84f-f562ee96db91, clientIf=5
,03-24 16:48:11.368  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:11.369  2150  2166 D BtGatt.GattService: start scan with filters
03-24 16:48:11.370  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:11.370  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:11.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1,
03-24 16:48:11.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:11.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:11.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:11.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 16:48:11.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:11.371  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:11.374  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:11.375  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:11.379  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
,03-24 16:48:11.379  2150  2212 D BtGatt.GattService: Client app is not null!,
03-24 16:48:11.381  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:11.382  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
03-24 16:48:11.382  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 16:48:11.382  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 16:48:11.382  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:11.383  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:11.383  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 16:48:11.383  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:11.383  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:11.383  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:11.383  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:11.385  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:11.385  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.386  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:11.386  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:11.386  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:11.386  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:48:11.388  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:11.388  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.389  2150  2167 D BtGatt.GattService: registerClient() - UUID=771778a1-5f88-4a5f-af1e-9f71a359ecb4
03-24 16:48:11.389  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:11.389  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.389  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=771778a1-5f88-4a5f-af1e-9f71a359ecb4, clientIf=6
03-24 16:48:11.389  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:11.391  2150  2221 D BtGatt.AdvertiseManager: message : 0
03-24 16:48:11.394  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
03-24 16:48:11.396  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:11.398  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:11.399  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:11.401  2150  2167 D BtGatt.GattService: stopScan() - queue size =1,
03-24 16:48:11.402  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:11.402  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:11.402  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:11.402  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:11.402  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:11.402  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:11.402  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:11.403  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:11.403  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.403  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:11.405  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 16:48:11.405  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.405  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:11.405  2150  2166 D BtGatt.GattService: registerClient() - UUID=707f7431-6e7d-41cb-9d14-8a303aba224f
03-24 16:48:11.405  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=707f7431-6e7d-41cb-9d14-8a303aba224f, clientIf=5
03-24 16:48:11.406  3274  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:48:11.406  2150  2167 D BtGatt.GattService: start scan with filters
03-24 16:48:11.406  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:11.406  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.406  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:48:11.407  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:11.408  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:11.408  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:48:11.410  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:11.410  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:11.410  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:11.411  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:11.411  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:11.411  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 16:48:11.411  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 16:48:11.411  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:11.412  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:11.412  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:11.412  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false],
03-24 16:48:11.412  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:11.412  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 16:48:11.412  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:11.412  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.414  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:11.414  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.414  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:11.414  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:11.415  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:11.415  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.416  2150  2957 D BtGatt.GattService: registerClient() - UUID=fbea07b4-82ae-4fe4-8aa5-4785bfb985d4
03-24 16:48:11.416  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=fbea07b4-82ae-4fe4-8aa5-4785bfb985d4, clientIf=6
03-24 16:48:11.416  3274  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:11.416  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:11.416  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.417  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:11.419  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:11.421  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:11.424  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:11.424  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:11.425  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:11.426  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:11.426  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:11.426  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:11.427  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:11.427  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:11.427  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:48:11.427  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:11.427  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:11.427  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.427  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:11.429  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:11.429  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.429  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:11.429  2150  2167 D BtGatt.GattService: registerClient() - UUID=08aecfd7-f260-4b36-8d4b-bdf9c9b81e96
03-24 16:48:11.430  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=08aecfd7-f260-4b36-8d4b-bdf9c9b81e96, clientIf=5
03-24 16:48:11.430  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:11.430  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.430  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:11.430  2150  2957 D BtGatt.GattService: start scan with filters
,03-24 16:48:11.431  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:11.431  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:11.431  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 16:48:11.431  3274  3274 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 16:48:11.431  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:11.431  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:11.431  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:48:11.431  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:11.431  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:11.432  3274  3796 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 360)
,03-24 16:48:11.433  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:11.434  3274  3796 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 33176
03-24 16:48:11.434  3274  3796 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 16:48:11.434  3274  3796 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 33176 (peer ID: F8:95:C7:87:3C:51)
03-24 16:48:11.435  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 16:48:11.435  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.435  3274  3796 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-24 16:48:11.436  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:11.436  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.436  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:11.436  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:11.438  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:11.438  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.438  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:11.438  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:11.440  3274  3331 I jxcore-log: INFO testThaliMobileNative: 
03-24 16:48:11.440  3274  3331 I jxcore-log: 
,03-24 16:48:11.440  3274  3331 I jxcore-log: ok 163 Must have listeningPort
03-24 16:48:11.440  3274  3331 I jxcore-log: 
,03-24 16:48:11.441  3274  3331 I jxcore-log: ok 164 listeningPort must be a number
03-24 16:48:11.441  3274  3331 I jxcore-log: 
03-24 16:48:11.441  3274  3331 I jxcore-log: ok 165 Connection must have clientPort
03-24 16:48:11.441  3274  3331 I jxcore-log: 
03-24 16:48:11.442  3274  3331 I jxcore-log: ok 166 clientPort must be a number
03-24 16:48:11.442  3274  3331 I jxcore-log: 
03-24 16:48:11.442  3274  3331 I jxcore-log: ok 167 Connection must have serverPort
03-24 16:48:11.442  3274  3331 I jxcore-log: 
03-24 16:48:11.442  3274  3331 I jxcore-log: ok 168 serverPort must be a number
03-24 16:48:11.442  3274  3331 I jxcore-log: 
03-24 16:48:11.443  3274  3331 I jxcore-log: ok 169 forward connection must have clientPort == 0
03-24 16:48:11.443  3274  3331 I jxcore-log: 
03-24 16:48:11.443  3274  3331 I jxcore-log: ok 170 forward connection must have serverPort == 0
03-24 16:48:11.443  3274  3331 I jxcore-log: 
,03-24 16:48:11.448  3274  3331 I jxcore-log: # teardown
03-24 16:48:11.448  3274  3331 I jxcore-log: 
,03-24 16:48:11.918  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:48:13.254   822  1415 I ActivityManager: Killing 2925:com.google.android.music:main/u0a66 (adj 15): empty #17
,03-24 16:48:14.929  2150  2210 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 16:48:16.290  2150  2223 W bt-btif : dm_pm_timer expires,
,03-24 16:48:16.290  2150  2223 W bt-btif : dm_pm_timer expires 0
03-24 16:48:16.290  2150  2223 W bt-btif : proc dm_pm_timer expires,
,03-24 16:48:16.406  2150  2150 D BtGatt.ScanManager: awakened up at time 311995
03-24 16:48:16.408  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:16.414  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 16:48:16.414  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:17.430  2150  2150 D BtGatt.ScanManager: awakened up at time 313019
,03-24 16:48:17.433  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:17.440  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 16:48:17.441  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:17.461  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:17.461  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 16:48:17.461  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
03-24 16:48:17.461  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
03-24 16:48:17.463  2150  2167 D BtGatt.GattService: stopScan() - queue size =1
03-24 16:48:17.464  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:17.465  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:17.465  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:17.465  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:48:17.465  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 16:48:17.465  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:48:17.466  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:17.466  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 16:48:17.467  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 16:48:17.467  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:48:17.468  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 16:48:17.469  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:17.469  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:17.469  3274  3331 I jxcore-log: ok 171 Should be able to call stopListeningForAdvertisments in teardown
03-24 16:48:17.469  3274  3331 I jxcore-log: 
03-24 16:48:17.470  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:17.470  3274  3331 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 16:48:17.470  3274  3331 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 360)
03-24 16:48:17.470  3274  3331 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 360)
03-24 16:48:17.470  3274  3331 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 16:48:17.470  3274  3331 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 360)
03-24 16:48:17.471  3274  3331 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 360)
03-24 16:48:17.471  3274  3796 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 360)
03-24 16:48:17.471  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:17.471  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:17.472  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 16:48:17.472  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:17.472  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 16:48:17.472  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:17.472  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:17.472  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:48:17.472  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 16:48:17.472  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:17.472  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:17.472  3274  3771 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:48:17.472  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:17.472  3274  3771 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:48:17.472  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:48:17.472  3274  3771 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 16:48:17.473  3274  3331 D BluetoothLeScanner: could not find callback wrapper
03-24 16:48:17.473  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:17.473  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 16:48:17.474  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:17.474  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:17.475  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:17.476  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:17.481  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:17.482  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:17.482  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 16:48:17.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:17.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:17.483  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:48:17.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 16:48:17.483  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:48:17.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:48:17.483  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:48:17.483  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:48:17.484  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:17.484  3274  3331 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 16:48:17.484  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:17.484  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:17.484  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:17.484  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:48:17.486  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:17.486  3274  3331 I jxcore-log: 
,03-24 16:48:17.491  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:48:17.491   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,03-24 16:48:17.497  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 16:48:17.498  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:17.498  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:17.501  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 16:48:17.501  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 16:48:17.501  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:48:17.501  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:17.501  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:17.501  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:17.501  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:48:17.503  3274  3331 I jxcore-log: ok 172 Should be able to call stopAdvertisingAndListening in teardown
03-24 16:48:17.503  3274  3331 I jxcore-log: 
,03-24 16:48:17.512  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:17.512  3274  3331 I jxcore-log: 
,03-24 16:48:17.514  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:17.514  3274  3331 I jxcore-log: 
,03-24 16:48:17.516  3274  3331 I jxcore-log: # setup
03-24 16:48:17.516  3274  3331 I jxcore-log: 
,03-24 16:48:18.107  3274  3331 I jxcore-log: # 39. Can shift large amounts of data
03-24 16:48:18.107  3274  3331 I jxcore-log: 
,03-24 16:48:18.236  2150  2223 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,03-24 16:48:18.292  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 52074, start advertisements: true
03-24 16:48:18.293  3274  3331 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectabl,e: false
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:18.293  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:18.293  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:18.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:48:18.302  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 16:48:18.302  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:48:18.302  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,03-24 16:48:18.302  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:18.313  2150  2957 D BtGatt.GattService: registerClient() - UUID=472e54df-e79c-4717-93ed-41a61c4a67ed
,03-24 16:48:18.314  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=472e54df-e79c-4717-93ed-41a61c4a67ed, clientIf=5,
03-24 16:48:18.315  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:48:18.316  2150  2166 D BtGatt.GattService: start scan with filters
,03-24 16:48:18.321  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:18.322  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:18.322  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:18.322  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:48:18.322  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:48:18.322  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:18.322  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:18.323  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 16:48:18.323  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 16:48:18.323  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:18.323  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:18.323  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:18.323  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 16:48:18.324  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:18.324  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:18.325  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:18.325  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:18.325  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:48:18.325  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:18.327  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:18.327  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:18.327  2150  2957 D BtGatt.GattService: registerClient() - UUID=c2c70317-b06a-49b1-b977-b7c1a27447ef
,03-24 16:48:18.327  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=c2c70317-b06a-49b1-b977-b7c1a27447ef, clientIf=6
03-24 16:48:18.328  3274  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:18.328  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:18.328  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:18.329  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:18.330  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
03-24 16:48:18.332  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
03-24 16:48:18.335  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 16:48:18.335  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:18.335  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:18.335   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:18.337  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:18.337  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 16:48:18.337  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:18.338  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:18.339  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 16:48:18.339  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 16:48:18.339  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:48:18.339  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 16:48:18.339  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:18.339  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:18.339  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:18.339  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:18.339  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:48:18.339  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:48:18.339  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:48:18.339  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:48:18.339  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:18.339  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:18.339  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:18.340  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:48:18.340  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:18.340  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:18.340  3274  3331 I jxcore-log: 
03-24 16:48:18.340   822  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:18.341  3274  3331 I jxcore-log: ok 173 Can call startUpdateAdvertisingAndListening without error
03-24 16:48:18.341  3274  3331 I jxcore-log: 
03-24 16:48:18.341  3274  3799 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:18.343  3274  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 16:48:18.343  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 52074, start advertisements: false
03-24 16:48:18.343  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:18.343  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should affect listening to advertisements only
03-24 16:48:18.343  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:18.343  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:18.344  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:18.344  3274  3331 I jxcore-log: 
,03-24 16:48:18.344  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:18.344  3274  3331 I jxcore-log: 
03-24 16:48:18.345  3274  3331 I jxcore-log: ok 174 Can call startListeningForAdvertisements without error
03-24 16:48:18.345  3274  3331 I jxcore-log: 
,03-24 16:48:22.534  2150  2223 E bt-btm  : btm_sec_disconnected - Clearing Pending flag,
,03-24 16:48:22.541  2150  2150 D BluetoothMapService: onReceive
,03-24 16:48:22.630   822  2545 I ActivityManager: Start proc 3800:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver
,03-24 16:48:22.650   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 24.839ms
,03-24 16:48:22.667   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 363us total 15.301ms
,03-24 16:48:22.686   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 355us total 16.536ms
,03-24 16:48:22.744   822   860 D BluetoothManagerService: Message: 20
,03-24 16:48:22.744   822   860 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22c16f30:true
,03-24 16:48:22.757  3800  3800 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 16:48:22.954   822  1154 I ActivityManager: Start proc 3822:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-24 16:48:22.994  3800  3800 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 16:48:23.014   822  1281 I ActivityManager: Killing 3486:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-24 16:48:23.222   822  1281 I ActivityManager: Killing 3422:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,03-24 16:48:23.459  2150  2150 D BtGatt.ScanManager: awakened up at time 319048
03-24 16:48:23.461  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:23.468  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
03-24 16:48:23.468  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:23.469  2150  2212 D BtGatt.GattService: current time is 319058314409
03-24 16:48:23.469  2150  2212 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -69, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 57, -105, -62, -122, 0, 100, 1, -128, -78, 52, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, 6, -121, 119, -122, -44, 84, 1, -128, -92, 46, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -7, 71, 62, -84, -123, 97, 1, -128, -92, 45, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 16:48:23.470  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:23.470  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:23.471  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:23.472  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 16:48:23.473  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
,03-24 16:48:23.474  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-24 16:48:23.474  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 1
03-24 16:48:23.474  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 16:48:23.475  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 16:48:23.475  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 16:48:23.486  3274  3331 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-24 16:48:23.486  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:23.489  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 16:48:23.489  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 16:48:23.489  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,03-24 16:48:23.489  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-24 16:48:23.489  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51,
03-24 16:48:23.489  3274  3331 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-24 16:48:23.491  3274  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 362)
03-24 16:48:23.491  3274  3846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-24 16:48:23.493  2150  2957 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-24 16:48:23.527  3462  3847 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 16:48:23.563  3462  3849 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 16:48:23.586  3502  3848 V KeepSync: Connecting to GoogleApiClient
,03-24 16:48:23.624  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 16:48:23.624  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:48:23.624  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:48:23.624  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:48:23.640  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:48:23.689  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-24 16:48:23.690  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:48:23.690  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:48:23.690  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:48:23.701  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: Handling authorization failure
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-24 16:48:23.734  1775  3850 E ClientConnectionOperation: 	... 7 more
,03-24 16:48:23.742  3502  3848 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-24 16:48:23.746  3502  3848 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 16:48:23.766  3502  3848 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 16:48:23.769  3502  3848 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-24 16:48:23.773  1349  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 16:48:23.773  1349  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:48:23.773  1349  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:48:23.773  1349  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:48:23.778  1349  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:48:23.861   822  2545 I art     : Explicit concurrent mark sweep GC freed 29464(1375KB) AllocSpace objects, 8(505KB) LOS objects, 32% free, 33MB/49MB, paused 1.535ms total 68.371ms
,03-24 16:48:23.864  3462  3849 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 16:48:23.868  3462  3847 E BooksSync: Soft error
03-24 16:48:23.868  3462  3847 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:48:23.868  3462  3847 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 16:48:23.868  3462  3847 E BooksSync: Sync error
03-24 16:48:23.868  3462  3847 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:48:23.868  3462  3847 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 16:48:23.868  3462  3847 I BooksSync: Finished books sync
,03-24 16:48:23.873   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289644, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:48:23.931  1349  1370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-24 16:48:23.931  1349  1370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:48:23.931  1349  1370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:48:23.931  1349  1370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:48:23.935  1349  1370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:48:23.981  3502  3848 E KeepSync: IOException
03-24 16:48:23.981  3502  3848 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-24 16:48:23.981  3502  3848 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-24 16:48:23.981  3502  3848 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-24 16:48:23.981  3502  3848 E KeepSync: 	... 10 more
03-24 16:48:23.981  3502  3848 W KeepSync: Sync result 2
,03-24 16:48:23.993   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 292010, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:48:24.048  2150  2223 W bt-btif : info:x10
03-24 16:48:24.048  2150  2212 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-24 16:48:24.075  3800  3800 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 16:48:24.077  3800  3800 I BluetoothClassifier: Bluetooth Device Name: G4-1,
,03-24 16:48:24.098  2150  2223 W bt-sdp  : process_service_search_attr_rsp,
,03-24 16:48:24.270  2150  2212 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 16:48:24.277  2150  2212 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
03-24 16:48:24.278  2150  2212 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 16:48:24.286  2150  2213 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-24 16:48:24.286  2150  2213 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 16:48:24.368  2150  2212 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,03-24 16:48:24.369  2150  2213 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 16:48:24.375  2150  2213 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,03-24 16:48:24.391  2150  2213 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 16:48:24.425  2150  2223 W bt-btif : new conn_srvc id:26, app_id:1
,03-24 16:48:24.425  2150  2223 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1
03-24 16:48:24.426  2150  2223 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 16:48:24.426  3274  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 362)
03-24 16:48:24.426  3274  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 362)
03-24 16:48:24.427  3274  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 363),
03-24 16:48:24.428  3274  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 363)
03-24 16:48:24.428  3274  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 362)
03-24 16:48:24.431  3274  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 363)
,03-24 16:48:24.441  3274  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 363)
,03-24 16:48:24.447  3274  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:24.449  3274  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 362),
03-24 16:48:24.449  3274  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 362),
03-24 16:48:24.449  3274  3855 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 363)
03-24 16:48:24.449  3274  3274 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 16:48:24.450  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51]
03-24 16:48:24.450  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 16:48:24.450  3274  3274 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 16:48:24.451  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0,
03-24 16:48:24.451  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:24.451  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:24.451  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:24.451  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:48:24.451  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:24.451  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 16:48:24.456  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:24.458  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:24.463  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:24.463  2150  2212 D BtGatt.GattService: Client app is not null!
,03-24 16:48:24.466  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 16:48:24.468  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:48:24.468  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:24.469  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 16:48:24.469  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:24.469  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 16:48:24.469  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:24.470  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:24.470  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:24.470  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:24.478  2150  2167 D BtGatt.GattService: registerClient() - UUID=96d3c8c2-6540-4e98-a6ce-73c0265db41c
,03-24 16:48:24.479  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=96d3c8c2-6540-4e98-a6ce-73c0265db41c, clientIf=6
03-24 16:48:24.479  3274  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:48:24.482  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:24.487  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:24.491  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:24.494  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:24.495  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:24.497  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:24.499  2150  3854 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:24.500  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 16:48:24.500  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:24.500  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:24.500  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:24.501  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:48:24.501  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:24.501  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:24.501  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.501  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
,03-24 16:48:24.503  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:24.503  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.503  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:24.504  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:24.505  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.507  2150  3854 D BtGatt.GattService: registerClient() - UUID=9369fdce-c746-447d-8168-d1472e063613
,03-24 16:48:24.508  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=9369fdce-c746-447d-8168-d1472e063613, clientIf=5
03-24 16:48:24.508  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:24.509  2150  2957 D BtGatt.GattService: start scan with filters
,03-24 16:48:24.510  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:24.510  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:24.510  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
,03-24 16:48:24.511  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:24.511  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:24.511  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:24.511  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1,
03-24 16:48:24.511  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:24.511  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:24.514  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:24.514  2150  2222 D BtGatt.ScanManager: handling starting scan,
,03-24 16:48:24.516  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:24.517  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:24.517  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.518  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 16:48:24.519  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.519  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:24.519  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:24.521  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 16:48:24.521  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:24.523  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 16:48:24.523  2150  3854 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:24.523  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.523  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:48:24.523  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 16:48:24.524  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 16:48:24.524  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 16:48:24.524  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:24.524  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 16:48:24.524  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:24.524  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:24.524  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:24.525  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:24.525  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.529  2150  2166 D BtGatt.GattService: registerClient() - UUID=2e28fa5a-755d-46a9-9633-1540d9c96642,
03-24 16:48:24.530  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=2e28fa5a-755d-46a9-9633-1540d9c96642, clientIf=6
03-24 16:48:24.530  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:48:24.531  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:24.535  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising,
,03-24 16:48:24.538  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,03-24 16:48:24.541  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 16:48:24.541  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:24.543  2150  2167 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:24.544  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:24.544  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:24.544  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:24.544  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
03-24 16:48:24.544  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:24.544  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:24.544  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:24.546  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:24.546  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.546  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
,03-24 16:48:24.548  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 16:48:24.548  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.548  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:24.550  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 16:48:24.550  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.550  2150  2212 D BtGatt.GattService: current time is 320139552689
03-24 16:48:24.550  2150  2212 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 16:48:24.550  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:24.551  2150  2167 D BtGatt.GattService: registerClient() - UUID=4191af10-de80-4e96-ab35-1a5bbda75e5d
,03-24 16:48:24.551  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=4191af10-de80-4e96-ab35-1a5bbda75e5d, clientIf=5
03-24 16:48:24.552  3274  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:24.552  2150  2166 D BtGatt.GattService: start scan with filters
,03-24 16:48:24.553  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:48:24.553  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:24.557  2150  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 16:48:24.558  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:24.560  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:24.562  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 16:48:24.562  2150  2212 D BtGatt.GattService: Client app is not null!
,03-24 16:48:24.563  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:24.564  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:48:24.564  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED,
,03-24 16:48:24.564  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false,
03-24 16:48:24.564  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:24.564  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 16:48:24.564  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:24.564  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:24.564  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:24.564  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 16:48:24.564  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.564  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 16:48:24.566  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,03-24 16:48:24.566  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.566  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:24.566  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:24.569  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:24.569  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.570  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:24.570  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.571  2150  2167 D BtGatt.GattService: registerClient() - UUID=216ed904-f8ea-47a4-81c5-0b4ffaff8363
03-24 16:48:24.571  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=216ed904-f8ea-47a4-81c5-0b4ffaff8363, clientIf=6
03-24 16:48:24.572  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:48:24.574  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:24.578  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:24.581  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:24.584  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
,03-24 16:48:24.584  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:24.586  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:24.587  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5,
03-24 16:48:24.587  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:24.587  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:24.587  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:24.588  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:24.588  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:48:24.588  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:24.588  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:24.588  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.588  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:24.590  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:24.590  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.591  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:24.592  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:24.592  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.598  2150  2167 D BtGatt.GattService: registerClient() - UUID=8126af40-2dd3-4be9-9a6b-9ac7e3adf14a
,03-24 16:48:24.599  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=8126af40-2dd3-4be9-9a6b-9ac7e3adf14a, clientIf=5
,03-24 16:48:24.599  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:24.599  2150  2166 D BtGatt.GattService: start scan with filters
03-24 16:48:24.600  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:24.600  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:24.600  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:24.601  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
,03-24 16:48:24.601  3274  3274 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 16:48:24.601  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:24.601  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 16:48:24.601  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
03-24 16:48:24.601  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:24.601  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:24.602  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:24.602  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 16:48:24.603  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:24.603  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.603  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:24.603  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:48:24.603  3274  3856 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 364),
03-24 16:48:24.605  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:24.605  3274  3856 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35136
,03-24 16:48:24.605  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.606  3274  3856 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 16:48:24.606  3274  3856 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 35136 (peer ID: F8:95:C7:87:3C:51)
03-24 16:48:24.606  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:24.606  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:24.607  3274  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
,03-24 16:48:24.613  3274  3331 I jxcore-log: INFO testThaliMobileNative: 
03-24 16:48:24.613  3274  3331 I jxcore-log: 
,03-24 16:48:24.614  3274  3331 I jxcore-log: INFO testThaliMobileNative: Forward connection
03-24 16:48:24.614  3274  3331 I jxcore-log: 
,03-24 16:48:24.617  3274  3856 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 35136
03-24 16:48:24.618  3274  3856 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,03-24 16:48:24.619  3274  3331 I jxcore-log: INFO testThaliMobileNative: forwardSend
03-24 16:48:24.619  3274  3331 I jxcore-log: 
03-24 16:48:24.619  3274  3856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 16:48:24.620  3274  3856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 16:48:24.622  3274  3856 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 364)
03-24 16:48:24.622  3274  3856 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 364)
,03-24 16:48:24.623  3274  3857 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 365, name: Sender)
,03-24 16:48:24.625  3274  3858 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 366, name: Receiver)
,03-24 16:48:24.677  3274  3331 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 16:48:24.677  3274  3331 I jxcore-log: 
,03-24 16:48:24.683  3274  3331 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 16:48:24.683  3274  3331 I jxcore-log: 
,03-24 16:48:24.688  3274  3331 I jxcore-log: INFO testThaliMobileNative: forwardData
03-24 16:48:24.688  3274  3331 I jxcore-log: 
,03-24 16:48:24.690  3274  3331 I jxcore-log: ok 175 received should match sent forward
03-24 16:48:24.690  3274  3331 I jxcore-log: 
,03-24 16:48:24.703  3274  3331 I jxcore-log: # teardown
03-24 16:48:24.703  3274  3331 I jxcore-log: 
,03-24 16:48:24.884  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:48:24.884  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should affect listening to advertisements only
,03-24 16:48:24.884  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,03-24 16:48:24.884  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,03-24 16:48:24.888  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:24.893  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 16:48:24.893  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 16:48:24.893  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:24.895  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:24.895  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:24.895  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:24.895  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 16:48:24.895  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 16:48:24.896  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:48:24.896  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,03-24 16:48:24.897  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:24.897  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
03-24 16:48:24.897  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:24.898  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:24.898  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.898  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:24.901  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:24.901  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:24.905  3274  3331 I jxcore-log: ok 176 Should be able to call stopListeningForAdvertisments in teardown
03-24 16:48:24.905  3274  3331 I jxcore-log: 
03-24 16:48:24.908  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:48:24.908  3274  3331 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> F8:95:C7:87:3C:51]
03-24 16:48:24.908  3274  3331 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 364)
03-24 16:48:24.908  3274  3331 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 364)
03-24 16:48:24.909  3274  3331 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 16:48:24.909  3274  3331 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 16:48:24.909  3274  3331 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 366
,03-24 16:48:24.909  3274  3331 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 16:48:24.909  3274  3331 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 365
03-24 16:48:24.910  3274  3331 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 364)
03-24 16:48:24.910  3274  3858 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
,03-24 16:48:24.910  3274  3858 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 366, name: Receiver)
03-24 16:48:24.910  3274  3857 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Sender): Socket closed
,03-24 16:48:24.910  3274  3857 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 365, name: Sender)
03-24 16:48:24.912  3274  3331 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 364)
,03-24 16:48:24.913  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
03-24 16:48:24.913  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:24.913  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 16:48:24.913  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:24.914  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 16:48:24.914  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 16:48:24.915  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:24.915  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:24.915  3274  3799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,03-24 16:48:24.915  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,03-24 16:48:24.915  3274  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
,03-24 16:48:24.915  3274  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 16:48:24.915  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:48:24.917  3274  3331 D BluetoothLeScanner: could not find callback wrapper
03-24 16:48:24.917  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
03-24 16:48:24.917  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,03-24 16:48:24.921  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:24.922  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:48:24.925  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
03-24 16:48:24.925  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:24.926  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 16:48:24.927  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:24.927  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:24.927  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
03-24 16:48:24.928  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 16:48:24.928  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:48:24.928  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false,
03-24 16:48:24.928  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:48:24.928  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 16:48:24.929  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-24 16:48:24.930  3274  3331 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear,
03-24 16:48:24.930  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:24.930  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:24.930  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:24.930  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:48:24.938  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 16:48:24.938   822  2543 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:24.939  2150  2223 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,03-24 16:48:24.943  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:24.943  3274  3331 I jxcore-log: 
03-24 16:48:24.944  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 16:48:24.945  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 16:48:24.945  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 16:48:24.945  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:48:24.945  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:24.948  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:24.948  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:24.948  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:24.948  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:24.948  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:48:24.949  3274  3331 I jxcore-log: ok 177 Should be able to call stopAdvertisingAndListening in teardown
03-24 16:48:24.949  3274  3331 I jxcore-log: 
,03-24 16:48:24.955  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:24.955  3274  3331 I jxcore-log: 
,03-24 16:48:24.956  3274  3331 I jxcore-log: # setup
03-24 16:48:24.956  3274  3331 I jxcore-log: 
,03-24 16:48:24.957  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:24.957  3274  3331 I jxcore-log: 
,03-24 16:48:27.947  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:27.947  3274  3331 I jxcore-log: 
,03-24 16:48:27.952  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:27.952  3274  3331 I jxcore-log: 
,03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:27.965  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:27.968  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:27.970  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:27.970  3274  3331 I jxcore-log: 
,03-24 16:48:27.971  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:27.971  3274  3331 I jxcore-log: 
,03-24 16:48:27.974  3274  3331 I jxcore-log: # 40. #startListeningForAdvertisements should fail if start not called
03-24 16:48:27.974  3274  3331 I jxcore-log: 
,03-24 16:48:27.976  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:27.976  3274  3331 I jxcore-log: 
,03-24 16:48:28.135  3274  3331 I jxcore-log: ok 178 specific error should be returned
03-24 16:48:28.135  3274  3331 I jxcore-log: 
,03-24 16:48:28.141  3274  3331 I jxcore-log: # teardown
03-24 16:48:28.141  3274  3331 I jxcore-log: 
,03-24 16:48:28.521  2150  2223 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 16:48:28.527  2150  2150 D BluetoothMapService: onReceive
,03-24 16:48:28.556  3800  3800 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 16:48:28.560  3800  3800 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 16:48:28.948  3274  3331 I jxcore-log: # setup
03-24 16:48:28.948  3274  3331 I jxcore-log: 
,03-24 16:48:29.059  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:29.059  3274  3331 I jxcore-log: 
,03-24 16:48:29.062  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:29.062  3274  3331 I jxcore-log: 
,03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:29.070  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:29.074  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:29.076  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:29.076  3274  3331 I jxcore-log: 
,03-24 16:48:29.077  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:29.077  3274  3331 I jxcore-log: 
,03-24 16:48:29.080  3274  3331 I jxcore-log: # 41. #startUpdateAdvertisingAndListening should fail if start not called
03-24 16:48:29.080  3274  3331 I jxcore-log: 
,03-24 16:48:29.082  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:29.082  3274  3331 I jxcore-log: 
,03-24 16:48:29.198  3274  3331 I jxcore-log: ok 179 specific error should be returned
03-24 16:48:29.198  3274  3331 I jxcore-log: 
,03-24 16:48:29.202  3274  3331 I jxcore-log: # teardown
03-24 16:48:29.202  3274  3331 I jxcore-log: 
,03-24 16:48:29.333  3274  3331 I jxcore-log: # setup
03-24 16:48:29.333  3274  3331 I jxcore-log: 
,03-24 16:48:29.453  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:29.453  3274  3331 I jxcore-log: 
,03-24 16:48:29.456  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:29.456  3274  3331 I jxcore-log: 
,03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:29.464  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:29.466  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:29.468  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:29.468  3274  3331 I jxcore-log: 
,03-24 16:48:29.469  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:29.469  3274  3331 I jxcore-log: 
,03-24 16:48:29.472  3274  3331 I jxcore-log: # 42. should be able to call #stopListeningForAdvertisements many times
03-24 16:48:29.472  3274  3331 I jxcore-log: 
,03-24 16:48:29.474  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:29.474  3274  3331 I jxcore-log: 
,03-24 16:48:29.608  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:29.608  3274  3331 I jxcore-log: 
,03-24 16:48:29.610  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 47267
03-24 16:48:29.610  3274  3331 I jxcore-log: 
,03-24 16:48:29.612  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:29.612  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:29.612  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:29.616  3274  3331 I jxcore-log: ok 180 no errors
03-24 16:48:29.616  3274  3331 I jxcore-log: 
,03-24 16:48:29.617  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:29.617  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:29.617  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:29.620  3274  3331 I jxcore-log: ok 181 still no errors
03-24 16:48:29.620  3274  3331 I jxcore-log: 
,03-24 16:48:29.626  3274  3331 I jxcore-log: # teardown
03-24 16:48:29.626  3274  3331 I jxcore-log: 
,03-24 16:48:29.776  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:29.777  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:29.777  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:29.781  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:29.782  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:29.782  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:29.791  3274  3331 I jxcore-log: # setup
03-24 16:48:29.791  3274  3331 I jxcore-log: 
,03-24 16:48:30.004  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:30.004  3274  3331 I jxcore-log: 
,03-24 16:48:30.008  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:30.008  3274  3331 I jxcore-log: 
,03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:30.016  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:30.020  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:30.021  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:30.021  3274  3331 I jxcore-log: 
,03-24 16:48:30.023  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:30.023  3274  3331 I jxcore-log: 
,03-24 16:48:30.026  3274  3331 I jxcore-log: # 43. should be able to call #startListeningForAdvertisements many times
03-24 16:48:30.026  3274  3331 I jxcore-log: 
,03-24 16:48:30.027  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:30.027  3274  3331 I jxcore-log: 
,03-24 16:48:30.049  2150  2210 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 16:48:30.159  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:30.159  3274  3331 I jxcore-log: 
,03-24 16:48:30.161  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 38797
03-24 16:48:30.161  3274  3331 I jxcore-log: 
,03-24 16:48:30.167  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 52074, start advertisements: false
03-24 16:48:30.167  3274  3331 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
,03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
,03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 16:48:30.167  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:30.168  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:30.168  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:48:30.168  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
03-24 16:48:30.172  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:48:30.172  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:30.172  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:30.176  2150  2167 D BtGatt.GattService: registerClient() - UUID=d017c1aa-564c-4286-b794-aa9ec52a4460
03-24 16:48:30.177  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=d017c1aa-564c-4286-b794-aa9ec52a4460, clientIf=5
03-24 16:48:30.177  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:30.177  2150  2166 D BtGatt.GattService: start scan with filters
03-24 16:48:30.178  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:30.179  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:48:30.179  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:30.179  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:48:30.179  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:48:30.179  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:30.179  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:30.180  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:30.181   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:30.187  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:30.187  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:48:30.187  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:48:30.188  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:30.188  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:48:30.188  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:30.188  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:30.188  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:48:30.190  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:30.190  3274  3331 I jxcore-log: 
03-24 16:48:30.190  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:30.190  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:30.190  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:30.191  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:30.192  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:30.192  3274  3331 I jxcore-log: 
03-24 16:48:30.193  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:30.193  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:30.193  3274  3331 I jxcore-log: ok 182 no errors
03-24 16:48:30.193  3274  3331 I jxcore-log: 
03-24 16:48:30.194  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:30.194  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:30.199  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 52074, start advertisements: false
,03-24 16:48:30.199  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:30.199  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:48:30.199  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:30.199  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:48:30.201  3274  3331 I jxcore-log: ok 183 still no errors
03-24 16:48:30.201  3274  3331 I jxcore-log: 
,03-24 16:48:30.207  3274  3331 I jxcore-log: # teardown
03-24 16:48:30.207  3274  3331 I jxcore-log: 
,03-24 16:48:31.095  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:31.095  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:31.095  3274  3331 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-24 16:48:31.095  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 16:48:31.095  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:31.095  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:31.095  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:31.096  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 16:48:31.096  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:48:31.099  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:31.102  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:31.103  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:31.103  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:31.103  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:48:31.104  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 16:48:31.104  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,03-24 16:48:31.104  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:31.104  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:31.105  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:31.106  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:31.108  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:31.108  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
03-24 16:48:31.108  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 16:48:31.108  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:31.109  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:31.109  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 16:48:31.111  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 16:48:31.111  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:31.115  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:31.115  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:31.115  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:31.115  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:31.115  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:48:31.122  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
03-24 16:48:31.122   822  1096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:31.127  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 16:48:31.128  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:31.128  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:31.132  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:31.132  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:31.132  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:31.132  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:31.134  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:48:31.135  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:31.135  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:31.136  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:31.136  3274  3331 I jxcore-log: 
03-24 16:48:31.137  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:31.137  3274  3331 I jxcore-log: 
,03-24 16:48:31.146  3274  3331 I jxcore-log: # setup
,03-24 16:48:31.146  3274  3331 I jxcore-log: 
,03-24 16:48:31.288  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:31.288  3274  3331 I jxcore-log: 
,03-24 16:48:31.293  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,03-24 16:48:31.293  3274  3331 I jxcore-log: 
,03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-24 16:48:31.304  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:31.309  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:31.312  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-24 16:48:31.312  3274  3331 I jxcore-log: 
,03-24 16:48:31.315  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-24 16:48:31.315  3274  3331 I jxcore-log: 
,03-24 16:48:31.322  3274  3331 I jxcore-log: # 44. should be able to call #startUpdateAdvertisingAndListening many times
,03-24 16:48:31.322  3274  3331 I jxcore-log: 
,03-24 16:48:31.326  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-24 16:48:31.326  3274  3331 I jxcore-log: 
,03-24 16:48:32.029  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:32.029  3274  3331 I jxcore-log: 
,03-24 16:48:32.031  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 51892
03-24 16:48:32.031  3274  3331 I jxcore-log: 
,03-24 16:48:32.037  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 51892, start advertisements: true,
03-24 16:48:32.037  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:48:32.037  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:32.038  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:48:32.043  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 16:48:32.043  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:32.043  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:32.044  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:32.049  2150  2957 D BtGatt.GattService: registerClient() - UUID=cc438b18-3246-4292-904e-97a017a5354a
,03-24 16:48:32.050  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=cc438b18-3246-4292-904e-97a017a5354a, clientIf=5
03-24 16:48:32.050  3274  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:32.051  2150  2166 D BtGatt.GattService: start scan with filters
,03-24 16:48:32.060  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:32.060  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:48:32.061  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
03-24 16:48:32.061  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,03-24 16:48:32.061  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:32.061  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:32.061  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:32.061  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:32.061  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:32.061  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:32.061  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:32.061  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 16:48:32.064  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:32.078  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 16:48:32.078  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:32.079  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 16:48:32.079  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:32.080  2150  2166 D BtGatt.GattService: registerClient() - UUID=9a48a8a8-ac57-4705-bcc7-73c696406956
,03-24 16:48:32.080  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:48:32.080  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=9a48a8a8-ac57-4705-bcc7-73c696406956, clientIf=6
03-24 16:48:32.081  3274  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:32.081  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
03-24 16:48:32.083  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:32.084  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:32.084  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:32.086  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:32.086  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:32.086  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
03-24 16:48:32.089  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:32.092  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
03-24 16:48:32.092  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:32.092  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:32.093   822  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:32.095  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:48:32.095  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:48:32.095  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:32.095  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:32.096  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
03-24 16:48:32.097  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 16:48:32.097  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:48:32.097  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 16:48:32.097  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,03-24 16:48:32.098  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:32.098  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:32.098  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:48:32.098  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:48:32.098  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:48:32.098  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:32.098  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:32.098  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:32.098  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:32.098  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:48:32.098  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:48:32.099  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:48:32.099   822  1326 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
03-24 16:48:32.101  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:32.101  3274  3331 I jxcore-log: 
03-24 16:48:32.101  3274  3860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:32.103  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:32.103  3274  3331 I jxcore-log: 
,03-24 16:48:32.104  3274  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
03-24 16:48:32.104  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:32.104  3274  3331 I jxcore-log: 
03-24 16:48:32.105  3274  3331 I jxcore-log: ok 184 no errors
03-24 16:48:32.105  3274  3331 I jxcore-log: 
,03-24 16:48:32.109  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 51892, start advertisements: true
,03-24 16:48:32.109  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:32.109  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:32.109  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:32.109  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK,
03-24 16:48:32.111  3274  3331 I jxcore-log: ok 185 still no errors
03-24 16:48:32.111  3274  3331 I jxcore-log: 
,03-24 16:48:32.117  3274  3331 I jxcore-log: # teardown
,03-24 16:48:32.117  3274  3331 I jxcore-log: 
,03-24 16:48:32.714  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:32.715  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 16:48:32.715  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:32.715  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 16:48:32.715  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:32.715  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 16:48:32.716  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:48:32.716  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:32.716  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:32.716  3274  3860 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:48:32.716  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:32.716  3274  3860 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:48:32.716  3274  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 16:48:32.720  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 16:48:32.720  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:48:32.724  2150  3854 D BtGatt.GattService: stopScan() - queue size =1
03-24 16:48:32.727  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:32.728  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:32.729  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:32.729  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:32.729  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:32.729  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:32.729  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:48:32.730  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 16:48:32.730  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:48:32.730  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:32.730  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 16:48:32.733  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,03-24 16:48:32.733  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:32.734  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:32.735  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:32.736  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:32.737  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 16:48:32.738  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:32.738  2150  2212 D BtGatt.GattService: current time is 328327539561
,03-24 16:48:32.738  2150  2212 D BtGatt.GattService: Batch record : [125, 47, 45, -22, 52, 76, 1, -128, -55, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -63, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 16:48:32.739  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:32.740  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:32.742  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:32.743  2150  2212 D BtGatt.GattService: Client app is not null!
,03-24 16:48:32.746  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 16:48:32.747  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:48:32.747  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:32.747  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:48:32.747  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 16:48:32.748  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:48:32.748  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:48:32.748  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:48:32.749  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 16:48:32.750  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:32.750  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:48:32.750  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:32.750  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-24 16:48:32.750  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:48:32.760  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 16:48:32.760   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:32.771  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:48:32.773  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:32.773  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,03-24 16:48:32.773  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:48:32.773  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:32.782  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:32.782  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:32.782  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:48:32.783  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:32.783  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:32.784  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED,
03-24 16:48:32.787  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:32.787  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:32.787  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,03-24 16:48:32.791  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:32.791  3274  3331 I jxcore-log: 
03-24 16:48:32.794  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,03-24 16:48:32.794  3274  3331 I jxcore-log: 
,03-24 16:48:32.796  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
03-24 16:48:32.796  3274  3331 I jxcore-log: 
,03-24 16:48:32.823  3274  3331 I jxcore-log: # setup,
03-24 16:48:32.823  3274  3331 I jxcore-log: 
,03-24 16:48:33.083  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
03-24 16:48:33.083  3274  3331 I jxcore-log: 
,03-24 16:48:33.088  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:33.088  3274  3331 I jxcore-log: 
,03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:33.098  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:33.104  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:33.107  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:33.107  3274  3331 I jxcore-log: 
,03-24 16:48:33.112  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:33.112  3274  3331 I jxcore-log: 
,03-24 16:48:33.118  3274  3331 I jxcore-log: # 45. should be able to call #stopAdvertisingAndListening many times
03-24 16:48:33.118  3274  3331 I jxcore-log: 
,03-24 16:48:33.123  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:33.123  3274  3331 I jxcore-log: 
,03-24 16:48:33.260  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:33.260  3274  3331 I jxcore-log: 
,03-24 16:48:33.263  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 49888
03-24 16:48:33.263  3274  3331 I jxcore-log: 
,03-24 16:48:33.265  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:33.265  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:33.265  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:33.269  3274  3331 I jxcore-log: ok 186 no errors
03-24 16:48:33.269  3274  3331 I jxcore-log: 
,03-24 16:48:33.270  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:48:33.270  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 16:48:33.270  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:33.272  3274  3331 I jxcore-log: ok 187 still no errors
03-24 16:48:33.272  3274  3331 I jxcore-log: 
,03-24 16:48:33.279  3274  3331 I jxcore-log: # teardown
03-24 16:48:33.279  3274  3331 I jxcore-log: 
,03-24 16:48:33.505  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:33.505  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:33.505  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:33.509  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:33.510  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:33.510  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:33.521  3274  3331 I jxcore-log: # setup
03-24 16:48:33.521  3274  3331 I jxcore-log: 
,03-24 16:48:33.644  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:33.644  3274  3331 I jxcore-log: 
,03-24 16:48:33.647  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:33.647  3274  3331 I jxcore-log: 
,03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:33.659  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:33.664  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:33.667  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:33.667  3274  3331 I jxcore-log: 
,03-24 16:48:33.670  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:33.670  3274  3331 I jxcore-log: 
,03-24 16:48:33.677  3274  3331 I jxcore-log: # 46. can get the network status before starting
03-24 16:48:33.677  3274  3331 I jxcore-log: 
,03-24 16:48:33.681  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:33.681  3274  3331 I jxcore-log: 
,03-24 16:48:33.822  3274  3331 I jxcore-log: ok 188 network status should have certain non-empty properties
03-24 16:48:33.822  3274  3331 I jxcore-log: 
,03-24 16:48:33.824  3274  3331 I jxcore-log: # teardown
03-24 16:48:33.824  3274  3331 I jxcore-log: 
,03-24 16:48:33.951  3274  3331 I jxcore-log: # setup
03-24 16:48:33.951  3274  3331 I jxcore-log: 
,03-24 16:48:34.071  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:34.071  3274  3331 I jxcore-log: 
,03-24 16:48:34.078  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:34.078  3274  3331 I jxcore-log: 
,03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:34.089  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:34.093  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:34.094  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:34.094  3274  3331 I jxcore-log: 
,03-24 16:48:34.096  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:34.096  3274  3331 I jxcore-log: 
,03-24 16:48:34.100  3274  3331 I jxcore-log: # 47. error returned with bad router
03-24 16:48:34.100  3274  3331 I jxcore-log: 
,03-24 16:48:34.102  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:34.102  3274  3331 I jxcore-log: 
,03-24 16:48:34.228  3274  3331 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 16:48:34.228  3274  3331 I jxcore-log: 
,03-24 16:48:34.231  3274  3331 I jxcore-log: ok 189 specific error expected
03-24 16:48:34.231  3274  3331 I jxcore-log: 
,03-24 16:48:34.233  3274  3331 I jxcore-log: # teardown
03-24 16:48:34.233  3274  3331 I jxcore-log: 
,03-24 16:48:34.841  3274  3331 I jxcore-log: # setup
03-24 16:48:34.841  3274  3331 I jxcore-log: 
,03-24 16:48:34.983  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:34.983  3274  3331 I jxcore-log: 
,03-24 16:48:34.985  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:34.985  3274  3331 I jxcore-log: 
,03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:34.993  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:34.996  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:34.998  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:34.998  3274  3331 I jxcore-log: 
03-24 16:48:34.999  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:34.999  3274  3331 I jxcore-log: 
,03-24 16:48:35.002  3274  3331 I jxcore-log: # 48. all services are stopped when we call stop
03-24 16:48:35.002  3274  3331 I jxcore-log: 
,03-24 16:48:35.005  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:35.005  3274  3331 I jxcore-log: 
,03-24 16:48:35.158  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:35.158  3274  3331 I jxcore-log: 
,03-24 16:48:35.162  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 57150
03-24 16:48:35.162  3274  3331 I jxcore-log: 
,03-24 16:48:35.169  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 51892, start advertisements: false
,03-24 16:48:35.169  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:35.169  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:48:35.169  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 16:48:35.174  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:48:35.174  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:35.174  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:35.180  2150  2166 D BtGatt.GattService: registerClient() - UUID=ff3bcac9-810d-4483-91a3-fc45054e61d8
,03-24 16:48:35.181  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=ff3bcac9-810d-4483-91a3-fc45054e61d8, clientIf=5
03-24 16:48:35.182  3274  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:48:35.184  2150  3854 D BtGatt.GattService: start scan with filters
,03-24 16:48:35.185  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:48:35.185  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:35.185  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:35.185  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 16:48:35.186  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:48:35.186  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:35.186  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 16:48:35.186  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:35.187   822  2545 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:35.193  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:35.193  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:35.195  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
03-24 16:48:35.195  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:35.195  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:35.195  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:35.198  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:35.198  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,03-24 16:48:35.200  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:35.201  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:35.202  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:35.202  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,03-24 16:48:35.202  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:35.202  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,03-24 16:48:35.202  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:35.203  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:35.205  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false},
03-24 16:48:35.205  3274  3331 I jxcore-log: 
,03-24 16:48:35.206  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
,03-24 16:48:35.206  3274  3331 I jxcore-log: 
,03-24 16:48:35.212  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 57150, start advertisements: true,
03-24 16:48:35.213  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:48:35.213  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:35.213  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:48:35.217  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,03-24 16:48:35.218  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 16:48:35.218  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:35.218  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:35.218  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
,03-24 16:48:35.218  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:35.219  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:35.219  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:35.224  2150  3854 D BtGatt.GattService: registerClient() - UUID=36a9f369-9436-4f51-aec9-ce1f04b73ffb
03-24 16:48:35.225  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=36a9f369-9436-4f51-aec9-ce1f04b73ffb, clientIf=6
03-24 16:48:35.225  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:35.226  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:35.230  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:35.234  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:35.236  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:35.237  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 16:48:35.237  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:35.237  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:35.237  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:35.237  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:48:35.237  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:48:35.237   822  1320 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:35.237  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,03-24 16:48:35.240  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:35.241  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:48:35.241  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:35.241  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:35.241  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:48:35.242  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 16:48:35.242  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,03-24 16:48:35.242  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:48:35.242  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 16:48:35.243  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:35.243  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:35.243  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:35.243  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,03-24 16:48:35.245   822  2545 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:35.245  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:35.245  3274  3331 I jxcore-log: 
03-24 16:48:35.247  3274  3861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:35.251  3274  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 16:48:35.252  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
,03-24 16:48:35.252  3274  3331 I jxcore-log: 
,03-24 16:48:35.255  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
,03-24 16:48:35.255  3274  3331 I jxcore-log: 
,03-24 16:48:35.257  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:48:35.257  3274  3331 I jxcore-log: ,
,03-24 16:48:35.262  3274  3331 I jxcore-log: ok 190 connection to servers manager should succeed after starting
03-24 16:48:35.262  3274  3331 I jxcore-log: 
,03-24 16:48:35.275  3274  3331 I jxcore-log: ok 191 connection to router server should succeed after starting
03-24 16:48:35.275  3274  3331 I jxcore-log: 
,03-24 16:48:35.276  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:35.277  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 16:48:35.277  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:35.277  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 16:48:35.277  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:35.277  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:48:35.277  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:48:35.277  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:35.277  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:35.277  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:35.277  3274  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:48:35.277  3274  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:48:35.277  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:48:35.277  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:48:35.277  3274  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
03-24 16:48:35.279  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:35.280  2150  3854 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:35.281  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:35.281  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:35.281  2150  2222 D BtGatt.ScanManager: stopping BLe Batch,
03-24 16:48:35.282  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:35.282  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:35.282  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:48:35.282  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING],
,03-24 16:48:35.282  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 16:48:35.282  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:35.282  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
03-24 16:48:35.284  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:35.284  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:35.284  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:35.285  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:35.286  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:35.287  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,03-24 16:48:35.287  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:35.287  2150  2212 D BtGatt.GattService: current time is 330876854716
03-24 16:48:35.287  2150  2212 D BtGatt.GattService: Batch record : [43, -104, -46, -35, -47, 76, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 16:48:35.288  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:35.290  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
,03-24 16:48:35.290  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:35.291  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6,
03-24 16:48:35.292  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:35.292  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:35.292  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:48:35.292  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
03-24 16:48:35.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED],
03-24 16:48:35.293  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:48:35.293  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:48:35.293  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
03-24 16:48:35.294  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:35.294  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:48:35.294  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:35.294  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:35.294  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:48:35.297  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:48:35.297  3274  3331 I jxcore-log: 
03-24 16:48:35.302  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:48:35.303   822  1154 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:35.312  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:48:35.313  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:35.313  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:35.316  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 16:48:35.316  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,03-24 16:48:35.316  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:35.316  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:35.316  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:35.317  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:35.317  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:48:35.318  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:48:35.318  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:48:35.318  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:35.318  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:35.319  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:35.319  3274  3331 I jxcore-log: 
,03-24 16:48:35.320  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:35.320  3274  3331 I jxcore-log: 
,03-24 16:48:35.321  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:35.321  3274  3331 I jxcore-log: 
,03-24 16:48:35.326  3274  3331 I jxcore-log: ok 192 is stopped after calling stop
03-24 16:48:35.326  3274  3331 I jxcore-log: 
,03-24 16:48:35.332  3274  3331 I jxcore-log: ok 193 connection to servers manager should fail after stopping
03-24 16:48:35.332  3274  3331 I jxcore-log: 
,03-24 16:48:35.336  3274  3331 I jxcore-log: ok 194 connection to router server should fail after stopping
03-24 16:48:35.336  3274  3331 I jxcore-log: 
,03-24 16:48:35.341  3274  3331 I jxcore-log: # teardown
03-24 16:48:35.341  3274  3331 I jxcore-log: 
,03-24 16:48:35.854  3274  3331 I jxcore-log: # setup
03-24 16:48:35.854  3274  3331 I jxcore-log: 
,03-24 16:48:36.031  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:36.031  3274  3331 I jxcore-log: 
,03-24 16:48:36.037  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:36.037  3274  3331 I jxcore-log: 
,03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:36.047  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:36.053  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:36.054  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:36.054  3274  3331 I jxcore-log: 
,03-24 16:48:36.056  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:36.056  3274  3331 I jxcore-log: 
,03-24 16:48:36.059  3274  3331 I jxcore-log: # 49. make sure terminateConnection is properly hooked up
03-24 16:48:36.059  3274  3331 I jxcore-log: 
,03-24 16:48:36.061  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:36.061  3274  3331 I jxcore-log: 
,03-24 16:48:36.220  3274  3331 I jxcore-log: ok 195 called with right arguments
03-24 16:48:36.220  3274  3331 I jxcore-log: 
,03-24 16:48:36.222  3274  3331 I jxcore-log: # teardown
03-24 16:48:36.222  3274  3331 I jxcore-log: 
,03-24 16:48:36.393  3274  3331 I jxcore-log: # setup
03-24 16:48:36.393  3274  3331 I jxcore-log: 
,03-24 16:48:36.500  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:36.500  3274  3331 I jxcore-log: 
,03-24 16:48:36.506  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:36.506  3274  3331 I jxcore-log: 
,03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:36.518  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:36.523  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:36.526  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:36.526  3274  3331 I jxcore-log: 
,03-24 16:48:36.530  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:36.530  3274  3331 I jxcore-log: 
,03-24 16:48:36.545  3274  3331 I jxcore-log: # 50. make sure terminateListener is properly hooked up
03-24 16:48:36.545  3274  3331 I jxcore-log: 
,03-24 16:48:36.547  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:36.547  3274  3331 I jxcore-log: 
,03-24 16:48:36.682  3274  3331 I jxcore-log: ok 196 called with right arguments
03-24 16:48:36.682  3274  3331 I jxcore-log: 
,03-24 16:48:36.685  3274  3331 I jxcore-log: # teardown
03-24 16:48:36.685  3274  3331 I jxcore-log: 
,03-24 16:48:36.835  3274  3331 I jxcore-log: # setup
03-24 16:48:36.835  3274  3331 I jxcore-log: 
,03-24 16:48:36.958  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:36.958  3274  3331 I jxcore-log: 
,03-24 16:48:36.962  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:36.962  3274  3331 I jxcore-log: 
,03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:36.971  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:36.974  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:36.976  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:36.976  3274  3331 I jxcore-log: 
,03-24 16:48:36.977  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:36.977  3274  3331 I jxcore-log: 
,03-24 16:48:36.981  3274  3331 I jxcore-log: # 51. make sure we actually call kill connections properly
03-24 16:48:36.981  3274  3331 I jxcore-log: 
,03-24 16:48:36.982  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:36.982  3274  3331 I jxcore-log: 
,03-24 16:48:37.122  3274  3331 I jxcore-log: ok 197 specific error expected
03-24 16:48:37.122  3274  3331 I jxcore-log: 
03-24 16:48:37.124  3274  3331 I jxcore-log: # teardown
03-24 16:48:37.124  3274  3331 I jxcore-log: 
,03-24 16:48:37.215  3274  3331 I jxcore-log: # setup
03-24 16:48:37.215  3274  3331 I jxcore-log: 
,03-24 16:48:37.313  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:37.313  3274  3331 I jxcore-log: 
,03-24 16:48:37.317  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:37.317  3274  3331 I jxcore-log: 
,03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:37.328  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:37.332  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:37.334  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:37.334  3274  3331 I jxcore-log: 
,03-24 16:48:37.335  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:37.335  3274  3331 I jxcore-log: 
,03-24 16:48:37.338  3274  3331 I jxcore-log: # 52. thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
03-24 16:48:37.338  3274  3331 I jxcore-log: 
,03-24 16:48:37.340  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:37.340  3274  3331 I jxcore-log: 
,03-24 16:48:37.486  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:37.486  3274  3331 I jxcore-log: 
,03-24 16:48:37.488  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 36315
03-24 16:48:37.488  3274  3331 I jxcore-log: 
,03-24 16:48:37.494  3274  3331 I jxcore-log: INFO thaliMobileNativeWrapper: routerPortConnectionFailed - {"routerPort":53199,"error":{}}
03-24 16:48:37.494  3274  3331 I jxcore-log: 
,03-24 16:48:37.495  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:37.495  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:37.495  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:37.497  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:48:37.497  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:48:37.497  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:37.502  3274  3331 I jxcore-log: ok 198 failure reason is as expected
03-24 16:48:37.502  3274  3331 I jxcore-log: 
,03-24 16:48:37.503  3274  3331 I jxcore-log: ok 199 error description is as expected
03-24 16:48:37.503  3274  3331 I jxcore-log: 
03-24 16:48:37.503  3274  3331 I jxcore-log: ok 200 must be stopped
03-24 16:48:37.503  3274  3331 I jxcore-log: 
03-24 16:48:37.509  3274  3331 I jxcore-log: # teardown
03-24 16:48:37.509  3274  3331 I jxcore-log: 
,03-24 16:48:37.654  3274  3331 I jxcore-log: # setup
03-24 16:48:37.654  3274  3331 I jxcore-log: 
,03-24 16:48:37.776  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:37.776  3274  3331 I jxcore-log: 
,03-24 16:48:37.781  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:37.781  3274  3331 I jxcore-log: 
,03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:37.789  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:37.791  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:37.793  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:37.793  3274  3331 I jxcore-log: 
,03-24 16:48:37.794  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:37.794  3274  3331 I jxcore-log: 
,03-24 16:48:37.797  3274  3331 I jxcore-log: # 53. We repeat failedConnection event when we get it from thaliTcpServersManager
03-24 16:48:37.797  3274  3331 I jxcore-log: 
,03-24 16:48:37.799  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:37.799  3274  3331 I jxcore-log: 
,03-24 16:48:37.930  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:37.930  3274  3331 I jxcore-log: 
,03-24 16:48:37.933  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 46828
03-24 16:48:37.933  3274  3331 I jxcore-log: 
,03-24 16:48:37.937  3274  3331 I jxcore-log: ok 201 peerIdentifier matches
03-24 16:48:37.937  3274  3331 I jxcore-log: 
03-24 16:48:37.937  3274  3331 I jxcore-log: ok 202 error description matches
,03-24 16:48:37.937  3274  3331 I jxcore-log: 
,03-24 16:48:37.943  3274  3331 I jxcore-log: # teardown
03-24 16:48:37.943  3274  3331 I jxcore-log: 
,03-24 16:48:38.042  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,03-24 16:48:38.042  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:38.042  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:38.043  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:38.043  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:38.043  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:38.052  3274  3331 I jxcore-log: # setup
03-24 16:48:38.052  3274  3331 I jxcore-log: 
,03-24 16:48:38.192  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:38.192  3274  3331 I jxcore-log: 
,03-24 16:48:38.197  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:38.197  3274  3331 I jxcore-log: 
,03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:38.206  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:38.211  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:38.213  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:38.213  3274  3331 I jxcore-log: 
,03-24 16:48:38.215  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:38.215  3274  3331 I jxcore-log: 
,03-24 16:48:38.217  3274  3331 I jxcore-log: # 54. we successfully receive and replay discoveryAdvertisingStateUpdate
03-24 16:48:38.217  3274  3331 I jxcore-log: 
,03-24 16:48:38.219  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:38.219  3274  3331 I jxcore-log: 
,03-24 16:48:38.365  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
,03-24 16:48:38.365  3274  3331 I jxcore-log: 
,03-24 16:48:38.369  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 38635,
03-24 16:48:38.369  3274  3331 I jxcore-log: 
,03-24 16:48:38.376  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 57150, start advertisements: false
,03-24 16:48:38.376  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:38.376  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:48:38.377  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 16:48:38.382  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:48:38.382  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:48:38.382  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:38.388  2150  3854 D BtGatt.GattService: registerClient() - UUID=ffba7312-c396-4b26-9d69-c3d94a7e0c68
,03-24 16:48:38.388  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=ffba7312-c396-4b26-9d69-c3d94a7e0c68, clientIf=5
,03-24 16:48:38.388  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:38.389  2150  2166 D BtGatt.GattService: start scan with filters
03-24 16:48:38.389  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 16:48:38.389  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:38.390  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 16:48:38.390  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:48:38.390  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:38.390  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 16:48:38.390  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:38.390   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:38.391  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:38.399  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
03-24 16:48:38.399  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.400  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:38.400  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 16:48:38.401  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:48:38.401  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
03-24 16:48:38.401  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:38.401  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:48:38.401  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.402  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:48:38.403  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:38.403  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:38.405  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:38.405  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:38.407  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:38.407  3274  3331 I jxcore-log: 
03-24 16:48:38.407  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:38.407  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:38.412  3274  3331 I jxcore-log: ok 203 discoveryActive matches
03-24 16:48:38.412  3274  3331 I jxcore-log: ,
03-24 16:48:38.413  3274  3331 I jxcore-log: ok 204 advertisingActive matches
03-24 16:48:38.413  3274  3331 I jxcore-log: 
03-24 16:48:38.416  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:38.416  3274  3331 I jxcore-log: 
,03-24 16:48:38.426  3274  3331 I jxcore-log: not ok 205 discoveryActive matches
,03-24 16:48:38.426  3274  3331 I jxcore-log: 
03-24 16:48:38.427  3274  3331 I jxcore-log:   ---
03-24 16:48:38.427  3274  3331 I jxcore-log: 
,03-24 16:48:38.427  3274  3331 I jxcore-log:     operator: equal
03-24 16:48:38.427  3274  3331 I jxcore-log: 
03-24 16:48:38.427  3274  3331 I jxcore-log:     expected: false
03-24 16:48:38.427  3274  3331 I jxcore-log: ,
03-24 16:48:38.427  3274  3331 I jxcore-log:     actual:   true
03-24 16:48:38.427  3274  3331 I jxcore-log: 
,03-24 16:48:38.427  3274  3331 I jxcore-log:   ...
,03-24 16:48:38.427  3274  3331 I jxcore-log: 
03-24 16:48:38.427  3274  3331 I jxcore-log: ok 206 advertisingActive matches
03-24 16:48:38.427  3274  3331 I jxcore-log: 
03-24 16:48:38.429  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 16:48:38.430  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:38.430  3274  3331 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,03-24 16:48:38.430  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:48:38.430  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:38.430  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,03-24 16:48:38.430  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:38.430  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 16:48:38.430  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:48:38.433  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
03-24 16:48:38.435  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 16:48:38.435  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.435  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:38.435  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:38.436  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:38.436  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:38.436  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 16:48:38.437  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
03-24 16:48:38.437  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
03-24 16:48:38.437  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:38.438  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:38.438  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.438  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:38.440  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:38.440  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:38.440  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:38.441  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 16:48:38.447  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,03-24 16:48:38.448  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:38.448  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:38.448  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:38.448  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:38.448  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:48:38.457  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
03-24 16:48:38.457   822   841 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:38.467  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:48:38.469  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:38.469  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:38.475  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:38.475  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:38.475  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:38.475  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:38.476  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,03-24 16:48:38.477  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:38.477  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:38.481  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:38.481  3274  3331 I jxcore-log: 
,03-24 16:48:38.483  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:38.483  3274  3331 I jxcore-log: 
,03-24 16:48:38.502  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:38.502  3274  3331 I jxcore-log: 
,03-24 16:48:38.504  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 40216
03-24 16:48:38.504  3274  3331 I jxcore-log: 
,03-24 16:48:38.510  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 40216, start advertisements: true
03-24 16:48:38.510  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:38.510  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:38.510  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:48:38.515  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 16:48:38.515  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:48:38.515  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:38.515  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:38.520  2150  2957 D BtGatt.GattService: registerClient() - UUID=23620bf1-e274-4c2c-b6e0-bb5928cfe3dc
,03-24 16:48:38.521  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=23620bf1-e274-4c2c-b6e0-bb5928cfe3dc, clientIf=5
03-24 16:48:38.521  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,03-24 16:48:38.522  2150  3854 D BtGatt.GattService: start scan with filters
,03-24 16:48:38.525  2150  2222 D BtGatt.ScanManager: handling starting scan
,03-24 16:48:38.525  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
03-24 16:48:38.525  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:38.525  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 16:48:38.525  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:48:38.525  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:38.526  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,03-24 16:48:38.526  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 16:48:38.526  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:38.526  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:38.527  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:38.527  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:38.527  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:38.528  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:38.528  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.529  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:38.529  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.530  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:38.530  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:48:38.532  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:38.532  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.534  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:38.534  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.536  2150  3854 D BtGatt.GattService: registerClient() - UUID=209d84db-9577-4455-9b79-3758f03caa1d
,03-24 16:48:38.537  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=209d84db-9577-4455-9b79-3758f03caa1d, clientIf=6
,03-24 16:48:38.537  3274  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:48:38.538  2150  2221 D BtGatt.AdvertiseManager: message : 0
03-24 16:48:38.543  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:38.546  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:38.549  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:38.550  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:38.550  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,03-24 16:48:38.551   822  1154 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:38.557  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:48:38.558  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 16:48:38.558  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:38.558  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:38.559  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,03-24 16:48:38.561  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
03-24 16:48:38.561  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
03-24 16:48:38.561  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,03-24 16:48:38.562  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:38.562  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:38.563  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:38.563  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,03-24 16:48:38.563  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,03-24 16:48:38.563  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
,03-24 16:48:38.563  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:48:38.563  3274  3274 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:48:38.564  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:38.564  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,03-24 16:48:38.564  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:38.564  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:48:38.564  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:38.565   822  2544 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:38.567  3274  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:38.568  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:38.568  3274  3331 I jxcore-log: 
,03-24 16:48:38.570  3274  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 16:48:38.580  3274  3331 I jxcore-log: not ok 207 discoveryActive matches
03-24 16:48:38.580  3274  3331 I jxcore-log: 
,03-24 16:48:38.581  3274  3331 I jxcore-log:   ---
03-24 16:48:38.581  3274  3331 I jxcore-log: 
03-24 16:48:38.581  3274  3331 I jxcore-log:     operator: equal
03-24 16:48:38.581  3274  3331 I jxcore-log: 
,03-24 16:48:38.581  3274  3331 I jxcore-log:     expected: false
03-24 16:48:38.581  3274  3331 I jxcore-log: 
03-24 16:48:38.581  3274  3331 I jxcore-log:     actual:   true
03-24 16:48:38.581  3274  3331 I jxcore-log: 
03-24 16:48:38.581  3274  3331 I jxcore-log:   ...,
03-24 16:48:38.581  3274  3331 I jxcore-log: 
,03-24 16:48:38.584  3274  3331 I jxcore-log: not ok 208 advertisingActive matches
03-24 16:48:38.584  3274  3331 I jxcore-log: 
03-24 16:48:38.584  3274  3331 I jxcore-log:   ---
03-24 16:48:38.584  3274  3331 I jxcore-log: 
,03-24 16:48:38.584  3274  3331 I jxcore-log:     operator: equal
03-24 16:48:38.584  3274  3331 I jxcore-log: 
03-24 16:48:38.585  3274  3331 I jxcore-log:     expected: true
03-24 16:48:38.585  3274  3331 I jxcore-log: 
03-24 16:48:38.585  3274  3331 I jxcore-log:     actual:   false
03-24 16:48:38.585  3274  3331 I jxcore-log: 
03-24 16:48:38.585  3274  3331 I jxcore-log:   ...
03-24 16:48:38.585  3274  3331 I jxcore-log: 
,03-24 16:48:38.587  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:38.587  3274  3331 I jxcore-log: 
,03-24 16:48:38.590  3274  3331 I jxcore-log: not ok 209 discoveryActive matches
03-24 16:48:38.590  3274  3331 I jxcore-log: 
03-24 16:48:38.590  3274  3331 I jxcore-log:   ---
,03-24 16:48:38.590  3274  3331 I jxcore-log: 
03-24 16:48:38.590  3274  3331 I jxcore-log:     operator: equal
03-24 16:48:38.590  3274  3331 I jxcore-log: 
,03-24 16:48:38.590  3274  3331 I jxcore-log:     expected: false
03-24 16:48:38.590  3274  3331 I jxcore-log: 
,03-24 16:48:38.590  3274  3331 I jxcore-log:     actual:   true
03-24 16:48:38.590  3274  3331 I jxcore-log: 
,03-24 16:48:38.591  3274  3331 I jxcore-log:   ...
03-24 16:48:38.591  3274  3331 I jxcore-log: 
03-24 16:48:38.591  3274  3331 I jxcore-log: ok 210 advertisingActive matches
03-24 16:48:38.591  3274  3331 I jxcore-log: 
03-24 16:48:38.593  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
03-24 16:48:38.593  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
03-24 16:48:38.593  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:38.593  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,03-24 16:48:38.593  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:38.594  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
03-24 16:48:38.594  3274  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:48:38.594  3274  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:48:38.594  3274  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,03-24 16:48:38.594  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 16:48:38.595  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
03-24 16:48:38.595  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:48:38.595  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:48:38.595  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:38.596  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
03-24 16:48:38.596  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:38.596  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
03-24 16:48:38.596  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:48:38.599  2150  3854 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:38.600  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:38.601  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:38.601  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:38.601  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:38.602  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 16:48:38.603  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:38.603  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,03-24 16:48:38.603  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
,03-24 16:48:38.604  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:38.604  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:38.604  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:38.605  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
,03-24 16:48:38.605  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:38.605  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 16:48:38.606  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:38.606  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:38.610  2150  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 16:48:38.611  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:38.613  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:38.613  2150  2212 D BtGatt.GattService: Client app is not null!
,03-24 16:48:38.614  2150  3854 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 16:48:38.615  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:38.615  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:38.615  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,03-24 16:48:38.616  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 16:48:38.616  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
03-24 16:48:38.616  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:38.616  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,03-24 16:48:38.616  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:48:38.617  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:38.617  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:38.618  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:38.618  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:38.618  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:38.618  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:38.618  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
03-24 16:48:38.621  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:38.621  3274  3331 I jxcore-log: 
,03-24 16:48:38.624  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:48:38.624  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:48:38.624  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:38.625  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:48:38.626   822  1281 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:38.632  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:48:38.633  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:38.633  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:38.637  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:38.638  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:38.638  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:48:38.640  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:38.640  3274  3331 I jxcore-log: 
03-24 16:48:38.642  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:38.642  3274  3331 I jxcore-log: 
03-24 16:48:38.643  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:38.643  3274  3331 I jxcore-log: 
,03-24 16:48:38.662  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:38.662  3274  3331 I jxcore-log: 
,03-24 16:48:38.664  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 46344
03-24 16:48:38.664  3274  3331 I jxcore-log: 
,03-24 16:48:38.671  3274  3331 I jxcore-log: # teardown
03-24 16:48:38.671  3274  3331 I jxcore-log: 
,03-24 16:48:39.182  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:48:39.182  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,03-24 16:48:39.182  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:39.183  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:48:39.183  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,03-24 16:48:39.184  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
03-24 16:48:39.192  3274  3331 I jxcore-log: # setup
03-24 16:48:39.192  3274  3331 I jxcore-log: 
,03-24 16:48:39.332  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 16:48:39.332  3274  3331 I jxcore-log: 
,03-24 16:48:39.333  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 16:48:39.333  3274  3331 I jxcore-log: 
,03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 16:48:39.341  3274  3331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 16:48:39.346  3274  3331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 16:48:39.347  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 16:48:39.347  3274  3331 I jxcore-log: 
,03-24 16:48:39.349  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 16:48:39.349  3274  3331 I jxcore-log: 
,03-24 16:48:39.352  3274  3331 I jxcore-log: # 55. can do HTTP requests between peers
03-24 16:48:39.352  3274  3331 I jxcore-log: 
,03-24 16:48:39.353  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 16:48:39.353  3274  3331 I jxcore-log: 
,03-24 16:48:39.496  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:48:39.496  3274  3331 I jxcore-log: 
,03-24 16:48:39.499  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 50294
03-24 16:48:39.499  3274  3331 I jxcore-log: 
,03-24 16:48:39.504  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 40216, start advertisements: false
03-24 16:48:39.504  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
,03-24 16:48:39.504  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:48:39.504  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,03-24 16:48:39.510  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:48:39.510  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:39.511  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:39.515  2150  2167 D BtGatt.GattService: registerClient() - UUID=51e2b11a-ff16-4c29-8fd6-a7aac6554807
,03-24 16:48:39.516  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=51e2b11a-ff16-4c29-8fd6-a7aac6554807, clientIf=5
03-24 16:48:39.517  3274  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:39.518  2150  3854 D BtGatt.GattService: start scan with filters
,03-24 16:48:39.520  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:39.520  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:48:39.520  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:39.521  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,03-24 16:48:39.524  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
03-24 16:48:39.524  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:39.524  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:39.524  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
03-24 16:48:39.525   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:39.531  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 16:48:39.531  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:39.533  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:39.533  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:39.534  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:39.534  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,03-24 16:48:39.536  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,03-24 16:48:39.537  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:39.537  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
03-24 16:48:39.538  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
03-24 16:48:39.538  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:39.539  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:39.539  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
03-24 16:48:39.539  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:39.539  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,03-24 16:48:39.540  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
,03-24 16:48:39.545  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:39.545  3274  3331 I jxcore-log: 
,03-24 16:48:39.547  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
03-24 16:48:39.547  3274  3331 I jxcore-log: 
,03-24 16:48:39.554  3274  3331 I io.jxcore.node.ConnectionHelper: start: Port number: 50294, start advertisements: true
,03-24 16:48:39.554  3274  3331 V io.jxcore.node.ConnectivityMonitor: start: Already started
03-24 16:48:39.555  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
03-24 16:48:39.555  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,03-24 16:48:39.559  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
03-24 16:48:39.559  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
03-24 16:48:39.559  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,03-24 16:48:39.559  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:39.559  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:39.559  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:39.559  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:39.559  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:39.564  2150  3854 D BtGatt.GattService: registerClient() - UUID=b0ecafe7-127d-499d-b576-3105eac6d76d
03-24 16:48:39.564  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=b0ecafe7-127d-499d-b576-3105eac6d76d, clientIf=6
,03-24 16:48:39.565  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:48:39.566  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:39.569  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:39.572  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:39.574  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
03-24 16:48:39.575  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:39.575  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
03-24 16:48:39.575  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
03-24 16:48:39.575  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:39.575  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:48:39.575  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
03-24 16:48:39.575  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
03-24 16:48:39.575   822  1154 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:39.579  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
03-24 16:48:39.579  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,03-24 16:48:39.579  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
03-24 16:48:39.579  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:39.579  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,03-24 16:48:39.580  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,03-24 16:48:39.581  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
03-24 16:48:39.581  3274  3331 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,03-24 16:48:39.581  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
03-24 16:48:39.582  3274  3331 I io.jxcore.node.ConnectionHelper: start: OK
03-24 16:48:39.582  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
03-24 16:48:39.582  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
03-24 16:48:39.582  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
03-24 16:48:39.583   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:39.584  3274  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:39.585  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
03-24 16:48:39.585  3274  3331 I jxcore-log: 
,03-24 16:48:39.587  3274  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 16:48:40.268  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:48:40.554  2150  2150 D BtGatt.ScanManager: awakened up at time 336143
,03-24 16:48:40.556  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:40.565  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 16:48:40.566  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:40.566  2150  2212 D BtGatt.GattService: current time is 336155571069
03-24 16:48:40.566   822  1326 D WifiService: acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1802bac6}
,03-24 16:48:40.566  2150  2212 D BtGatt.GattService: Batch record : [110, 4, 60, -123, -58, 79, 1, -128, -80, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -60, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 16:48:40.567  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:40.569  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 16:48:40.571  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:95:C7:87:3C:51], added - the peer count is 1
03-24 16:48:40.571  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> E0:DB:10:14:E2:C0], added - the peer count is 2
03-24 16:48:40.572  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:95:C7:87:3C:51], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: 
03-24 16:48:40.572  3274  3274 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> E0:DB:10:14:E2:C0], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 
,03-24 16:48:40.572   822  1024 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,03-24 16:48:40.579  3274  3331 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 16:48:40.579  3274  3331 I jxcore-log: 
,03-24 16:48:40.585  3274  3331 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 16:48:40.585  3274  3331 I jxcore-log: 
,03-24 16:48:40.588  3274  3331 I jxcore-log: ok 211 found a peer! {"peerIdentifier":"F8:95:C7:87:3C:51","portNumber":37939,"hostAddress":"127.0.0.1"}
03-24 16:48:40.588  3274  3331 I jxcore-log: 
,03-24 16:48:40.599  3274  3331 I jxcore-log: DEBUG createPeerListener: first connection
03-24 16:48:40.599  3274  3331 I jxcore-log: 
,03-24 16:48:40.603  3274  3331 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
03-24 16:48:40.603  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:40.605  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 16:48:40.605  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
03-24 16:48:40.605  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
03-24 16:48:40.605  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: G4-1 F8:95:C7:87:3C:51
03-24 16:48:40.605  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
03-24 16:48:40.605  3274  3331 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
03-24 16:48:40.606  3274  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 371)
03-24 16:48:40.606  3274  3865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-24 16:48:40.608  2150  3854 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 16:48:40.608  3274  3331 I jxcore-log: DEBUG createPeerListener: createPeerListener
03-24 16:48:40.608  3274  3331 I jxcore-log: 
03-24 16:48:40.611  3274  3331 I jxcore-log: DEBUG createPeerListener: pleaseConnect= false
03-24 16:48:40.611  3274  3331 I jxcore-log: 
,03-24 16:48:42.301  2150  2150 D BtGatt.ScanManager: awakened up at time 337891
03-24 16:48:42.302   822  1281 D WifiService: releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1802bac6}
,03-24 16:48:42.303  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:42.306  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 16:48:42.306  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:42.307  2150  2212 D BtGatt.GattService: current time is 337896284401
03-24 16:48:42.307  2150  2212 D BtGatt.GattService: Batch record : [110, 4, 60, -123, -58, 79, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -59, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 16:48:42.307  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
03-24 16:48:42.308  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
,03-24 16:48:42.310  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> E0:DB:10:14:E2:C0] updated - the peer count is 2
03-24 16:48:42.310  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
,03-24 16:48:42.371   822  1254 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,03-24 16:48:42.451   878   878 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-24 16:48:42.452   878   878 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,03-24 16:48:42.493   878   878 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,03-24 16:48:42.493   878   878 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-24 16:48:42.872  2150  2223 W bt-btif : No ag scb for peer addr
,03-24 16:48:42.902  2150  2223 W bt-btif : info:x10
,03-24 16:48:42.902  2150  2212 D         : remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,03-24 16:48:42.937  3800  3800 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 16:48:42.946  3800  3800 I BluetoothClassifier: Bluetooth Device Name: G4-1
,03-24 16:48:42.949  2150  2223 W bt-sdp  : process_service_search_attr_rsp
,03-24 16:48:43.197  2150  2212 D btif_config: btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,03-24 16:48:43.204  2150  2212 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,03-24 16:48:43.204  2150  2212 E bt-btif : check_cod: remote_cod = 0x5a020c
,03-24 16:48:43.211  2150  2213 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
03-24 16:48:43.211  2150  2213 I BluetoothBondStateMachine: Entering PendingCommandState State
,03-24 16:48:43.258  2150  2212 I BluetoothBondStateMachine: bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0,
03-24 16:48:43.258  2150  2213 D BluetoothAdapterProperties: Failed to remove device: F8:95:C7:87:3C:51
,03-24 16:48:43.261  2150  2213 I BluetoothBondStateMachine: Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10,
,03-24 16:48:43.273  2150  2213 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-24 16:48:43.466   878   878 I kickstart: STATUS: Received file 'm9kefs1'
03-24 16:48:43.467   878   878 I kickstart: STATUS: 950272 bytes transferred in 0.973357 seconds
03-24 16:48:43.467   878   878 I kickstart: STATUS: Successfully downloaded files from target 
03-24 16:48:43.467   878   878 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,03-24 16:48:43.470   878   878 I kickstart: STATUS: Sahara protocol completed
,03-24 16:48:45.070  2150  2223 W bt-btif : new conn_srvc id:26, app_id:255
03-24 16:48:45.070  2150  2223 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 16:48:45.070  2150  2223 W bt-btif : bta_dm_pm_ssr:2, lat:1200
,03-24 16:48:45.072  3274  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection accepted
03-24 16:48:45.073  3274  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Incoming connection initialized (thread ID: 372)
03-24 16:48:45.074  3274  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 16:48:45.074  2150  2223 W bt-btif : new conn_srvc id:26, app_id:1
03-24 16:48:45.074  2150  2223 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:255
03-24 16:48:45.074  2150  2223 W bt-btif : bta_dm_pm_ssr conn_srvc id:26, app_id:1,
03-24 16:48:45.074  2150  2223 W bt-btif : bta_dm_pm_ssr:2, lat:1200
03-24 16:48:45.075  3274  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onSocketConnected: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 371)
03-24 16:48:45.075  3274  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 371)
,03-24 16:48:45.075   822   840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 16:48:45.078  3274  3867 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 372)
03-24 16:48:45.078  3274  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesWritten: 15 bytes successfully written (thread ID: 373)
03-24 16:48:45.079  3274  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Outgoing connection initialized (*handshake* thread ID: 373)
,03-24 16:48:45.079  3274  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 371)
,03-24 16:48:45.086  3274  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
03-24 16:48:45.087  3274  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesRead: Read 15 bytes successfully (thread ID: 372)
03-24 16:48:45.089  3274  3868 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Entering thread (ID: 373)
03-24 16:48:45.090  3274  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Got valid identity from [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:45.091  3274  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: onBytesWritten: 15 bytes successfully written (thread ID: 372)
,03-24 16:48:45.092  3274  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: removeThreadFromList: Removing thread with ID 372
,03-24 16:48:45.092  3274  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Handshake thread disposed (thread ID: 372),
03-24 16:48:45.092  3274  3867 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onIncomingConnectionConnected: [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:45.093  3274  3867 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 372)
03-24 16:48:45.093  3274  3274 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 16:48:45.093  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Incoming connection to peer [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:45.093  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 16:48:45.094  3274  3274 I io.jxcore.node.ConnectionHelper: lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
03-24 16:48:45.094  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 2 -> 0
03-24 16:48:45.095  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:45.095  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
,03-24 16:48:45.095  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:45.095  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:48:45.095  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:45.095  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:45.096  3274  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,03-24 16:48:45.100  2150  2221 D BtGatt.AdvertiseManager: message : 1
03-24 16:48:45.100  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:48:45.103  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:45.103  2150  2212 D BtGatt.GattService: Client app is not null!
,03-24 16:48:45.105  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6,
,03-24 16:48:45.107  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,03-24 16:48:45.107  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:45.107  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 3, timeout: 0, is connectable: false
03-24 16:48:45.107  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
,03-24 16:48:45.107  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
03-24 16:48:45.108  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:45.108  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:45.109  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:45.109  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...,
,03-24 16:48:45.113  3274  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: onBytesRead: Read 15 bytes successfully (thread ID: 373)
,03-24 16:48:45.115  3274  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Handshake succeeded with [<no peer name> F8:95:C7:87:3C:51]
,03-24 16:48:45.115  3274  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onHandshakeSucceeded: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 371)
03-24 16:48:45.115  3274  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: handleSuccessfulClientThread: [<no peer name> F8:95:C7:87:3C:51] (thread ID: 371)
03-24 16:48:45.115  3274  3868 D org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread: Exiting thread (ID: 373)
03-24 16:48:45.118  2150  2957 D BtGatt.GattService: registerClient() - UUID=51ae66f4-61a8-4f1a-805e-2208ed29da01
,03-24 16:48:45.119  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=51ae66f4-61a8-4f1a-805e-2208ed29da01, clientIf=6
03-24 16:48:45.119  3274  3289 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:45.121  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:45.124  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:45.126  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:45.129  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:45.130  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:45.132  2150  2167 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:45.134  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:45.134  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 16:48:45.134  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.134  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:45.135  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:45.135  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:45.135  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:45.135  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,03-24 16:48:45.135  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,03-24 16:48:45.135  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:45.135  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:45.135  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.136  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
03-24 16:48:45.138  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 16:48:45.138  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.138  2150  2212 D BtGatt.GattService: current time is 340727642473
03-24 16:48:45.138  2150  2212 D BtGatt.GattService: Batch record : [-127, -59, 40, 32, -73, -32, 1, -128, -40, 49, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0, 110, 4, 60, -123, -58, 79, 1, -128, -71, 48, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
03-24 16:48:45.138  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:45.138  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 16:48:45.142  2150  2957 D BtGatt.GattService: registerClient() - UUID=158d003b-5f41-4071-801e-15febd206599
03-24 16:48:45.143  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=158d003b-5f41-4071-801e-15febd206599, clientIf=5
03-24 16:48:45.143  3274  3292 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:45.143  2150  2167 D BtGatt.GattService: start scan with filters
03-24 16:48:45.145  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:45.145  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:48:45.145  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:48:45.145  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 3 -> 1
03-24 16:48:45.146  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,03-24 16:48:45.146  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:45.146  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:45.146  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 16:48:45.146  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:48:45.146  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:45.148  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:45.148  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
03-24 16:48:45.149  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:45.149  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.149  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
03-24 16:48:45.149  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:48:45.149  2150  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 16:48:45.151  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:45.151  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
03-24 16:48:45.151  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:45.153  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,03-24 16:48:45.153  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:45.158  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 16:48:45.158  2150  2212 D BtGatt.GattService: Client app is not null!
,03-24 16:48:45.158  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:45.159  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:45.159  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 16:48:45.159  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
03-24 16:48:45.159  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:45.159  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 16:48:45.159  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:45.159  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:45.159  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,03-24 16:48:45.159  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,03-24 16:48:45.164  2150  2957 D BtGatt.GattService: registerClient() - UUID=84a3cd3b-54c1-4b0a-991d-2788eef1ea65
,03-24 16:48:45.165  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=84a3cd3b-54c1-4b0a-991d-2788eef1ea65, clientIf=6
03-24 16:48:45.165  3274  3291 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,03-24 16:48:45.166  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:45.169  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:45.171  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:45.174  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:45.175  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:45.176  2150  2166 D BtGatt.GattService: stopScan() - queue size =1
03-24 16:48:45.177  2150  2957 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:45.178  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,03-24 16:48:45.178  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:45.178  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,03-24 16:48:45.178  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.178  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:45.178  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
03-24 16:48:45.178  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:45.178  2150  2222 D BtGatt.ScanManager: stopping BLe Batch,
,03-24 16:48:45.178  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
03-24 16:48:45.181  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:45.181  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.181  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:45.182  2150  2957 D BtGatt.GattService: registerClient() - UUID=2d976307-0978-454e-82ce-2ecca36d9ef0
03-24 16:48:45.182  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
03-24 16:48:45.182  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:45.182  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=2d976307-0978-454e-82ce-2ecca36d9ef0, clientIf=5
,03-24 16:48:45.182  3274  3289 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:45.183  2150  2167 D BtGatt.GattService: start scan with filters
03-24 16:48:45.183  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 2 -> 0
03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 0
03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1
03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:48:45.183  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:48:45.189  2150  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 16:48:45.190  2150  2222 D BtGatt.ScanManager: handling starting scan
03-24 16:48:45.190  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:45.192  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
03-24 16:48:45.192  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:45.193  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=6
03-24 16:48:45.194  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,03-24 16:48:45.194  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:45.194  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.194  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
03-24 16:48:45.194  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 16:48:45.194  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
03-24 16:48:45.195  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,03-24 16:48:45.195  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 F8 CF C5 D9 E5 61
03-24 16:48:45.195  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:45.195  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
03-24 16:48:45.195  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
03-24 16:48:45.196  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:45.196  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.196  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:48:45.196  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:48:45.198  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:45.198  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.199  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:45.199  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,03-24 16:48:45.201  2150  2167 D BtGatt.GattService: registerClient() - UUID=5e387990-7ee3-4d79-bf5d-cadec7d6f9e3
03-24 16:48:45.201  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=5e387990-7ee3-4d79-bf5d-cadec7d6f9e3, clientIf=6
03-24 16:48:45.201  3274  3292 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
03-24 16:48:45.202  2150  2221 D BtGatt.AdvertiseManager: message : 0
,03-24 16:48:45.205  2150  2221 D BtGatt.AdvertiseManager: starting multi advertising
,03-24 16:48:45.207  2150  2212 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,03-24 16:48:45.209  2150  2212 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,03-24 16:48:45.210  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,03-24 16:48:45.211  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
,03-24 16:48:45.213  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
,03-24 16:48:45.213  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:45.213  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
03-24 16:48:45.213  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:45.213  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.213  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:48:45.213  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
03-24 16:48:45.213  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
03-24 16:48:45.213  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:45.213  3274  3274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,03-24 16:48:45.215  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:45.216  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.216  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:45.217  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,03-24 16:48:45.217  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.218  2150  2167 D BtGatt.GattService: registerClient() - UUID=1bfe9cb7-7ac9-4f5b-b049-9d09f41d713c
03-24 16:48:45.219  2150  2212 D BtGatt.GattService: onClientRegistered() - UUID=1bfe9cb7-7ac9-4f5b-b049-9d09f41d713c, clientIf=5
03-24 16:48:45.219  3274  3291 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
03-24 16:48:45.219  2150  2166 D BtGatt.GattService: start scan with filters
03-24 16:48:45.220  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,03-24 16:48:45.220  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
03-24 16:48:45.221  2150  2222 D BtGatt.ScanManager: handling starting scan,
,03-24 16:48:45.221  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Incoming socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 16:48:45.221  3274  3274 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 1
03-24 16:48:45.221  3274  3274 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnected: [<no peer name> F8:95:C7:87:3C:51]
03-24 16:48:45.221  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,03-24 16:48:45.221  3274  3274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
03-24 16:48:45.221  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
03-24 16:48:45.221  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:45.221  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
03-24 16:48:45.221  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing connection to peer [<no peer name> F8:95:C7:87:3C:51],
03-24 16:48:45.221  3274  3274 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:95:C7:87:3C:51] updated - the peer count is 2
03-24 16:48:45.222  3274  3869 D io.jxcore.node.IncomingSocketThread: Entering thread (ID: 374)
03-24 16:48:45.222  3274  3274 I io.jxcore.node.ConnectionHelper: onConnected: Outgoing socket thread, for peer [<no peer name> F8:95:C7:87:3C:51], created successfully
03-24 16:48:45.222  3274  3274 D io.jxcore.node.ConnectionHelper: onConnected: The total number of connections is now 2
03-24 16:48:45.222  2150  2212 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
03-24 16:48:45.223  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.224  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
03-24 16:48:45.224  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.224  2150  2222 D BtGatt.ScanManager: Starting BLE batch scan
,03-24 16:48:45.224  2150  2222 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
03-24 16:48:45.224  3274  3870 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 375)
03-24 16:48:45.225  3274  3870 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58052
03-24 16:48:45.225  3274  3870 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
03-24 16:48:45.225  2150  2212 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
03-24 16:48:45.225  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.226  3274  3870 I io.jxcore.node.ConnectionHelper: onListeningForIncomingConnections: Outgoing connection is using port 58052 (peer ID: F8:95:C7:87:3C:51)
03-24 16:48:45.226  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
03-24 16:48:45.226  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:45.226  3274  3869 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 50294
03-24 16:48:45.226  3274  3869 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
03-24 16:48:45.227  3274  3869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 16:48:45.227  3274  3869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 16:48:45.228  3274  3869 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 374)
,03-24 16:48:45.228  3274  3869 D io.jxcore.node.IncomingSocketThread: Exiting thread (ID: 374)
03-24 16:48:45.228  3274  3872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 376, name: Sender)
03-24 16:48:45.229  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:48:45.229  3274  3331 I jxcore-log: 
03-24 16:48:45.229  3274  3873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 377, name: Receiver)
03-24 16:48:45.230  3274  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "F8:95:C7:87:3C:51" removed
03-24 16:48:45.230  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:48:45.230  3274  3331 I jxcore-log: 
03-24 16:48:45.233  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:48:45.233  3274  3331 I jxcore-log: 
,03-24 16:48:45.237  3274  3331 I jxcore-log: DEBUG createPeerListener: forward connection
03-24 16:48:45.237  3274  3331 I jxcore-log: 
,03-24 16:48:45.240  3274  3870 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 58052
,03-24 16:48:45.240  3274  3870 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
03-24 16:48:45.240  3274  3870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 16:48:45.240  3274  3870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 8192 bytes
03-24 16:48:45.241  3274  3874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 378, name: Sender)
03-24 16:48:45.241  3274  3870 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 375)
03-24 16:48:45.241  3274  3870 D io.jxcore.node.OutgoingSocketThread: Exiting thread (ID: 375)
,03-24 16:48:45.242  3274  3875 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 379, name: Receiver)
,03-24 16:48:45.255  3274  3331 I jxcore-log: DEBUG createNativeListener: new stream: 
03-24 16:48:45.255  3274  3331 I jxcore-log: 
,03-24 16:48:45.258  3274  3331 I jxcore-log: DEBUG createNativeListener: new outgoing socket
03-24 16:48:45.258  3274  3331 I jxcore-log: 
,03-24 16:48:45.304  3274  3331 I jxcore-log: DEBUG createNativeListener: stream close:
03-24 16:48:45.304  3274  3331 I jxcore-log: 
,03-24 16:48:45.443  3274  3331 I jxcore-log: ok 212 server should return 200
03-24 16:48:45.443  3274  3331 I jxcore-log: 
,03-24 16:48:45.454  3274  3331 I jxcore-log: ok 213 response body should match testData
,03-24 16:48:45.454  3274  3331 I jxcore-log: 
,03-24 16:48:45.460  3274  3331 I jxcore-log: # teardown
,03-24 16:48:45.460  3274  3331 I jxcore-log: 
,03-24 16:48:45.474  3274  3874 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 378, thread name: Sender)
,03-24 16:48:45.474  3274  3874 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Input stream got -1 on read
03-24 16:48:45.474  3274  3874 W io.jxcore.node.ConnectionHelper: onDisconnected: Outgoing connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Input stream got -1 on read
03-24 16:48:45.474  3274  3874 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
03-24 16:48:45.474  3274  3874 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 375)
,03-24 16:48:45.474  3274  3874 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 375)
03-24 16:48:45.474  3274  3874 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 16:48:45.474  3274  3874 D io.jxcore.node.OutgoingSocketThread: close: Stopping receiving thread...
03-24 16:48:45.475  3274  3874 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 379
,03-24 16:48:45.475  3274  3874 D io.jxcore.node.OutgoingSocketThread: close: Stopping sending thread...
03-24 16:48:45.475  3274  3874 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 378
03-24 16:48:45.475  3274  3874 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 375)
03-24 16:48:45.475  3274  3875 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Receiver): bt socket closed, read return: -1
,03-24 16:48:45.475  3274  3874 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 375)
03-24 16:48:45.475  3274  3875 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 379, name: Receiver)
03-24 16:48:45.475  3274  3874 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
03-24 16:48:45.475  3274  3874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 378, name: Sender)
,03-24 16:48:46.165  2150  2353 W bt-btif : invalid rfc slot id: 16
,03-24 16:48:46.165  3274  3873 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 377, thread name: Receiver): bt socket closed, read return: -1
03-24 16:48:46.166  3274  3873 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
03-24 16:48:46.166  3274  3873 W io.jxcore.node.ConnectionHelper: onDisconnected: Incoming connection, peer [<no peer name> F8:95:C7:87:3C:51] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
03-24 16:48:46.166  3274  3873 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 374
03-24 16:48:46.166  3274  3873 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 374)
03-24 16:48:46.166  3274  3873 D io.jxcore.node.IncomingSocketThread: closeBluetoothSocketAndStreams: Bluetooth socket closed
03-24 16:48:46.167  3274  3873 D io.jxcore.node.IncomingSocketThread: close: Stopping receiving thread...
,03-24 16:48:46.167  3274  3873 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 377
03-24 16:48:46.167  3274  3873 D io.jxcore.node.IncomingSocketThread: close: Stopping sending thread...
03-24 16:48:46.167  3274  3873 I io.jxcore.node.StreamCopyingThread: doStop: Thread ID: 376
03-24 16:48:46.167  3274  3873 D io.jxcore.node.IncomingSocketThread: closeLocalSocketAndStreams: Closing... (thread ID: 374)
03-24 16:48:46.167  3274  3873 I io.jxcore.node.IncomingSocketThread: close: Complete (thread ID: 374)
03-24 16:48:46.168  3274  3873 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
03-24 16:48:46.169  3274  3872 W io.jxcore.node.StreamCopyingThread: Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Sender): Socket closed
,03-24 16:48:46.169  3274  3872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 376, name: Sender)
03-24 16:48:46.174  3274  3873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 377, name: Receiver)
,03-24 16:48:46.189  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:48:46.189  3274  3331 I jxcore-log: 
,03-24 16:48:46.196  3274  3331 I jxcore-log: INFO thaliMobileNativeWrapper: incomingConnectionToPortNumberFailed: %s
03-24 16:48:46.196  3274  3331 I jxcore-log: 
,03-24 16:48:46.199  3274  3331 I jxcore-log: INFO thaliMobileNativeWrapper: got incomingConnectionToPortNumberFailed for port [object Object] but we are listening on 50294
03-24 16:48:46.199  3274  3331 I jxcore-log: 
,03-24 16:48:46.368  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
03-24 16:48:46.369  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Stop operation: Should start/stop everything
,03-24 16:48:46.369  3274  3331 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
03-24 16:48:46.369  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
03-24 16:48:46.369  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
03-24 16:48:46.371  3274  3331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,03-24 16:48:46.372  3274  3864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
03-24 16:48:46.372  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,03-24 16:48:46.372  3274  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
03-24 16:48:46.372  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
03-24 16:48:46.372  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
03-24 16:48:46.372  3274  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
03-24 16:48:46.372  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
03-24 16:48:46.374  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,03-24 16:48:46.374  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
03-24 16:48:46.374  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
03-24 16:48:46.374  3274  3274 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
03-24 16:48:46.378  2150  2957 D BtGatt.GattService: stopScan() - queue size =1
03-24 16:48:46.381  2150  2167 D BtGatt.GattService: unregisterClient() - clientIf=5
03-24 16:48:46.383  2150  2212 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,03-24 16:48:46.383  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
03-24 16:48:46.383  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:46.383  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:46.383  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
03-24 16:48:46.383  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
03-24 16:48:46.383  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
03-24 16:48:46.383  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:46.383  2150  2222 D BtGatt.ScanManager: stopping BLe Batch
03-24 16:48:46.384  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
03-24 16:48:46.386  2150  2212 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
03-24 16:48:46.386  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:46.386  2150  2222 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,03-24 16:48:46.387  2150  2221 D BtGatt.AdvertiseManager: message : 1
,03-24 16:48:46.389  2150  2221 D BtGatt.AdvertiseManager: stop advertise for client 6
,03-24 16:48:46.393  2150  2212 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,03-24 16:48:46.393  2150  2212 D BtGatt.GattService: Client app is not null!
03-24 16:48:46.394  2150  2166 D BtGatt.GattService: unregisterClient() - clientIf=6
,03-24 16:48:46.395  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
03-24 16:48:46.395  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
03-24 16:48:46.395  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
03-24 16:48:46.395  2150  2212 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
03-24 16:48:46.395  2150  2212 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
03-24 16:48:46.396  2150  2212 D BtGatt.GattService: current time is 341985370598
,03-24 16:48:46.396  2150  2212 D BtGatt.GattService: Batch record : [-25, 21, -60, -60, -83, 109, 1, -128, -89, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -127, -59, 40, 32, -73, -32, 1, -128, -69, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64, 0]
03-24 16:48:46.397  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,03-24 16:48:46.397  2150  2212 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -32, -37, 16, 20, -30, -64]
03-24 16:48:46.398  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,03-24 16:48:46.398  3274  3331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,03-24 16:48:46.398  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,03-24 16:48:46.398  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
03-24 16:48:46.399  3274  3331 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
03-24 16:48:46.401  3274  3331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-24 16:48:46.401  3274  3331 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
03-24 16:48:46.401  3274  3331 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
03-24 16:48:46.401  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
03-24 16:48:46.401  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 16:48:46.401  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,03-24 16:48:46.410  3274  3274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,03-24 16:48:46.411   822  1415 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 16:48:46.418  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: false
,03-24 16:48:46.419  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 16:48:46.419  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,03-24 16:48:46.423  3274  3274 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
03-24 16:48:46.423  3274  3274 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
03-24 16:48:46.423  3274  3274 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,03-24 16:48:46.424  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
03-24 16:48:46.424  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
03-24 16:48:46.424  3274  3274 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,03-24 16:48:46.426  3274  3331 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
03-24 16:48:46.426  3274  3331 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
03-24 16:48:46.426  3274  3331 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,03-24 16:48:46.429  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
03-24 16:48:46.429  3274  3331 I jxcore-log: 
,03-24 16:48:46.431  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:46.431  3274  3331 I jxcore-log: 
,03-24 16:48:46.433  3274  3331 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
03-24 16:48:46.433  3274  3331 I jxcore-log: 
,03-24 16:48:46.453  2150  2223 W bt-btif : bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,03-24 16:48:46.454  3274  3331 I jxcore-log: # setup
03-24 16:48:46.454  3274  3331 I jxcore-log: 
,03-24 16:48:48.905  2150  2210 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-24 16:48:50.099  2150  2223 E bt-btm  : btm_sec_disconnected - Clearing Pending flag
,03-24 16:48:50.107  2150  2150 D BluetoothMapService: onReceive
,03-24 16:48:50.135  3800  3800 I BTConnectionReceiver: onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,03-24 16:48:50.140  3800  3800 I BluetoothClassifier: Bluetooth Device Name: G4-1,
,03-24 16:48:50.385  3274  3331 I jxcore-log: # 56. Test BEACONS_RETRIEVED_AND_PARSED locally
,03-24 16:48:50.385  3274  3331 I jxcore-log: 
,03-24 16:48:50.935  3274  3331 I jxcore-log: ok 214 peerIdentifier should be identifier
03-24 16:48:50.935  3274  3331 I jxcore-log: ,
03-24 16:48:50.936  3274  3331 I jxcore-log: ok 215 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 16:48:50.936  3274  3331 I jxcore-log: 
03-24 16:48:50.936  3274  3331 I jxcore-log: ok 216 good beacon
03-24 16:48:50.936  3274  3331 I jxcore-log: ,
03-24 16:48:50.937  3274  3331 I jxcore-log: ok 217 good preAmble
03-24 16:48:50.937  3274  3331 I jxcore-log: 
03-24 16:48:50.938  3274  3331 I jxcore-log: ok 218 public keys match!
03-24 16:48:50.938  3274  3331 I jxcore-log: 
,03-24 16:48:50.940  3274  3331 I jxcore-log: ok 219 must return null after successful call
03-24 16:48:50.940  3274  3331 I jxcore-log: ,
,03-24 16:48:50.949  3274  3331 I jxcore-log: # teardown
,03-24 16:48:50.949  3274  3331 I jxcore-log: 
,03-24 16:48:51.021  3274  3331 I jxcore-log: # setup
,03-24 16:48:51.021  3274  3331 I jxcore-log: 
,03-24 16:48:51.647  3274  3331 I jxcore-log: # 57. Test HTTP_BAD_RESPONSE locally
,03-24 16:48:51.647  3274  3331 I jxcore-log: 
,03-24 16:48:51.806  3274  3331 I jxcore-log: ok 220 Response should be HTTP_BAD_RESPONSE
,03-24 16:48:51.806  3274  3331 I jxcore-log: 
03-24 16:48:51.808  3274  3331 I jxcore-log: ok 221 must return null after successful call
03-24 16:48:51.808  3274  3331 I jxcore-log: 
,03-24 16:48:51.818  3274  3331 I jxcore-log: # teardown
,03-24 16:48:51.818  3274  3331 I jxcore-log: 
,03-24 16:48:51.924  3274  3331 I jxcore-log: # setup
,03-24 16:48:51.924  3274  3331 I jxcore-log: 
,03-24 16:48:52.136  3274  3331 I jxcore-log: # 58. Test NETWORK_PROBLEM locally
03-24 16:48:52.136  3274  3331 I jxcore-log: ,
,03-24 16:48:52.489  3274  3331 I jxcore-log: ok 222 Response should be NETWORK_PROBLEM
03-24 16:48:52.489  3274  3331 I jxcore-log: 
,03-24 16:48:52.493  3274  3331 I jxcore-log: ok 223 reject reason should be: Could not establish TCP connection
03-24 16:48:52.493  3274  3331 I jxcore-log: 
,03-24 16:48:52.500  3274  3331 I jxcore-log: # teardown
03-24 16:48:52.500  3274  3331 I jxcore-log: 
,03-24 16:48:52.653  3274  3331 I jxcore-log: # setup
03-24 16:48:52.653  3274  3331 I jxcore-log: 
,03-24 16:48:52.845  3274  3331 I jxcore-log: # 59. Test timeout locally
03-24 16:48:52.845  3274  3331 I jxcore-log: 
,03-24 16:48:52.940  1349  1349 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:48:53.013  1349  1373 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket,
03-24 16:48:53.013  1349  1373 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:48:53.013  1349  1373 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:48:53.014  1349  1373 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:48:53.025  1349  1373 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-24 16:48:53.106  1349  1373 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-24 16:48:53.106  1349  1373 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-24 16:48:53.106  1349  1373 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-24 16:48:53.106  1349  1373 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-24 16:48:53.106  1349  1373 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-24 16:48:53.106  1349  1373 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-24 16:48:53.106  1349  1373 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 16:48:53.112  2739  2774 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-24 16:48:53.112  2739  2774 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-24 16:48:53.112  2739  2774 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-24 16:48:53.112  2739  2774 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-24 16:48:53.112  2739  2774 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-24 16:48:53.112  2739  2774 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-24 16:48:53.112  2739  2774 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:446)
,03-24 16:48:53.146  2739  2774 W System  : Ignoring header User-Agent because its value was null.
,03-24 16:48:54.114  3274  3331 I jxcore-log: ok 224 Should be NETWORK_PROBLEM caused by timeout
03-24 16:48:54.114  3274  3331 I jxcore-log: 
,03-24 16:48:54.122  3274  3331 I jxcore-log: ok 225 reject reason should be Could not establish TCP connection
03-24 16:48:54.122  3274  3331 I jxcore-log: 
,03-24 16:48:54.130  3274  3331 I jxcore-log: # teardown
03-24 16:48:54.130  3274  3331 I jxcore-log: 
,03-24 16:48:54.282  3274  3331 I jxcore-log: # setup
03-24 16:48:54.282  3274  3331 I jxcore-log: 
,03-24 16:48:54.477  3274  3331 I jxcore-log: # 60. Call the start two times
03-24 16:48:54.477  3274  3331 I jxcore-log: 
,03-24 16:48:54.658  3274  3331 I jxcore-log: ok 226 Call start once
03-24 16:48:54.658  3274  3331 I jxcore-log: 
,03-24 16:48:54.728  3274  3331 I jxcore-log: ok 227 Response should be BEACONS_RETRIEVED_AND_PARSED
03-24 16:48:54.728  3274  3331 I jxcore-log: 
,03-24 16:48:54.729  3274  3331 I jxcore-log: ok 228 must return null after successful call.
03-24 16:48:54.729  3274  3331 I jxcore-log: 
,03-24 16:48:54.738  3274  3331 I jxcore-log: # teardown
03-24 16:48:54.738  3274  3331 I jxcore-log: 
,03-24 16:48:54.841  3274  3331 I jxcore-log: # setup
03-24 16:48:54.841  3274  3331 I jxcore-log: 
,03-24 16:48:55.038  3274  3331 I jxcore-log: # 61. Call the kill before calling the start
03-24 16:48:55.038  3274  3331 I jxcore-log: 
,03-24 16:48:55.188  3274  3331 I jxcore-log: ok 229 Should be Killed
03-24 16:48:55.188  3274  3331 I jxcore-log: 
,03-24 16:48:55.193  3274  3331 I jxcore-log: ok 230 Start after killed
03-24 16:48:55.193  3274  3331 I jxcore-log: 
,03-24 16:48:55.199  3274  3331 I jxcore-log: # teardown
03-24 16:48:55.199  3274  3331 I jxcore-log: 
,03-24 16:48:55.352  3274  3331 I jxcore-log: # setup,
03-24 16:48:55.352  3274  3331 I jxcore-log: 
,03-24 16:48:55.625  3274  3331 I jxcore-log: # 62. Call the kill immediately after the start
03-24 16:48:55.625  3274  3331 I jxcore-log: 
,03-24 16:48:55.803  3274  3331 I jxcore-log: ok 231 Should be KILLED
03-24 16:48:55.803  3274  3331 I jxcore-log: 
,03-24 16:48:55.805  3274  3331 I jxcore-log: ok 232 must return null after successful kill
03-24 16:48:55.805  3274  3331 I jxcore-log: 
,03-24 16:48:55.811  3274  3331 I jxcore-log: # teardown
03-24 16:48:55.811  3274  3331 I jxcore-log: 
,03-24 16:48:55.939  3274  3331 I jxcore-log: # setup
03-24 16:48:55.939  3274  3331 I jxcore-log: 
,03-24 16:48:56.137  3274  3331 I jxcore-log: # 63. Call the kill while waiting a response from the server
03-24 16:48:56.137  3274  3331 I jxcore-log: 
,03-24 16:48:58.286  3274  3331 I jxcore-log: ok 233 Should be KILLED
03-24 16:48:58.286  3274  3331 I jxcore-log: 
,03-24 16:48:58.289  3274  3331 I jxcore-log: ok 234 must return null after successful kill
03-24 16:48:58.289  3274  3331 I jxcore-log: 
,03-24 16:48:58.316  3274  3331 I jxcore-log: # teardown
03-24 16:48:58.316  3274  3331 I jxcore-log: 
,03-24 16:48:58.853  3274  3331 I jxcore-log: # setup
03-24 16:48:58.853  3274  3331 I jxcore-log: 
,03-24 16:48:59.745  3274  3331 I jxcore-log: # 64. Test to exceed the max content size locally
03-24 16:48:59.745  3274  3331 I jxcore-log: 
,03-24 16:48:59.982  3274  3331 I jxcore-log: ok 235 HTTP_BAD_RESPONSE should be response when content size is exceeded
03-24 16:48:59.982  3274  3331 I jxcore-log: 
,03-24 16:48:59.986  3274  3331 I jxcore-log: ok 236 must return null after successful call
03-24 16:48:59.986  3274  3331 I jxcore-log: 
,03-24 16:48:59.996  3274  3331 I jxcore-log: # teardown
03-24 16:48:59.996  3274  3331 I jxcore-log: 
,03-24 16:49:00.686  3274  3274 I io.jxcore.node.ConnectionHelper: restoreDefaultBleDiscoverySettings: Powering the BLE discovery back up
,03-24 16:49:00.686  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 0 -> 2
,03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 1,
03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 1, timeout: 0, is connectable: false
03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
,03-24 16:49:00.687  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 1 -> 3
03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 0
03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 0, report delay in milliseconds: 500, scan result type: 0
03-24 16:49:00.690  3274  3274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 0 -> 2
03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
03-24 16:49:00.691  3274  3274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
03-24 16:49:00.699  3274  3331 I jxcore-log: # setup
03-24 16:49:00.699  3274  3331 I jxcore-log: 
,03-24 16:49:00.905  3274  3331 I jxcore-log: # 65. Close the server socket while the client is waiting a response from the server. Local test.
03-24 16:49:00.905  3274  3331 I jxcore-log: 
,03-24 16:49:03.137  3274  3331 I jxcore-log: ok 237 Should be NETWORK_PROBLEM caused closing server socket
03-24 16:49:03.137  3274  3331 I jxcore-log: 
,03-24 16:49:03.144  3274  3331 I jxcore-log: ok 238 Should be Could not establish TCP connection
03-24 16:49:03.144  3274  3331 I jxcore-log: 
,03-24 16:49:03.152  3274  3331 I jxcore-log: # teardown
03-24 16:49:03.152  3274  3331 I jxcore-log: 
,03-24 16:49:03.325  3274  3331 I jxcore-log: # setup
03-24 16:49:03.325  3274  3331 I jxcore-log: 
,03-24 16:49:03.559  3274  3331 I jxcore-log: # 66. Close the client socket while the client is waiting a response from the server. Local test.
03-24 16:49:03.559  3274  3331 I jxcore-log: 
,03-24 16:49:05.757  3274  3331 I jxcore-log: ok 239 Should be NETWORK_PROBLEM caused closing client socket
03-24 16:49:05.757  3274  3331 I jxcore-log: 
,03-24 16:49:05.763  3274  3331 I jxcore-log: ok 240 Should be Could not establish TCP connection
03-24 16:49:05.763  3274  3331 I jxcore-log: 
,03-24 16:49:05.776  3274  3331 I jxcore-log: # teardown
03-24 16:49:05.776  3274  3331 I jxcore-log: 
,03-24 16:49:05.862  3274  3331 I jxcore-log: # setup
03-24 16:49:05.862  3274  3331 I jxcore-log: 
,03-24 16:49:06.012  3274  3331 I jxcore-log: # 67. #generatePreambleAndBeacons bad args
03-24 16:49:06.012  3274  3331 I jxcore-log: 
,03-24 16:49:06.153  3274  3331 I jxcore-log: ok 241 publicKeysToNotify cannot be null
03-24 16:49:06.153  3274  3331 I jxcore-log: 
,03-24 16:49:06.155  3274  3331 I jxcore-log: ok 242 ecdh for local device cannot be null
03-24 16:49:06.155  3274  3331 I jxcore-log: 
,03-24 16:49:06.156  3274  3331 I jxcore-log: ok 243 milliseconds cannot be less than 0
03-24 16:49:06.156  3274  3331 I jxcore-log: 
,03-24 16:49:06.158  3274  3331 I jxcore-log: ok 244 milliseconds cannot be 0
03-24 16:49:06.158  3274  3331 I jxcore-log: 
,03-24 16:49:06.160  3274  3331 I jxcore-log: ok 245 milliseconds cannot be greater than one_day
03-24 16:49:06.160  3274  3331 I jxcore-log: 
,03-24 16:49:06.164  3274  3331 I jxcore-log: # teardown
03-24 16:49:06.164  3274  3331 I jxcore-log: 
,03-24 16:49:06.323  3274  3331 I jxcore-log: # setup
03-24 16:49:06.323  3274  3331 I jxcore-log: 
,03-24 16:49:06.443  3274  3331 I jxcore-log: # 68. #generatePreambleAndBeacons empty keys to notify
03-24 16:49:06.443  3274  3331 I jxcore-log: 
,03-24 16:49:06.610  3274  3331 I jxcore-log: ok 246 should be equal
03-24 16:49:06.610  3274  3331 I jxcore-log: 
,03-24 16:49:06.613  3274  3331 I jxcore-log: # teardown
03-24 16:49:06.613  3274  3331 I jxcore-log: 
,03-24 16:49:06.703  3274  3331 I jxcore-log: # setup
03-24 16:49:06.703  3274  3331 I jxcore-log: 
,03-24 16:49:06.792  3274  3331 I jxcore-log: # 69. #generatePreambleAndBeacons multiple keys to notify
03-24 16:49:06.792  3274  3331 I jxcore-log: 
,03-24 16:49:07.009  3274  3331 I jxcore-log: ok 247 should be equal,
03-24 16:49:07.009  3274  3331 I jxcore-log: 
03-24 16:49:07.009  3274  3331 I jxcore-log: ok 248 should be equal
03-24 16:49:07.009  3274  3331 I jxcore-log: 
03-24 16:49:07.010  3274  3331 I jxcore-log: ok 249 (unnamed assert)
03-24 16:49:07.010  3274  3331 I jxcore-log: 
,03-24 16:49:07.010  3274  3331 I jxcore-log: ok 250 should be equal
03-24 16:49:07.010  3274  3331 I jxcore-log: 
03-24 16:49:07.012  3274  3331 I jxcore-log: # teardown
03-24 16:49:07.012  3274  3331 I jxcore-log: 
,03-24 16:49:07.133  3274  3331 I jxcore-log: # setup
03-24 16:49:07.133  3274  3331 I jxcore-log: 
,03-24 16:49:07.250  3274  3331 I jxcore-log: # 70. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
03-24 16:49:07.250  3274  3331 I jxcore-log: 
,03-24 16:49:07.385  3274  3331 I jxcore-log: ok 251 should throw
03-24 16:49:07.385  3274  3331 I jxcore-log: 
,03-24 16:49:07.387  3274  3331 I jxcore-log: # teardown
03-24 16:49:07.387  3274  3331 I jxcore-log: 
,03-24 16:49:07.555  3274  3331 I jxcore-log: # setup
03-24 16:49:07.555  3274  3331 I jxcore-log: 
,03-24 16:49:07.678  3274  3331 I jxcore-log: # 71. #parseBeacons invalid expiration in beaconStreamWithPreAmble
03-24 16:49:07.678  3274  3331 I jxcore-log: 
,03-24 16:49:07.901  3274  3331 I jxcore-log: ok 252 Preamble expiration must be a 64 bit integer
03-24 16:49:07.901  3274  3331 I jxcore-log: 
,03-24 16:49:07.905  3274  3331 I jxcore-log: # teardown
03-24 16:49:07.905  3274  3331 I jxcore-log: 
,03-24 16:49:08.033  3274  3331 I jxcore-log: # setup
03-24 16:49:08.033  3274  3331 I jxcore-log: 
,03-24 16:49:08.153  3274  3331 I jxcore-log: # 72. #parseBeacons expiration out of range lower
03-24 16:49:08.153  3274  3331 I jxcore-log: 
,03-24 16:49:08.371  3274  3331 I jxcore-log: ok 253 Expiration out of range
03-24 16:49:08.371  3274  3331 I jxcore-log: 
,03-24 16:49:08.373  3274  3331 I jxcore-log: # teardown
03-24 16:49:08.373  3274  3331 I jxcore-log: 
,03-24 16:49:08.502  3274  3331 I jxcore-log: # setup
03-24 16:49:08.502  3274  3331 I jxcore-log: 
,03-24 16:49:08.685  3274  3331 I jxcore-log: # 73. #parseBeacons expiration out of range lower
03-24 16:49:08.685  3274  3331 I jxcore-log: 
,03-24 16:49:08.876  3274  3331 I jxcore-log: ok 254 Expiration out of range,
03-24 16:49:08.876  3274  3331 I jxcore-log: 
,03-24 16:49:08.889  3274  3331 I jxcore-log: # teardown
03-24 16:49:08.889  3274  3331 I jxcore-log: 
,03-24 16:49:09.034  3274  3331 I jxcore-log: # setup
03-24 16:49:09.034  3274  3331 I jxcore-log: 
,03-24 16:49:09.269  3274  3331 I jxcore-log: # 74. #parseBeacons no beacons returns null
03-24 16:49:09.269  3274  3331 I jxcore-log: 
,03-24 16:49:09.399  3274  3331 I jxcore-log: ok 255 should be equal
03-24 16:49:09.399  3274  3331 I jxcore-log: 
,03-24 16:49:09.402  3274  3331 I jxcore-log: # teardown
03-24 16:49:09.402  3274  3331 I jxcore-log: 
,03-24 16:49:09.493  3274  3331 I jxcore-log: # setup
03-24 16:49:09.493  3274  3331 I jxcore-log: 
,03-24 16:49:09.627  3274  3331 I jxcore-log: # 75. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
03-24 16:49:09.627  3274  3331 I jxcore-log: 
,03-24 16:49:09.799  3274  3331 I jxcore-log: ok 256 Malformed encrypted beacon key ID
03-24 16:49:09.799  3274  3331 I jxcore-log: 
,03-24 16:49:09.802  3274  3331 I jxcore-log: # teardown
03-24 16:49:09.802  3274  3331 I jxcore-log: 
,03-24 16:49:09.893  3274  3331 I jxcore-log: # setup
03-24 16:49:09.893  3274  3331 I jxcore-log: 
,03-24 16:49:09.993  3274  3331 I jxcore-log: # 76. #parseBeacons addressBookCallback fails decrypt
03-24 16:49:09.993  3274  3331 I jxcore-log: 
,03-24 16:49:10.274  3274  3331 I jxcore-log: ok 257 should be equal
03-24 16:49:10.274  3274  3331 I jxcore-log: 
,03-24 16:49:10.276  3274  3331 I jxcore-log: # teardown
03-24 16:49:10.276  3274  3331 I jxcore-log: 
,03-24 16:49:10.455  3274  3331 I jxcore-log: # setup
03-24 16:49:10.455  3274  3331 I jxcore-log: 
,03-24 16:49:10.581  3274  3331 I jxcore-log: # 77. #parseBeacons addressBookCallback returns no matches
03-24 16:49:10.581  3274  3331 I jxcore-log: 
,03-24 16:49:10.788  3274  3331 I jxcore-log: ok 258 should be equal,
03-24 16:49:10.788  3274  3331 I jxcore-log: 
03-24 16:49:10.789  3274  3331 I jxcore-log: ok 259 should be equal
03-24 16:49:10.789  3274  3331 I jxcore-log: ,
03-24 16:49:10.791  3274  3331 I jxcore-log: # teardown
03-24 16:49:10.791  3274  3331 I jxcore-log: 
,03-24 16:49:11.003  3274  3331 I jxcore-log: # setup,
03-24 16:49:11.003  3274  3331 I jxcore-log: 
,03-24 16:49:11.476  3274  3331 I jxcore-log: # 78. #parseBeacons addressBookCallback returns spurious match,
03-24 16:49:11.476  3274  3331 I jxcore-log: 
,03-24 16:49:11.760  3274  3331 I jxcore-log: ok 260 should be equal,
03-24 16:49:11.760  3274  3331 I jxcore-log: 
03-24 16:49:11.761  3274  3331 I jxcore-log: ok 261 should be equal
03-24 16:49:11.761  3274  3331 I jxcore-log: 
03-24 16:49:11.763  3274  3331 I jxcore-log: # teardown
03-24 16:49:11.763  3274  3331 I jxcore-log: 
,03-24 16:49:11.916  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:49:11.945  3274  3331 I jxcore-log: # setup
03-24 16:49:11.945  3274  3331 I jxcore-log: 
,03-24 16:49:12.090  3274  3331 I jxcore-log: # 79. #parseBeacons addressBookCallback returns public key
03-24 16:49:12.090  3274  3331 I jxcore-log: 
,03-24 16:49:12.424  3274  3331 I jxcore-log: ok 262 right number of calls to address book
03-24 16:49:12.424  3274  3331 I jxcore-log: 
03-24 16:49:12.425  3274  3331 I jxcore-log: ok 263 good preAmble
03-24 16:49:12.425  3274  3331 I jxcore-log: 
03-24 16:49:12.425  3274  3331 I jxcore-log: ok 264 good unencryptedKeyId
,03-24 16:49:12.425  3274  3331 I jxcore-log: 
03-24 16:49:12.425  3274  3331 I jxcore-log: ok 265 good beacon
03-24 16:49:12.425  3274  3331 I jxcore-log: 
03-24 16:49:12.427  3274  3331 I jxcore-log: # teardown
03-24 16:49:12.427  3274  3331 I jxcore-log: 
,03-24 16:49:14.207  3274  3331 I jxcore-log: # setup
03-24 16:49:14.207  3274  3331 I jxcore-log: 
,03-24 16:49:14.401  3274  3331 I jxcore-log: # 80. validate generatePskIdentityField
03-24 16:49:14.401  3274  3331 I jxcore-log: 
,03-24 16:49:15.040  3274  3331 I jxcore-log: ok 266 decoded buffers match
03-24 16:49:15.040  3274  3331 I jxcore-log: 
,03-24 16:49:15.044  3274  3331 I jxcore-log: # teardown
03-24 16:49:15.044  3274  3331 I jxcore-log: 
,03-24 16:49:15.194  3274  3331 I jxcore-log: # setup
03-24 16:49:15.194  3274  3331 I jxcore-log: 
,03-24 16:49:15.741  3274  3331 I jxcore-log: # 81. validate generatePskSecret
03-24 16:49:15.741  3274  3331 I jxcore-log: 
,03-24 16:49:15.952  3274  3331 I jxcore-log: ok 267 secrets match
03-24 16:49:15.952  3274  3331 I jxcore-log: 
,03-24 16:49:15.954  3274  3331 I jxcore-log: # teardown
03-24 16:49:15.954  3274  3331 I jxcore-log: 
,03-24 16:49:16.158  3274  3331 I jxcore-log: # setup
03-24 16:49:16.158  3274  3331 I jxcore-log: 
,03-24 16:49:16.391  3274  3331 I jxcore-log: # 82. Add two Peers.
03-24 16:49:16.391  3274  3331 I jxcore-log: 
,03-24 16:49:17.177  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:17.177  3274  3331 I jxcore-log: 
,03-24 16:49:17.177  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:17.177  3274  3331 I jxcore-log: 
,03-24 16:49:17.178  3274  3331 I jxcore-log: connectionType:AndroidBluetooth
03-24 16:49:17.178  3274  3331 I jxcore-log: 
03-24 16:49:17.178  3274  3331 I jxcore-log: hostAddress:anything
03-24 16:49:17.178  3274  3331 I jxcore-log: 
03-24 16:49:17.178  3274  3331 I jxcore-log: portNumber:8080
03-24 16:49:17.178  3274  3331 I jxcore-log: 
03-24 16:49:17.178  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:17.178  3274  3331 I jxcore-log: 
,03-24 16:49:17.186  3274  3331 I jxcore-log: ok 268 should be equal
03-24 16:49:17.186  3274  3331 I jxcore-log: 
03-24 16:49:17.186  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:17.186  3274  3331 I jxcore-log: 
,03-24 16:49:17.186  3274  3331 I jxcore-log: peerIdentifier:id3212
03-24 16:49:17.186  3274  3331 I jxcore-log: 
03-24 16:49:17.186  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:17.186  3274  3331 I jxcore-log: 
03-24 16:49:17.186  3274  3331 I jxcore-log: hostAddress:anything
03-24 16:49:17.186  3274  3331 I jxcore-log: 
,03-24 16:49:17.186  3274  3331 I jxcore-log: portNumber:8080
03-24 16:49:17.186  3274  3331 I jxcore-log: 
03-24 16:49:17.186  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:17.186  3274  3331 I jxcore-log: 
03-24 16:49:17.189  3274  3331 I jxcore-log: ok 269 should be equal
03-24 16:49:17.189  3274  3331 I jxcore-log: 
,03-24 16:49:17.190  3274  3331 I jxcore-log: ok 270 should be equal
03-24 16:49:17.190  3274  3331 I jxcore-log: 
03-24 16:49:17.190  3274  3331 I jxcore-log: ok 271 should be equal
03-24 16:49:17.190  3274  3331 I jxcore-log: 
,03-24 16:49:17.191  3274  3331 I jxcore-log: ok 272 should be equal
03-24 16:49:17.191  3274  3331 I jxcore-log: 
,03-24 16:49:17.194  3274  3331 I jxcore-log: # teardown
03-24 16:49:17.194  3274  3331 I jxcore-log: 
,03-24 16:49:17.288  3274  3331 I jxcore-log: killed
03-24 16:49:17.288  3274  3331 I jxcore-log: 
,03-24 16:49:17.299  3274  3331 I jxcore-log: # setup,
03-24 16:49:17.299  3274  3331 I jxcore-log: 
,03-24 16:49:17.879  3274  3331 I jxcore-log: # 83. TCP_NATIVE peer loses DNS
03-24 16:49:17.879  3274  3331 I jxcore-log: 
,03-24 16:49:17.937  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:17.937  3274  3331 I jxcore-log: 
,03-24 16:49:17.937  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:17.937  3274  3331 I jxcore-log: 
03-24 16:49:17.937  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:17.937  3274  3331 I jxcore-log: 
03-24 16:49:17.937  3274  3331 I jxcore-log: hostAddress:127.0.0.1
03-24 16:49:17.937  3274  3331 I jxcore-log: 
03-24 16:49:17.937  3274  3331 I jxcore-log: portNumber:58832
,03-24 16:49:17.937  3274  3331 I jxcore-log: 
03-24 16:49:17.937  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:17.937  3274  3331 I jxcore-log: 
03-24 16:49:17.940  3274  3331 I jxcore-log: ok 273 should be equal
03-24 16:49:17.940  3274  3331 I jxcore-log: 
03-24 16:49:17.940  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:17.940  3274  3331 I jxcore-log: ,
03-24 16:49:17.940  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:17.940  3274  3331 I jxcore-log: 
03-24 16:49:17.940  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:17.940  3274  3331 I jxcore-log: 
03-24 16:49:17.940  3274  3331 I jxcore-log: hostAddress:undefined
03-24 16:49:17.940  3274  3331 I jxcore-log: 
,03-24 16:49:17.940  3274  3331 I jxcore-log: portNumber:58832
03-24 16:49:17.940  3274  3331 I jxcore-log: 
03-24 16:49:17.940  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:17.940  3274  3331 I jxcore-log: 
03-24 16:49:17.941  3274  3331 I jxcore-log: ok 274 should be equal
03-24 16:49:17.941  3274  3331 I jxcore-log: 
,03-24 16:49:17.942  3274  3331 I jxcore-log: # teardown
03-24 16:49:17.942  3274  3331 I jxcore-log: 
,03-24 16:49:18.163  3274  3331 I jxcore-log: killed
03-24 16:49:18.163  3274  3331 I jxcore-log: 
,03-24 16:49:18.173  3274  3331 I jxcore-log: # setup
03-24 16:49:18.173  3274  3331 I jxcore-log: 
,03-24 16:49:18.372  3274  3331 I jxcore-log: # 84. Resolves an action locally
,03-24 16:49:18.372  3274  3331 I jxcore-log: 
,03-24 16:49:18.582  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:18.582  3274  3331 I jxcore-log: 
,03-24 16:49:18.582  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:18.582  3274  3331 I jxcore-log: 
03-24 16:49:18.582  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:18.582  3274  3331 I jxcore-log: 
03-24 16:49:18.583  3274  3331 I jxcore-log: hostAddress:127.0.0.1
03-24 16:49:18.583  3274  3331 I jxcore-log: 
,03-24 16:49:18.583  3274  3331 I jxcore-log: portNumber:36942
03-24 16:49:18.583  3274  3331 I jxcore-log: 
03-24 16:49:18.583  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:18.583  3274  3331 I jxcore-log: 
,03-24 16:49:18.642  3274  3331 I jxcore-log: ok 275 Host address must match,
03-24 16:49:18.642  3274  3331 I jxcore-log: 
03-24 16:49:18.643  3274  3331 I jxcore-log: ok 276 suggestedTCPTimeout must match
03-24 16:49:18.643  3274  3331 I jxcore-log: 
03-24 16:49:18.643  3274  3331 I jxcore-log: ok 277 connectionType must match
03-24 16:49:18.643  3274  3331 I jxcore-log: 
,03-24 16:49:18.643  3274  3331 I jxcore-log: ok 278 portNumber must match
03-24 16:49:18.643  3274  3331 I jxcore-log: 
,03-24 16:49:18.649  3274  3331 I jxcore-log: # teardown
03-24 16:49:18.649  3274  3331 I jxcore-log: 
,03-24 16:49:18.811  3274  3331 I jxcore-log: killed
03-24 16:49:18.811  3274  3331 I jxcore-log: 
,03-24 16:49:18.822  3274  3331 I jxcore-log: # setup
03-24 16:49:18.822  3274  3331 I jxcore-log: 
,03-24 16:49:19.038  3274  3331 I jxcore-log: # 85. Resolves an action locally using ThaliPeerPoolDefault
03-24 16:49:19.038  3274  3331 I jxcore-log: 
,03-24 16:49:19.153  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:19.153  3274  3331 I jxcore-log: 
,03-24 16:49:19.154  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:19.154  3274  3331 I jxcore-log: 
03-24 16:49:19.154  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:19.154  3274  3331 I jxcore-log: 
,03-24 16:49:19.154  3274  3331 I jxcore-log: hostAddress:127.0.0.1
03-24 16:49:19.154  3274  3331 I jxcore-log: 
03-24 16:49:19.154  3274  3331 I jxcore-log: portNumber:46071
03-24 16:49:19.154  3274  3331 I jxcore-log: 
,03-24 16:49:19.154  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:19.154  3274  3331 I jxcore-log: 
,03-24 16:49:19.209  3274  3331 I jxcore-log: ok 279 Host address must match
03-24 16:49:19.209  3274  3331 I jxcore-log: 
,03-24 16:49:19.210  3274  3331 I jxcore-log: ok 280 suggestedTCPTimeout must match
03-24 16:49:19.210  3274  3331 I jxcore-log: 
03-24 16:49:19.210  3274  3331 I jxcore-log: ok 281 connectionType must match
03-24 16:49:19.210  3274  3331 I jxcore-log: 
,03-24 16:49:19.210  3274  3331 I jxcore-log: ok 282 portNumber must match
03-24 16:49:19.210  3274  3331 I jxcore-log: 
,03-24 16:49:19.218  3274  3331 I jxcore-log: # teardown
03-24 16:49:19.218  3274  3331 I jxcore-log: 
,03-24 16:49:20.037  3274  3331 I jxcore-log: killed
03-24 16:49:20.037  3274  3331 I jxcore-log: 
,03-24 16:49:20.049  3274  3331 I jxcore-log: # setup
03-24 16:49:20.049  3274  3331 I jxcore-log: 
,03-24 16:49:20.268  3274  3331 I jxcore-log: # 86. Action fails because of a bad hostname.
03-24 16:49:20.268  3274  3331 I jxcore-log: 
,03-24 16:49:20.566  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:20.566  3274  3331 I jxcore-log: 
,03-24 16:49:20.566  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:20.566  3274  3331 I jxcore-log: 
03-24 16:49:20.566  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:20.566  3274  3331 I jxcore-log: 
03-24 16:49:20.566  3274  3331 I jxcore-log: hostAddress:address-that-does-not-exists
03-24 16:49:20.566  3274  3331 I jxcore-log: 
03-24 16:49:20.566  3274  3331 I jxcore-log: portNumber:123
03-24 16:49:20.566  3274  3331 I jxcore-log: 
,03-24 16:49:20.566  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:20.566  3274  3331 I jxcore-log: 
,03-24 16:49:23.700  1349  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 16:49:23.701  1349  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:49:23.701  1349  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:49:23.702  1349  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:49:23.714  1349  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:49:23.765  3093  3891 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-24 16:49:23.765  3093  3891 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	,at jcs.i(PG:143)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at blb.a(PG:3937)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at czp.a(PG:18188)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	,at czp.a(PG:9081)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:49:23.765  3093  3891 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at jdm.a(PG:77)
,03-24 16:49:23.765  3093  3891 E HttpOperation: 	... 12 more
03-24 16:49:23.765  3093  3891 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at fal.a(PG:38)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:49:23.765  3093  3891 E HttpOperation: 	,... 14 more
,03-24 16:49:23.821  1349  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,03-24 16:49:23.821  1349  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:49:23.821  1349  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:49:23.821  1349  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:49:23.825  1349  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:49:23.839  3093  3891 E HttpOperation: [getmobileexperiments] Unexpected exception
03-24 16:49:23.839  3093  3891 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jdm.a(PG:82)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jcs.o(PG:406)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jcn.a(PG:1379)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jcs.i(PG:143)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at hec.a(PG:42)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at hee.a(PG:102)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at czr.a(PG:65)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at kka.a(PG:108)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at czp.a(PG:19176)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at czp.a(PG:9081)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at czq.run(PG:1686)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:49:23.839  3093  3891 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jdj.a(PG:4091)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jdj.a(PG:1125)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jdm.a(PG:77)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	,... 15 more
03-24 16:49:23.839  3093  3891 E HttpOperation: Caused by: faj: BadAuthentication
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at fal.a(PG:38)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	at jdj.a(PG:4089)
03-24 16:49:23.839  3093  3891 E HttpOperation: 	... 17 more
03-24 16:49:23.840  3093  3891 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
03-24 16:49:23.840  3093  3891 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jdm.a(PG:82)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jcs.o(PG:406)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jcn.a(PG:1379)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jcs.i(PG:143)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at hec.a(PG:42)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at hee.a(PG:102)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at czr.a(PG:65)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at kka.a(PG:108)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at czp.a(PG:19176)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at czp.a(PG:9081)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at czq.run(PG:1686)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jdj.a(PG:4091)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jdj.a(PG:1125)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jdm.a(PG:77)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	... 15 more
03-24 16:49:23.840  3093  3891 E ExperimentLoader: Caused by: faj: BadAuthentication
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at fal.a(PG:38)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	at jdj.a(PG:4089)
03-24 16:49:23.840  3093  3891 E ExperimentLoader: 	... 17 more,
,03-24 16:49:23.976   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 350048, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,03-24 16:49:25.574  3274  3331 I jxcore-log: ok 283 should be equal
03-24 16:49:25.574  3274  3331 I jxcore-log: 
,03-24 16:49:25.576  3274  3331 I jxcore-log: ok 284 should be equal
03-24 16:49:25.576  3274  3331 I jxcore-log: 
,03-24 16:49:25.578  3274  3331 I jxcore-log: ok 285 should be equal
03-24 16:49:25.578  3274  3331 I jxcore-log: 
,03-24 16:49:25.598  3274  3331 I jxcore-log: # teardown
03-24 16:49:25.598  3274  3331 I jxcore-log: 
,03-24 16:49:25.761  3274  3331 I jxcore-log: killed
03-24 16:49:25.761  3274  3331 I jxcore-log: 
,03-24 16:49:25.772  3274  3331 I jxcore-log: # setup
03-24 16:49:25.772  3274  3331 I jxcore-log: 
,03-24 16:49:26.005  3274  3331 I jxcore-log: # 87. hostaddress is removed when the action is running. 
,03-24 16:49:26.005  3274  3331 I jxcore-log: 
,03-24 16:49:26.305  3274  3331 I jxcore-log: _peerAvailabilityChanged
,03-24 16:49:26.305  3274  3331 I jxcore-log: 
03-24 16:49:26.305  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:26.305  3274  3331 I jxcore-log: 
03-24 16:49:26.306  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:26.306  3274  3331 I jxcore-log: 
03-24 16:49:26.306  3274  3331 I jxcore-log: hostAddress:127.0.0.1
,03-24 16:49:26.306  3274  3331 I jxcore-log: 
03-24 16:49:26.306  3274  3331 I jxcore-log: portNumber:60491
03-24 16:49:26.306  3274  3331 I jxcore-log: 
03-24 16:49:26.306  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:26.306  3274  3331 I jxcore-log: 
,03-24 16:49:28.310  3274  3331 I jxcore-log: _peerAvailabilityChanged
03-24 16:49:28.310  3274  3331 I jxcore-log: 
,03-24 16:49:28.311  3274  3331 I jxcore-log: peerIdentifier:id123
03-24 16:49:28.311  3274  3331 I jxcore-log: 
,03-24 16:49:28.311  3274  3331 I jxcore-log: connectionType:tcp
03-24 16:49:28.311  3274  3331 I jxcore-log: 
03-24 16:49:28.311  3274  3331 I jxcore-log: hostAddress:undefined
03-24 16:49:28.311  3274  3331 I jxcore-log: 
03-24 16:49:28.312  3274  3331 I jxcore-log: portNumber:60491
03-24 16:49:28.312  3274  3331 I jxcore-log: 
03-24 16:49:28.312  3274  3331 I jxcore-log: _peerAvailabilityChanged - end
03-24 16:49:28.312  3274  3331 I jxcore-log: 
,03-24 16:49:28.318  3274  3331 I jxcore-log: ok 286 should be equal
03-24 16:49:28.318  3274  3331 I jxcore-log: 
,03-24 16:49:28.343  3274  3331 I jxcore-log: # teardown
03-24 16:49:28.343  3274  3331 I jxcore-log: 
,03-24 16:49:28.517  3274  3331 I jxcore-log: killed
03-24 16:49:28.517  3274  3331 I jxcore-log: 
,03-24 16:49:28.524  3274  3331 I jxcore-log: # setup
03-24 16:49:28.524  3274  3331 I jxcore-log: 
,03-24 16:49:28.755  3274  3331 I jxcore-log: # 88. Start and stop ThaliNotificationServer
03-24 16:49:28.755  3274  3331 I jxcore-log: 
,03-24 16:49:29.019  3274  3331 I jxcore-log: ok 287 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
03-24 16:49:29.019  3274  3331 I jxcore-log: 
03-24 16:49:29.020  3274  3331 I jxcore-log: ok 288 ThaliMobile.StopAdvertisingAndListeningshould be called once
03-24 16:49:29.020  3274  3331 I jxcore-log: 
,03-24 16:49:29.023  3274  3331 I jxcore-log: # teardown
03-24 16:49:29.023  3274  3331 I jxcore-log: 
,03-24 16:49:29.222  3274  3331 I jxcore-log: # setup
03-24 16:49:29.222  3274  3331 I jxcore-log: 
,03-24 16:49:29.395  3274  3331 I jxcore-log: # 89. Pass an empty array to ThaliNotificationServer.start
03-24 16:49:29.395  3274  3331 I jxcore-log: 
,03-24 16:49:29.608  3274  3331 I jxcore-log: ok 289 StartUpdateAdvertisingAndListening should not be called
03-24 16:49:29.608  3274  3331 I jxcore-log: 
,03-24 16:49:29.623  3274  3331 I jxcore-log: ok 290 ThaliMobile.StopAdvertisingAndListening should be called once
03-24 16:49:29.623  3274  3331 I jxcore-log: 
,03-24 16:49:29.663  3274  3331 I jxcore-log: ok 291 no error
03-24 16:49:29.663  3274  3331 I jxcore-log: 
,03-24 16:49:29.664  3274  3331 I jxcore-log: ok 292 should be 204
03-24 16:49:29.664  3274  3331 I jxcore-log: 
,03-24 16:49:29.669  3274  3331 I jxcore-log: # teardown
03-24 16:49:29.669  3274  3331 I jxcore-log: 
,03-24 16:49:29.869  3274  3331 I jxcore-log: # setup
03-24 16:49:29.869  3274  3331 I jxcore-log: 
,03-24 16:49:30.033  3274  3331 I jxcore-log: # 90. Pass a string to ThaliNotificationServer.start
03-24 16:49:30.033  3274  3331 I jxcore-log: 
,03-24 16:49:30.964  3274  3331 I jxcore-log: ok 293 StartUpdateAdvertisingAndListening should not be called
03-24 16:49:30.964  3274  3331 I jxcore-log: 
,03-24 16:49:30.966  3274  3331 I jxcore-log: # teardown
03-24 16:49:30.966  3274  3331 I jxcore-log: 
,03-24 16:49:31.255  3274  3331 I jxcore-log: # setup
03-24 16:49:31.255  3274  3331 I jxcore-log: 
,03-24 16:49:32.931  3274  3331 I jxcore-log: # 91. Pass an empty parameter to ThaliNotificationServer.start
03-24 16:49:32.931  3274  3331 I jxcore-log: 
,03-24 16:49:33.143  3274  3331 I jxcore-log: ok 294 StartUpdateAdvertisingAndListening should not be called
03-24 16:49:33.143  3274  3331 I jxcore-log: 
03-24 16:49:33.145  3274  3331 I jxcore-log: # teardown
03-24 16:49:33.145  3274  3331 I jxcore-log: 
,03-24 16:49:33.263  3274  3331 I jxcore-log: # setup
03-24 16:49:33.263  3274  3331 I jxcore-log: 
,03-24 16:49:33.453  3274  3331 I jxcore-log: # 92. Make an HTTP request to /NotificationBeacons
03-24 16:49:33.453  3274  3331 I jxcore-log: 
,03-24 16:49:33.692  3274  3331 I jxcore-log: ok 295 no error
03-24 16:49:33.692  3274  3331 I jxcore-log: 
,03-24 16:49:33.692  3274  3331 I jxcore-log: ok 296 should be 200
03-24 16:49:33.692  3274  3331 I jxcore-log: 
03-24 16:49:33.692  3274  3331 I jxcore-log: ok 297 should be equal
03-24 16:49:33.692  3274  3331 I jxcore-log: 
03-24 16:49:33.693  3274  3331 I jxcore-log: ok 298 should be equal
03-24 16:49:33.693  3274  3331 I jxcore-log: 
,03-24 16:49:33.709  3274  3331 I jxcore-log: ok 299 (unnamed assert)
03-24 16:49:33.709  3274  3331 I jxcore-log: ,
,03-24 16:49:33.732  3274  3331 I jxcore-log: ok 300 no error
03-24 16:49:33.732  3274  3331 I jxcore-log: 
,03-24 16:49:33.733  3274  3331 I jxcore-log: ok 301 should be 204
03-24 16:49:33.733  3274  3331 I jxcore-log: 
,03-24 16:49:33.737  3274  3331 I jxcore-log: # teardown
03-24 16:49:33.737  3274  3331 I jxcore-log: 
,03-24 16:49:33.913  3274  3331 I jxcore-log: # setup
03-24 16:49:33.913  3274  3331 I jxcore-log: 
,03-24 16:49:34.100  3274  3331 I jxcore-log: # 93. Make an HTTP request to /NotificationBeacons (no keys)
03-24 16:49:34.100  3274  3331 I jxcore-log: 
,03-24 16:49:34.278  3274  3331 I jxcore-log: ok 302 error should be null
03-24 16:49:34.278  3274  3331 I jxcore-log: 
,03-24 16:49:34.279  3274  3331 I jxcore-log: ok 303 should be 204
03-24 16:49:34.279  3274  3331 I jxcore-log: 
,03-24 16:49:34.285  3274  3331 I jxcore-log: # teardown
03-24 16:49:34.285  3274  3331 I jxcore-log: 
,03-24 16:49:34.443  3274  3331 I jxcore-log: # setup
03-24 16:49:34.443  3274  3331 I jxcore-log: 
,03-24 16:49:34.613  3274  3331 I jxcore-log: # 94. Make an HTTP request to /NotificationBeaconsbefore calling start
03-24 16:49:34.613  3274  3331 I jxcore-log: 
,03-24 16:49:34.808  3274  3331 I jxcore-log: ok 304 should be 404
03-24 16:49:34.808  3274  3331 I jxcore-log: 
,03-24 16:49:34.817  3274  3331 I jxcore-log: # teardown,
03-24 16:49:34.817  3274  3331 I jxcore-log: 
,03-24 16:49:34.920  3274  3331 I jxcore-log: # setup
03-24 16:49:34.920  3274  3331 I jxcore-log: 
,03-24 16:49:35.051  3274  3331 I jxcore-log: # 95. #testThaliPeerAction - test getters
,03-24 16:49:35.051  3274  3331 I jxcore-log: 
,03-24 16:49:35.222  3274  3331 I jxcore-log: ok 305 getPeerIdentifier
03-24 16:49:35.222  3274  3331 I jxcore-log: 
03-24 16:49:35.223  3274  3331 I jxcore-log: ok 306 getConnectionType
03-24 16:49:35.223  3274  3331 I jxcore-log: 
03-24 16:49:35.223  3274  3331 I jxcore-log: ok 307 getActionType
03-24 16:49:35.223  3274  3331 I jxcore-log: 
03-24 16:49:35.224  3274  3331 I jxcore-log: ok 308 getActionState
03-24 16:49:35.224  3274  3331 I jxcore-log: 
03-24 16:49:35.226  3274  3331 I jxcore-log: # teardown
03-24 16:49:35.226  3274  3331 I jxcore-log: 
,03-24 16:49:35.449  3274  3331 I jxcore-log: # setup
03-24 16:49:35.449  3274  3331 I jxcore-log: 
,03-24 16:49:35.642  3274  3331 I jxcore-log: # 96. #testThaliPeerAction - start and kill
03-24 16:49:35.642  3274  3331 I jxcore-log: 
,03-24 16:49:35.782  3274  3331 I jxcore-log: ok 309 initial state
03-24 16:49:35.782  3274  3331 I jxcore-log: 
,03-24 16:49:35.797  3274  3331 I jxcore-log: ok 310 after start
03-24 16:49:35.797  3274  3331 I jxcore-log: 
,03-24 16:49:35.798  3274  3331 I jxcore-log: ok 311 after kill
03-24 16:49:35.798  3274  3331 I jxcore-log: 
03-24 16:49:35.800  3274  3331 I jxcore-log: # teardown
03-24 16:49:35.800  3274  3331 I jxcore-log: 
,03-24 16:49:35.945  3274  3331 I jxcore-log: # setup
03-24 16:49:35.945  3274  3331 I jxcore-log: ,
,03-24 16:49:36.044  3274  3331 I jxcore-log: # 97. #testThaliPeerAction - double start
03-24 16:49:36.044  3274  3331 I jxcore-log: 
,03-24 16:49:36.255  3274  3331 I jxcore-log: ok 312 should be equal
03-24 16:49:36.255  3274  3331 I jxcore-log: 
,03-24 16:49:36.258  3274  3331 I jxcore-log: # teardown
03-24 16:49:36.258  3274  3331 I jxcore-log: 
,03-24 16:49:36.411  3274  3331 I jxcore-log: # setup
03-24 16:49:36.411  3274  3331 I jxcore-log: 
,03-24 16:49:36.577  3274  3331 I jxcore-log: # 98. #testThaliPeerAction - start after kill
03-24 16:49:36.577  3274  3331 I jxcore-log: 
,03-24 16:49:36.789  3274  3331 I jxcore-log: ok 313 clean kill
03-24 16:49:36.789  3274  3331 I jxcore-log: 
,03-24 16:49:36.799  3274  3331 I jxcore-log: ok 314 should be equal
03-24 16:49:36.799  3274  3331 I jxcore-log: 
,03-24 16:49:36.804  3274  3331 I jxcore-log: # teardown
03-24 16:49:36.804  3274  3331 I jxcore-log: 
,03-24 16:49:36.942  3274  3331 I jxcore-log: # setup
03-24 16:49:36.942  3274  3331 I jxcore-log: 
,03-24 16:49:37.049  3274  3331 I jxcore-log: # 99. #testThaliPeerAction - make sure ids are unique
03-24 16:49:37.049  3274  3331 I jxcore-log: 
,03-24 16:49:37.179  3274  3331 I jxcore-log: ok 315 should not be equal
03-24 16:49:37.179  3274  3331 I jxcore-log: 
,03-24 16:49:37.184  3274  3331 I jxcore-log: # teardown
03-24 16:49:37.184  3274  3331 I jxcore-log: 
,03-24 16:49:37.285  3274  3331 I jxcore-log: # setup
03-24 16:49:37.285  3274  3331 I jxcore-log: 
,03-24 16:49:37.454  3274  3331 I jxcore-log: # 100. Test PeerConnectionInformation basics
03-24 16:49:37.454  3274  3331 I jxcore-log: 
,03-24 16:49:37.631  3274  3331 I jxcore-log: ok 316 connection type works
03-24 16:49:37.631  3274  3331 I jxcore-log: 
,03-24 16:49:37.633  3274  3331 I jxcore-log: ok 317 getHostAddress works
03-24 16:49:37.633  3274  3331 I jxcore-log: 
,03-24 16:49:37.635  3274  3331 I jxcore-log: ok 318 getPortNumber works
03-24 16:49:37.635  3274  3331 I jxcore-log: 
03-24 16:49:37.636  3274  3331 I jxcore-log: ok 319 getSuggestedTCPTimeout works
03-24 16:49:37.636  3274  3331 I jxcore-log: 
,03-24 16:49:37.643  3274  3331 I jxcore-log: # teardown
03-24 16:49:37.643  3274  3331 I jxcore-log: 
,03-24 16:49:37.808  3274  3331 I jxcore-log: # setup
03-24 16:49:37.808  3274  3331 I jxcore-log: 
,03-24 16:49:37.966  3274  3331 I jxcore-log: # 101. Test PeerDictionary basic functionality
03-24 16:49:37.966  3274  3331 I jxcore-log: 
,03-24 16:49:38.082  3274  3331 I jxcore-log: ok 320 Entry counter must be 1
03-24 16:49:38.082  3274  3331 I jxcore-log: 
03-24 16:49:38.083  3274  3331 I jxcore-log: ok 321 Size must be 1
03-24 16:49:38.083  3274  3331 I jxcore-log: 
,03-24 16:49:38.083  3274  3331 I jxcore-log: ok 322 Entry counter must be 2
03-24 16:49:38.083  3274  3331 I jxcore-log: 
,03-24 16:49:38.087  3274  3331 I jxcore-log: ok 323 Size must be 2
03-24 16:49:38.087  3274  3331 I jxcore-log: 
,03-24 16:49:38.093  3274  3331 I jxcore-log: ok 324 Entry2 should not be found
03-24 16:49:38.093  3274  3331 I jxcore-log: 
03-24 16:49:38.094  3274  3331 I jxcore-log: ok 325 Size must be 1
03-24 16:49:38.094  3274  3331 I jxcore-log: 
,03-24 16:49:38.094  3274  3331 I jxcore-log: ok 326 Size must be 0
03-24 16:49:38.094  3274  3331 I jxcore-log: 
,03-24 16:49:38.097  3274  3331 I jxcore-log: # teardown
03-24 16:49:38.097  3274  3331 I jxcore-log: 
,03-24 16:49:38.253  3274  3331 I jxcore-log: # setup
03-24 16:49:38.253  3274  3331 I jxcore-log: 
,03-24 16:49:38.415  3274  3331 I jxcore-log: # 102. Test PeerDictionary with multiple entries.
03-24 16:49:38.415  3274  3331 I jxcore-log: 
,03-24 16:49:39.290  3274  3331 I jxcore-log: ok 327 Size must be100
03-24 16:49:39.290  3274  3331 I jxcore-log: 
,03-24 16:49:39.293  3274  3331 I jxcore-log: ok 328 Entries between 20 and MAXSIZE + 20 should exist
03-24 16:49:39.293  3274  3331 I jxcore-log: 
,03-24 16:49:40.002  3274  3331 I jxcore-log: ok 329 WAITING state entry should not be removed
03-24 16:49:40.002  3274  3331 I jxcore-log: 
,03-24 16:49:40.004  3274  3331 I jxcore-log: # teardown
03-24 16:49:40.004  3274  3331 I jxcore-log: 
,03-24 16:49:40.115  3274  3331 I jxcore-log: # setup
03-24 16:49:40.115  3274  3331 I jxcore-log: 
,03-24 16:49:40.325  3274  3331 I jxcore-log: # 103. RESOLVED entries are removed before WAITING state entry.
03-24 16:49:40.325  3274  3331 I jxcore-log: 
,03-24 16:49:40.441  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:49:41.081  3274  3331 I jxcore-log: ok 330 Entries between 6 and MAXSIZE + 4 should exist
03-24 16:49:41.081  3274  3331 I jxcore-log: 
,03-24 16:49:41.081  3274  3331 I jxcore-log: ok 331 Size should be MAXSIZE
03-24 16:49:41.081  3274  3331 I jxcore-log: 
03-24 16:49:41.081  3274  3331 I jxcore-log: ok 332 Size should be MAXSIZE+6
03-24 16:49:41.081  3274  3331 I jxcore-log: 
03-24 16:49:41.083  3274  3331 I jxcore-log: # teardown
03-24 16:49:41.083  3274  3331 I jxcore-log: 
,03-24 16:49:41.422  3274  3331 I jxcore-log: # setup
03-24 16:49:41.422  3274  3331 I jxcore-log: 
,03-24 16:49:42.302  3274  3331 I jxcore-log: # 104. WAITING entries are removed before CONTROLLED_BY_POOL state entry.,
03-24 16:49:42.302  3274  3331 I jxcore-log: 
,03-24 16:49:43.098  3274  3331 I jxcore-log: ok 333 WAITING state entry should not be removed,
03-24 16:49:43.098  3274  3331 I jxcore-log: 
03-24 16:49:43.100  3274  3331 I jxcore-log: ok 334 Waiting entries between 6 and MAXSIZE + 4 should exist
03-24 16:49:43.100  3274  3331 I jxcore-log: 
03-24 16:49:43.100  3274  3331 I jxcore-log: ok 335 Size should be MAXSIZE
03-24 16:49:43.100  3274  3331 I jxcore-log: 
,03-24 16:49:43.101  3274  3331 I jxcore-log: ok 336 entryCounter should be MAXSIZE+6
03-24 16:49:43.101  3274  3331 I jxcore-log: 
03-24 16:49:43.103  3274  3331 I jxcore-log: # teardown
03-24 16:49:43.103  3274  3331 I jxcore-log: 
,03-24 16:49:43.333  3274  3331 I jxcore-log: # setup
03-24 16:49:43.333  3274  3331 I jxcore-log: 
,03-24 16:49:43.503  3274  3331 I jxcore-log: # 105. When CONTROLLED_BY_POOL entry is removed and kill is called.
03-24 16:49:43.503  3274  3331 I jxcore-log: 
,03-24 16:49:44.280  3274  3331 I jxcore-log: ok 337 Kill should be called once
03-24 16:49:44.280  3274  3331 I jxcore-log: 
,03-24 16:49:44.281  3274  3331 I jxcore-log: ok 338 Size should be 100
03-24 16:49:44.281  3274  3331 I jxcore-log: 
03-24 16:49:44.282  3274  3331 I jxcore-log: # teardown
03-24 16:49:44.282  3274  3331 I jxcore-log: 
,03-24 16:49:44.466  3274  3331 I jxcore-log: # setup
03-24 16:49:44.466  3274  3331 I jxcore-log: 
,03-24 16:49:44.777  3274  3331 I jxcore-log: # 106. #ThaliPeerPoolInterface - bad enqueues,
03-24 16:49:44.777  3274  3331 I jxcore-log: 
,03-24 16:49:44.983  3274  3331 I jxcore-log: ok 339 null arg,
03-24 16:49:44.983  3274  3331 I jxcore-log: 
03-24 16:49:44.984  3274  3331 I jxcore-log: ok 340 wrong arg type
03-24 16:49:44.984  3274  3331 I jxcore-log: 
,03-24 16:49:44.985  3274  3331 I jxcore-log: ok 341 wrong state
03-24 16:49:44.985  3274  3331 I jxcore-log: 
03-24 16:49:44.987  3274  3331 I jxcore-log: # teardown
03-24 16:49:44.987  3274  3331 I jxcore-log: 
,03-24 16:49:45.165  3274  3331 I jxcore-log: # setup
03-24 16:49:45.165  3274  3331 I jxcore-log: 
,03-24 16:49:45.334  3274  3331 I jxcore-log: # 107. #ThaliPeerPoolInterface - do not allow same object type
03-24 16:49:45.334  3274  3331 I jxcore-log: 
,03-24 16:49:45.531  3274  3331 I jxcore-log: ok 342 good enqueue
03-24 16:49:45.531  3274  3331 I jxcore-log: 
,03-24 16:49:45.536  3274  3331 I jxcore-log: ok 343 should be equal
03-24 16:49:45.536  3274  3331 I jxcore-log: 
,03-24 16:49:45.543  3274  3331 I jxcore-log: # teardown
03-24 16:49:45.543  3274  3331 I jxcore-log: 
,03-24 16:49:45.745  3274  3331 I jxcore-log: # setup
03-24 16:49:45.745  3274  3331 I jxcore-log: 
,03-24 16:49:45.930  3274  3331 I jxcore-log: # 108. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
03-24 16:49:45.930  3274  3331 I jxcore-log: 
,03-24 16:49:46.102  3274  3331 I jxcore-log: ok 344 good enqueue
03-24 16:49:46.102  3274  3331 I jxcore-log: 
,03-24 16:49:46.103  3274  3331 I jxcore-log: ok 345 2nd good enqueue
03-24 16:49:46.103  3274  3331 I jxcore-log: 
03-24 16:49:46.103  3274  3331 I jxcore-log: ok 346 we are in the pool
03-24 16:49:46.103  3274  3331 I jxcore-log: 
,03-24 16:49:46.105  3274  3331 I jxcore-log: ok 347 We are out of the pool
03-24 16:49:46.105  3274  3331 I jxcore-log: 
,03-24 16:49:46.106  3274  3331 I jxcore-log: ok 348 Action was killed
03-24 16:49:46.106  3274  3331 I jxcore-log: 
,03-24 16:49:46.106  3274  3331 I jxcore-log: ok 349 The original kill was called too
03-24 16:49:46.106  3274  3331 I jxcore-log: 
03-24 16:49:46.107  3274  3331 I jxcore-log: ok 350 second item is still in queue
03-24 16:49:46.107  3274  3331 I jxcore-log: 
03-24 16:49:46.109  3274  3331 I jxcore-log: # teardown
03-24 16:49:46.109  3274  3331 I jxcore-log: 
,03-24 16:49:46.258  3274  3331 I jxcore-log: # setup
03-24 16:49:46.258  3274  3331 I jxcore-log: ,
,03-24 16:49:46.403  3274  3331 I jxcore-log: # 109. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
03-24 16:49:46.403  3274  3331 I jxcore-log: 
,03-24 16:49:46.551  3274  3331 I jxcore-log: ok 351 good enqueue
03-24 16:49:46.551  3274  3331 I jxcore-log: 
03-24 16:49:46.553  3274  3331 I jxcore-log: ok 352 first kill
03-24 16:49:46.553  3274  3331 I jxcore-log: 
,03-24 16:49:46.554  3274  3331 I jxcore-log: ok 353 second NOOP kill
03-24 16:49:46.554  3274  3331 I jxcore-log: 
03-24 16:49:46.562  3274  3331 I jxcore-log: # teardown
03-24 16:49:46.562  3274  3331 I jxcore-log: 
,03-24 16:49:46.848  3274  3331 I jxcore-log: # setup
03-24 16:49:46.848  3274  3331 I jxcore-log: 
,03-24 16:49:46.966  3274  3331 I jxcore-log: # 110. compareBufferArrays
03-24 16:49:46.966  3274  3331 I jxcore-log: 
,03-24 16:49:47.123  3274  3331 I jxcore-log: ok 354 should throw
03-24 16:49:47.123  3274  3331 I jxcore-log: 
03-24 16:49:47.124  3274  3331 I jxcore-log: ok 355 should throw
03-24 16:49:47.124  3274  3331 I jxcore-log: 
03-24 16:49:47.125  3274  3331 I jxcore-log: ok 356 (unnamed assert),
03-24 16:49:47.125  3274  3331 I jxcore-log: 
03-24 16:49:47.125  3274  3331 I jxcore-log: ok 357 (unnamed assert)
03-24 16:49:47.125  3274  3331 I jxcore-log: 
03-24 16:49:47.126  3274  3331 I jxcore-log: ok 358 (unnamed assert)
03-24 16:49:47.126  3274  3331 I jxcore-log: 
03-24 16:49:47.126  3274  3331 I jxcore-log: ok 359 (unnamed assert)
03-24 16:49:47.126  3274  3331 I jxcore-log: 
03-24 16:49:47.127  3274  3331 I jxcore-log: ok 360 (unnamed assert),
03-24 16:49:47.127  3274  3331 I jxcore-log: 
03-24 16:49:47.129  3274  3331 I jxcore-log: # teardown
03-24 16:49:47.129  3274  3331 I jxcore-log: 
,03-24 16:49:47.283  3274  3331 I jxcore-log: # setup
,03-24 16:49:47.283  3274  3331 I jxcore-log: 
,03-24 16:49:47.463  3274  3331 I jxcore-log: # 111. Call start twice and get error
03-24 16:49:47.463  3274  3331 I jxcore-log: 
,03-24 16:49:47.623  3274  3331 I jxcore-log: ok 361 should throw
03-24 16:49:47.623  3274  3331 I jxcore-log: 
,03-24 16:49:47.626  3274  3331 I jxcore-log: # teardown
03-24 16:49:47.626  3274  3331 I jxcore-log: 
,03-24 16:49:47.784  3274  3331 I jxcore-log: # setup
03-24 16:49:47.784  3274  3331 I jxcore-log: 
,03-24 16:49:48.031  3274  3331 I jxcore-log: # 112. Start and make sure it runs
03-24 16:49:48.031  3274  3331 I jxcore-log: 
,03-24 16:49:48.166  3274  3331 I jxcore-log: # teardown
03-24 16:49:48.166  3274  3331 I jxcore-log: ,
,03-24 16:49:48.293  3274  3331 I jxcore-log: # setup
03-24 16:49:48.293  3274  3331 I jxcore-log: ,
,03-24 16:49:48.395  3274  3331 I jxcore-log: # 113. Make sure getTimeWhenRun is right after start
03-24 16:49:48.395  3274  3331 I jxcore-log: 
,03-24 16:49:48.520  3274  3331 I jxcore-log: ok 362 (unnamed assert)
03-24 16:49:48.520  3274  3331 I jxcore-log: 
,03-24 16:49:48.524  3274  3331 I jxcore-log: # teardown
03-24 16:49:48.524  3274  3331 I jxcore-log: 
,03-24 16:49:48.682  3274  3331 I jxcore-log: # setup
03-24 16:49:48.682  3274  3331 I jxcore-log: 
,03-24 16:49:48.833  3274  3331 I jxcore-log: # 114. Make sure getTimeWhenRun is -1 after function is called,
03-24 16:49:48.833  3274  3331 I jxcore-log: 
,03-24 16:49:48.983  3274  3331 I jxcore-log: ok 363 should be equal,
03-24 16:49:48.983  3274  3331 I jxcore-log: 
03-24 16:49:48.988  3274  3331 I jxcore-log: # teardown
03-24 16:49:48.988  3274  3331 I jxcore-log: 
,03-24 16:49:49.099  3274  3331 I jxcore-log: # setup,
03-24 16:49:49.099  3274  3331 I jxcore-log: 
,03-24 16:49:49.272  3274  3331 I jxcore-log: # 115. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running,
03-24 16:49:49.272  3274  3331 I jxcore-log: 
,03-24 16:49:49.435  3274  3331 I jxcore-log: ok 364 should be equal,
03-24 16:49:49.435  3274  3331 I jxcore-log: 
03-24 16:49:49.437  3274  3331 I jxcore-log: ok 365 should be equal
03-24 16:49:49.437  3274  3331 I jxcore-log: 
,03-24 16:49:49.444  3274  3331 I jxcore-log: ok 366 should throw
03-24 16:49:49.444  3274  3331 I jxcore-log: 
,03-24 16:49:49.446  3274  3331 I jxcore-log: # teardown
03-24 16:49:49.446  3274  3331 I jxcore-log: 
,03-24 16:49:49.585  3274  3331 I jxcore-log: # setup
,03-24 16:49:49.585  3274  3331 I jxcore-log: 
,03-24 16:49:49.687  3274  3331 I jxcore-log: # 116. Test TransientState
03-24 16:49:49.687  3274  3331 I jxcore-log: 
,03-24 16:49:49.807  3274  3331 I jxcore-log: ok 367 should throw
03-24 16:49:49.807  3274  3331 I jxcore-log: 
,03-24 16:49:49.814  3274  3331 I jxcore-log: ok 368 should throw
03-24 16:49:49.814  3274  3331 I jxcore-log: 
,03-24 16:49:49.816  3274  3331 I jxcore-log: ok 369 should be equal
03-24 16:49:49.816  3274  3331 I jxcore-log: 
,03-24 16:49:49.818  3274  3331 I jxcore-log: ok 370 should be equal
03-24 16:49:49.818  3274  3331 I jxcore-log: 
,03-24 16:49:49.819  3274  3331 I jxcore-log: ok 371 should be equal
03-24 16:49:49.819  3274  3331 I jxcore-log: 
,03-24 16:49:49.821  3274  3331 I jxcore-log: ok 372 should be equal
03-24 16:49:49.821  3274  3331 I jxcore-log: 
,03-24 16:49:49.823  3274  3331 I jxcore-log: ok 373 (unnamed assert)
03-24 16:49:49.823  3274  3331 I jxcore-log: 
03-24 16:49:49.823  3274  3331 I jxcore-log: ok 374 (unnamed assert)
03-24 16:49:49.823  3274  3331 I jxcore-log: 
03-24 16:49:49.826  3274  3331 I jxcore-log: # teardown
03-24 16:49:49.826  3274  3331 I jxcore-log: 
,03-24 16:49:49.941  3274  3331 I jxcore-log: # setup
03-24 16:49:49.941  3274  3331 I jxcore-log: 
,03-24 16:49:50.039  3274  3331 I jxcore-log: # 117. No peers and empty database
03-24 16:49:50.039  3274  3331 I jxcore-log: 
,03-24 16:49:50.367  3274  3331 I jxcore-log: ok 375 verify failed
03-24 16:49:50.367  3274  3331 I jxcore-log: 
,03-24 16:49:50.367  3274  3331 I jxcore-log: ok 376 constructor called once
03-24 16:49:50.367  3274  3331 I jxcore-log: 
,03-24 16:49:50.369  3274  3331 I jxcore-log: ok 377 constructor called with right args
03-24 16:49:50.369  3274  3331 I jxcore-log: 
03-24 16:49:50.370  3274  3331 I jxcore-log: ok 378 match start arg
03-24 16:49:50.370  3274  3331 I jxcore-log: 
03-24 16:49:50.370  3274  3331 I jxcore-log: ok 379 start called once
03-24 16:49:50.370  3274  3331 I jxcore-log: 
,03-24 16:49:50.370  3274  3331 I jxcore-log: ok 380 stop called once
03-24 16:49:50.370  3274  3331 I jxcore-log: 
03-24 16:49:50.371  3274  3331 I jxcore-log: ok 381 stop after start
03-24 16:49:50.371  3274  3331 I jxcore-log: 
,03-24 16:49:50.376  3274  3331 I jxcore-log: # teardown
03-24 16:49:50.376  3274  3331 I jxcore-log: 
,03-24 16:49:50.913  3274  3331 I jxcore-log: # setup
03-24 16:49:50.913  3274  3331 I jxcore-log: 
,03-24 16:49:55.416  3274  3331 I jxcore-log: # 118. One peer and empty DB
03-24 16:49:55.416  3274  3331 I jxcore-log: 
,03-24 16:49:55.773  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:49:55.773  3274  3331 I jxcore-log: 
,03-24 16:49:55.774  3274  3331 I jxcore-log: ok 382 verify failed
03-24 16:49:55.774  3274  3331 I jxcore-log: 
03-24 16:49:55.775  3274  3331 I jxcore-log: ok 383 constructor called once
03-24 16:49:55.775  3274  3331 I jxcore-log: 
03-24 16:49:55.775  3274  3331 I jxcore-log: ok 384 constructor called with right args
03-24 16:49:55.775  3274  3331 I jxcore-log: 
,03-24 16:49:55.783  3274  3331 I jxcore-log: ok 385 match start arg
03-24 16:49:55.783  3274  3331 I jxcore-log: 
,03-24 16:49:55.786  3274  3331 I jxcore-log: ok 386 start called once
03-24 16:49:55.786  3274  3331 I jxcore-log: 
,03-24 16:49:55.788  3274  3331 I jxcore-log: ok 387 stop called once
03-24 16:49:55.788  3274  3331 I jxcore-log: 
,03-24 16:49:55.791  3274  3331 I jxcore-log: ok 388 stop after start
,03-24 16:49:55.791  3274  3331 I jxcore-log: 
03-24 16:49:55.796  3274  3331 I jxcore-log: # teardown
03-24 16:49:55.796  3274  3331 I jxcore-log: 
,03-24 16:49:56.635  3274  3331 I jxcore-log: # setup
03-24 16:49:56.635  3274  3331 I jxcore-log: 
,03-24 16:49:56.816  3274  3331 I jxcore-log: # 119. One peer with _Local set behind current seq
03-24 16:49:56.816  3274  3331 I jxcore-log: 
,03-24 16:49:57.696  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:49:57.696  3274  3331 I jxcore-log: 
03-24 16:49:57.697  3274  3331 I jxcore-log: ok 389 verify failed
03-24 16:49:57.697  3274  3331 I jxcore-log: 
03-24 16:49:57.698  3274  3331 I jxcore-log: ok 390 constructor called once
03-24 16:49:57.698  3274  3331 I jxcore-log: 
,03-24 16:49:57.700  3274  3331 I jxcore-log: ok 391 constructor called with right args
03-24 16:49:57.700  3274  3331 I jxcore-log: 
,03-24 16:49:57.701  3274  3331 I jxcore-log: ok 392 match start arg
03-24 16:49:57.701  3274  3331 I jxcore-log: 
,03-24 16:49:57.701  3274  3331 I jxcore-log: ok 393 start called once
03-24 16:49:57.701  3274  3331 I jxcore-log: 
,03-24 16:49:57.701  3274  3331 I jxcore-log: ok 394 stop called once
03-24 16:49:57.701  3274  3331 I jxcore-log: 
,03-24 16:49:57.702  3274  3331 I jxcore-log: ok 395 stop after start
03-24 16:49:57.702  3274  3331 I jxcore-log: 
03-24 16:49:57.706  3274  3331 I jxcore-log: # teardown
03-24 16:49:57.706  3274  3331 I jxcore-log: 
,03-24 16:49:57.849  3274  3331 I jxcore-log: # setup
03-24 16:49:57.849  3274  3331 I jxcore-log: 
,03-24 16:49:58.152  3274  3331 I jxcore-log: # 120. One peer with _Local set equal to current seq
03-24 16:49:58.152  3274  3331 I jxcore-log: 
,03-24 16:49:58.484  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:49:58.484  3274  3331 I jxcore-log: ,
03-24 16:49:58.485  3274  3331 I jxcore-log: ok 396 verify failed
03-24 16:49:58.485  3274  3331 I jxcore-log: 
03-24 16:49:58.486  3274  3331 I jxcore-log: ok 397 constructor called once
03-24 16:49:58.486  3274  3331 I jxcore-log: 
,03-24 16:49:58.486  3274  3331 I jxcore-log: ok 398 constructor called with right args
03-24 16:49:58.486  3274  3331 I jxcore-log: 
03-24 16:49:58.487  3274  3331 I jxcore-log: ok 399 match start arg
03-24 16:49:58.487  3274  3331 I jxcore-log: 
03-24 16:49:58.487  3274  3331 I jxcore-log: ok 400 start called once
03-24 16:49:58.487  3274  3331 I jxcore-log: 
03-24 16:49:58.487  3274  3331 I jxcore-log: ok 401 stop called once
03-24 16:49:58.487  3274  3331 I jxcore-log: 
,03-24 16:49:58.487  3274  3331 I jxcore-log: ok 402 stop after start
03-24 16:49:58.487  3274  3331 I jxcore-log: 
03-24 16:49:58.492  3274  3331 I jxcore-log: # teardown
03-24 16:49:58.492  3274  3331 I jxcore-log: 
,03-24 16:49:58.652  3274  3331 I jxcore-log: # setup
03-24 16:49:58.652  3274  3331 I jxcore-log: 
,03-24 16:49:59.302  3274  3331 I jxcore-log: # 121. One peer with _Local set ahead of current seq (and no this should not happen)
03-24 16:49:59.302  3274  3331 I jxcore-log: 
,03-24 16:49:59.670  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:49:59.670  3274  3331 I jxcore-log: 
,03-24 16:49:59.672  3274  3331 I jxcore-log: ok 403 verify failed
03-24 16:49:59.672  3274  3331 I jxcore-log: 
,03-24 16:49:59.672  3274  3331 I jxcore-log: ok 404 constructor called once
03-24 16:49:59.672  3274  3331 I jxcore-log: 
,03-24 16:49:59.672  3274  3331 I jxcore-log: ok 405 constructor called with right args
03-24 16:49:59.672  3274  3331 I jxcore-log: 
03-24 16:49:59.673  3274  3331 I jxcore-log: ok 406 match start arg
03-24 16:49:59.673  3274  3331 I jxcore-log: 
03-24 16:49:59.673  3274  3331 I jxcore-log: ok 407 start called once
03-24 16:49:59.673  3274  3331 I jxcore-log: 
03-24 16:49:59.673  3274  3331 I jxcore-log: ok 408 stop called once
03-24 16:49:59.673  3274  3331 I jxcore-log: 
03-24 16:49:59.673  3274  3331 I jxcore-log: ok 409 stop after start
03-24 16:49:59.673  3274  3331 I jxcore-log: 
,03-24 16:49:59.678  3274  3331 I jxcore-log: # teardown
03-24 16:49:59.678  3274  3331 I jxcore-log: 
,03-24 16:50:00.075  3274  3331 I jxcore-log: # setup
03-24 16:50:00.075  3274  3331 I jxcore-log: 
,03-24 16:50:01.349  3274  3331 I jxcore-log: # 122. Three peers, one not in DB, one behind and one ahead
03-24 16:50:01.349  3274  3331 I jxcore-log: 
,03-24 16:50:02.479  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:02.479  3274  3331 I jxcore-log: 
,03-24 16:50:02.482  3274  3331 I jxcore-log: ok 410 verify failed
03-24 16:50:02.482  3274  3331 I jxcore-log: 
,03-24 16:50:02.483  3274  3331 I jxcore-log: ok 411 constructor called once
03-24 16:50:02.483  3274  3331 I jxcore-log: 
03-24 16:50:02.483  3274  3331 I jxcore-log: ok 412 constructor called with right args
03-24 16:50:02.483  3274  3331 I jxcore-log: 
03-24 16:50:02.484  3274  3331 I jxcore-log: ok 413 match start arg
03-24 16:50:02.484  3274  3331 I jxcore-log: 
,03-24 16:50:02.484  3274  3331 I jxcore-log: ok 414 start called once
03-24 16:50:02.484  3274  3331 I jxcore-log: 
,03-24 16:50:02.484  3274  3331 I jxcore-log: ok 415 stop called once
03-24 16:50:02.484  3274  3331 I jxcore-log: 
03-24 16:50:02.484  3274  3331 I jxcore-log: ok 416 stop after start
03-24 16:50:02.484  3274  3331 I jxcore-log: 
,03-24 16:50:02.490  3274  3331 I jxcore-log: # teardown
03-24 16:50:02.490  3274  3331 I jxcore-log: 
,03-24 16:50:02.595  3274  3331 I jxcore-log: # setup
03-24 16:50:02.595  3274  3331 I jxcore-log: 
,03-24 16:50:03.192  3274  3331 I jxcore-log: # 123. More than maximum peers, make sure we only send maximum allowed
03-24 16:50:03.192  3274  3331 I jxcore-log: 
,03-24 16:50:03.959  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:03.959  3274  3331 I jxcore-log: ,
03-24 16:50:03.961  3274  3331 I jxcore-log: ok 417 verify failed
03-24 16:50:03.961  3274  3331 I jxcore-log: 
,03-24 16:50:03.961  3274  3331 I jxcore-log: ok 418 constructor called once
03-24 16:50:03.961  3274  3331 I jxcore-log: 
,03-24 16:50:03.962  3274  3331 I jxcore-log: ok 419 constructor called with right args
03-24 16:50:03.962  3274  3331 I jxcore-log: 
03-24 16:50:03.962  3274  3331 I jxcore-log: ok 420 match start arg
03-24 16:50:03.962  3274  3331 I jxcore-log: 
03-24 16:50:03.963  3274  3331 I jxcore-log: ok 421 start called once
03-24 16:50:03.963  3274  3331 I jxcore-log: 
03-24 16:50:03.963  3274  3331 I jxcore-log: ok 422 stop called once
03-24 16:50:03.963  3274  3331 I jxcore-log: 
,03-24 16:50:03.963  3274  3331 I jxcore-log: ok 423 stop after start
03-24 16:50:03.963  3274  3331 I jxcore-log: 
03-24 16:50:03.968  3274  3331 I jxcore-log: # teardown
03-24 16:50:03.968  3274  3331 I jxcore-log: 
,03-24 16:50:04.832  3274  3331 I jxcore-log: # setup
03-24 16:50:04.832  3274  3331 I jxcore-log: 
,03-24 16:50:04.953  3274  3331 I jxcore-log: # 124. two peers with empty DB, update the doc
03-24 16:50:04.953  3274  3331 I jxcore-log: 
,03-24 16:50:06.134  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:06.134  3274  3331 I jxcore-log: 
,03-24 16:50:06.172  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:06.172  3274  3331 I jxcore-log: 
,03-24 16:50:06.173  3274  3331 I jxcore-log: ok 424 verify failed
03-24 16:50:06.173  3274  3331 I jxcore-log: 
03-24 16:50:06.174  3274  3331 I jxcore-log: ok 425 constructor called once
03-24 16:50:06.174  3274  3331 I jxcore-log: 
03-24 16:50:06.174  3274  3331 I jxcore-log: ok 426 constructor called with right args
03-24 16:50:06.174  3274  3331 I jxcore-log: 
03-24 16:50:06.174  3274  3331 I jxcore-log: ok 427 last start before stop
03-24 16:50:06.174  3274  3331 I jxcore-log: 
,03-24 16:50:06.175  3274  3331 I jxcore-log: ok 428 empty first start
03-24 16:50:06.175  3274  3331 I jxcore-log: 
03-24 16:50:06.176  3274  3331 I jxcore-log: ok 429 full second start
03-24 16:50:06.176  3274  3331 I jxcore-log: 
03-24 16:50:06.176  3274  3331 I jxcore-log: ok 430 only 2 timers
03-24 16:50:06.176  3274  3331 I jxcore-log: 
03-24 16:50:06.180  3274  3331 I jxcore-log: # teardown
03-24 16:50:06.180  3274  3331 I jxcore-log: 
,03-24 16:50:06.264  3274  3331 I jxcore-log: # setup
03-24 16:50:06.264  3274  3331 I jxcore-log: 
,03-24 16:50:06.401  3274  3331 I jxcore-log: # 125. add doc and make sure tokens refresh when they expire
03-24 16:50:06.401  3274  3331 I jxcore-log: 
,03-24 16:50:06.916  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:06.916  3274  3331 I jxcore-log: 
,03-24 16:50:07.046  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:07.046  3274  3331 I jxcore-log: 
,03-24 16:50:07.152  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 16:50:07.152  3274  3331 I jxcore-log: 
,03-24 16:50:07.162  3274  3331 I jxcore-log: ok 431 verify failed
03-24 16:50:07.162  3274  3331 I jxcore-log: 
,03-24 16:50:07.163  3274  3331 I jxcore-log: ok 432 constructor called once
,03-24 16:50:07.163  3274  3331 I jxcore-log: 
,03-24 16:50:07.163  3274  3331 I jxcore-log: ok 433 constructor called with right args
03-24 16:50:07.163  3274  3331 I jxcore-log: 
,03-24 16:50:07.164  3274  3331 I jxcore-log: ok 434 start before stop,
03-24 16:50:07.164  3274  3331 I jxcore-log: 
03-24 16:50:07.165  3274  3331 I jxcore-log: ok 435 We got at least 3 calls to start
03-24 16:50:07.165  3274  3331 I jxcore-log: 
03-24 16:50:07.165  3274  3331 I jxcore-log: ok 436 at least 3
03-24 16:50:07.165  3274  3331 I jxcore-log: 
03-24 16:50:07.165  3274  3331 I jxcore-log: ok 437 default 1
03-24 16:50:07.165  3274  3331 I jxcore-log: 
,03-24 16:50:07.166  3274  3331 I jxcore-log: ok 438 1 run
03-24 16:50:07.166  3274  3331 I jxcore-log: 
03-24 16:50:07.166  3274  3331 I jxcore-log: ok 439 default 2
03-24 16:50:07.166  3274  3331 I jxcore-log: 
03-24 16:50:07.166  3274  3331 I jxcore-log: ok 440 2 run
03-24 16:50:07.166  3274  3331 I jxcore-log: ,
03-24 16:50:07.167  3274  3331 I jxcore-log: ok 441 default 3
03-24 16:50:07.167  3274  3331 I jxcore-log: 
03-24 16:50:07.175  3274  3331 I jxcore-log: # teardown
03-24 16:50:07.175  3274  3331 I jxcore-log: 
,03-24 16:50:07.376  3274  3331 I jxcore-log: # setup
03-24 16:50:07.376  3274  3331 I jxcore-log: 
,03-24 16:50:07.491  3274  3331 I jxcore-log: # 126. start and stop and start and stop
03-24 16:50:07.491  3274  3331 I jxcore-log: 
,03-24 16:50:07.875  3274  3331 I jxcore-log: ok 442 start out null
03-24 16:50:07.875  3274  3331 I jxcore-log: 
,03-24 16:50:07.906  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:07.906  3274  3331 I jxcore-log: 
,03-24 16:50:07.907  3274  3331 I jxcore-log: ok 443 back to null
03-24 16:50:07.907  3274  3331 I jxcore-log: 
,03-24 16:50:07.933  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
03-24 16:50:07.933  3274  3331 I jxcore-log: 
03-24 16:50:07.934  3274  3331 I jxcore-log: ok 444 still null
03-24 16:50:07.934  3274  3331 I jxcore-log: 
03-24 16:50:07.935  3274  3331 I jxcore-log: ok 445 verify failed
03-24 16:50:07.935  3274  3331 I jxcore-log: 
,03-24 16:50:07.936  3274  3331 I jxcore-log: ok 446 constructor called once
03-24 16:50:07.936  3274  3331 I jxcore-log: 
03-24 16:50:07.936  3274  3331 I jxcore-log: ok 447 constructor called with right args
03-24 16:50:07.936  3274  3331 I jxcore-log: 
03-24 16:50:07.936  3274  3331 I jxcore-log: ok 448 first start before first stop
03-24 16:50:07.936  3274  3331 I jxcore-log: 
03-24 16:50:07.936  3274  3331 I jxcore-log: ok 449 first stop before second start
03-24 16:50:07.936  3274  3331 I jxcore-log: 
,03-24 16:50:07.937  3274  3331 I jxcore-log: ok 450 second start before second stop
03-24 16:50:07.937  3274  3331 I jxcore-log: 
03-24 16:50:07.946  3274  3331 I jxcore-log: # teardown
03-24 16:50:07.946  3274  3331 I jxcore-log: 
,03-24 16:50:08.026  3274  3331 I jxcore-log: # setup
03-24 16:50:08.026  3274  3331 I jxcore-log: 
,03-24 16:50:08.393  3385  3899 V GoogleAuthProtoRequest: [343] a.<init>: mAccountName set to: thalitester@gmail.com
,03-24 16:50:08.455  1349  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
03-24 16:50:08.455  1349  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:50:08.456  1349  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:50:08.456  1349  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:50:08.471  1349  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: [343] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: [343] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-24 16:50:08.502  3385  3899 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-24 16:50:09.030  3274  3331 I jxcore-log: # 127. two identical starts in a row
03-24 16:50:09.030  3274  3331 I jxcore-log: 
,03-24 16:50:09.341  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:09.341  3274  3331 I jxcore-log: 
,03-24 16:50:09.344  3274  3331 I jxcore-log: ok 451 verify failed,
03-24 16:50:09.344  3274  3331 I jxcore-log: 
03-24 16:50:09.345  3274  3331 I jxcore-log: ok 452 constructor called once
03-24 16:50:09.345  3274  3331 I jxcore-log: 
03-24 16:50:09.345  3274  3331 I jxcore-log: ok 453 constructor called with right args
,03-24 16:50:09.345  3274  3331 I jxcore-log: 
03-24 16:50:09.346  3274  3331 I jxcore-log: ok 454 (unnamed assert)
03-24 16:50:09.346  3274  3331 I jxcore-log: ,
,03-24 16:50:09.352  3274  3331 I jxcore-log: # teardown
,03-24 16:50:09.352  3274  3331 I jxcore-log: 
,03-24 16:50:09.950  3274  3331 I jxcore-log: # setup
03-24 16:50:09.950  3274  3331 I jxcore-log: 
,03-24 16:50:10.106  3274  3331 I jxcore-log: # 128. two different starts in a row
03-24 16:50:10.106  3274  3331 I jxcore-log: 
,03-24 16:50:10.896  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:10.896  3274  3331 I jxcore-log: 
,03-24 16:50:10.904  3274  3331 I jxcore-log: ok 455 verify failed
03-24 16:50:10.904  3274  3331 I jxcore-log: 
03-24 16:50:10.904  3274  3331 I jxcore-log: ok 456 constructor called once
03-24 16:50:10.904  3274  3331 I jxcore-log: 
,03-24 16:50:10.905  3274  3331 I jxcore-log: ok 457 constructor called with right args
03-24 16:50:10.905  3274  3331 I jxcore-log: 
03-24 16:50:10.905  3274  3331 I jxcore-log: ok 458 (unnamed assert)
03-24 16:50:10.905  3274  3331 I jxcore-log: 
03-24 16:50:10.905  3274  3331 I jxcore-log: ok 459 (unnamed assert)
03-24 16:50:10.905  3274  3331 I jxcore-log: 
,03-24 16:50:10.909  3274  3331 I jxcore-log: # teardown
03-24 16:50:10.909  3274  3331 I jxcore-log: 
,03-24 16:50:11.056  3274  3331 I jxcore-log: # setup
03-24 16:50:11.056  3274  3331 I jxcore-log: 
,03-24 16:50:11.256  3274  3331 I jxcore-log: # 129. two stops and a start and two stops
03-24 16:50:11.256  3274  3331 I jxcore-log: 
,03-24 16:50:11.674  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:11.674  3274  3331 I jxcore-log: 
,03-24 16:50:11.677  3274  3331 I jxcore-log: ok 460 verify failed,
03-24 16:50:11.677  3274  3331 I jxcore-log: 
03-24 16:50:11.677  3274  3331 I jxcore-log: ok 461 constructor called once
,03-24 16:50:11.677  3274  3331 I jxcore-log: 
03-24 16:50:11.678  3274  3331 I jxcore-log: ok 462 constructor called with right args
03-24 16:50:11.678  3274  3331 I jxcore-log: 
03-24 16:50:11.679  3274  3331 I jxcore-log: ok 463 start before stop
03-24 16:50:11.679  3274  3331 I jxcore-log: 
,03-24 16:50:11.693  3274  3331 I jxcore-log: # teardown,
03-24 16:50:11.693  3274  3331 I jxcore-log: 
,03-24 16:50:11.809  3274  3331 I jxcore-log: # setup,
03-24 16:50:11.809  3274  3331 I jxcore-log: ,
,03-24 16:50:11.916  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:50:11.947  3274  3331 I jxcore-log: # 130. we properly enqueue requests so no then needed
03-24 16:50:11.947  3274  3331 I jxcore-log: 
,03-24 16:50:12.292  3274  3331 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
03-24 16:50:12.292  3274  3331 I jxcore-log: 
,03-24 16:50:12.294  3274  3331 I jxcore-log: ok 464 verify failed
03-24 16:50:12.294  3274  3331 I jxcore-log: 
,03-24 16:50:12.294  3274  3331 I jxcore-log: ok 465 constructor called once
03-24 16:50:12.294  3274  3331 I jxcore-log: 
,03-24 16:50:12.294  3274  3331 I jxcore-log: ok 466 constructor called with right args
03-24 16:50:12.294  3274  3331 I jxcore-log: 
,03-24 16:50:12.295  3274  3331 I jxcore-log: ok 467 start before stop
03-24 16:50:12.295  3274  3331 I jxcore-log: 
03-24 16:50:12.299  3274  3331 I jxcore-log: # teardown
03-24 16:50:12.299  3274  3331 I jxcore-log: 
,03-24 16:50:12.515  3274  3331 I jxcore-log: # setup
03-24 16:50:12.515  3274  3331 I jxcore-log: 
,03-24 16:50:12.781  3274  3331 I jxcore-log: # 131. test calculateSeqPointKeyId
03-24 16:50:12.781  3274  3331 I jxcore-log: 
,03-24 16:50:12.948  3274  3331 I jxcore-log: ok 468 should be equal,
03-24 16:50:12.948  3274  3331 I jxcore-log: 
03-24 16:50:12.949  3274  3331 I jxcore-log: ok 469 should be equal
03-24 16:50:12.949  3274  3331 I jxcore-log: 
03-24 16:50:12.952  3274  3331 I jxcore-log: # teardown
03-24 16:50:12.952  3274  3331 I jxcore-log: 
,03-24 16:50:13.132  3274  3331 I jxcore-log: # setup,
03-24 16:50:13.132  3274  3331 I jxcore-log: 
,03-24 16:50:13.946  3274  3331 I jxcore-log: # 132. can create servers manager
03-24 16:50:13.946  3274  3331 I jxcore-log: 
,03-24 16:50:14.152  3274  3331 I jxcore-log: ok 470 serversManager must not be null
03-24 16:50:14.152  3274  3331 I jxcore-log: 
,03-24 16:50:14.153  3274  3331 I jxcore-log: ok 471 serversManager must be an object
03-24 16:50:14.153  3274  3331 I jxcore-log: 
,03-24 16:50:14.161  3274  3331 I jxcore-log: # teardown
03-24 16:50:14.161  3274  3331 I jxcore-log: 
,03-24 16:50:14.378  3274  3331 I jxcore-log: # setup
03-24 16:50:14.378  3274  3331 I jxcore-log: 
,03-24 16:50:14.479  3274  3331 I jxcore-log: # 133. calling stop without start causes error,
03-24 16:50:14.479  3274  3331 I jxcore-log: 
,03-24 16:50:14.630  3274  3331 I jxcore-log: ok 472 We need to call start first
03-24 16:50:14.630  3274  3331 I jxcore-log: 
,03-24 16:50:14.636  3274  3331 I jxcore-log: # teardown
03-24 16:50:14.636  3274  3331 I jxcore-log: 
,03-24 16:50:14.902  3274  3331 I jxcore-log: # setup
03-24 16:50:14.902  3274  3331 I jxcore-log: 
,03-24 16:50:15.173  3274  3331 I jxcore-log: # 134. can start/stop servers manager
03-24 16:50:15.173  3274  3331 I jxcore-log: 
,03-24 16:50:15.327  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:50:15.327  3274  3331 I jxcore-log: 
,03-24 16:50:15.338  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 59095
03-24 16:50:15.338  3274  3331 I jxcore-log: 
,03-24 16:50:15.342  3274  3331 I jxcore-log: ok 473 port must be in range
03-24 16:50:15.342  3274  3331 I jxcore-log: 
,03-24 16:50:15.344  3274  3331 I jxcore-log: # teardown
03-24 16:50:15.344  3274  3331 I jxcore-log: 
,03-24 16:50:15.519  3274  3331 I jxcore-log: # setup,
03-24 16:50:15.519  3274  3331 I jxcore-log: 
,03-24 16:50:15.722  3274  3331 I jxcore-log: # 135. starting twice resolves with listening port,
03-24 16:50:15.722  3274  3331 I jxcore-log: 
,03-24 16:50:16.043  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server,
03-24 16:50:16.043  3274  3331 I jxcore-log: 
,03-24 16:50:16.052  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 36208,
03-24 16:50:16.052  3274  3331 I jxcore-log: 
,03-24 16:50:16.058  3274  3331 I jxcore-log: ok 474 second start should return same port,
03-24 16:50:16.058  3274  3331 I jxcore-log: 
,03-24 16:50:16.063  3274  3331 I jxcore-log: # teardown,
03-24 16:50:16.063  3274  3331 I jxcore-log: 
,03-24 16:50:16.717  3274  3331 I jxcore-log: # setup,
03-24 16:50:16.717  3274  3331 I jxcore-log: 
,03-24 16:50:16.870  3274  3331 I jxcore-log: # 136. terminateIncomingConnection will terminate a connection
03-24 16:50:16.870  3274  3331 I jxcore-log: 
,03-24 16:50:17.102  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:50:17.102  3274  3331 I jxcore-log: 
,03-24 16:50:17.105  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 43547
03-24 16:50:17.105  3274  3331 I jxcore-log: 
,03-24 16:50:17.111  3274  3331 I jxcore-log: DEBUG createNativeListener: new incoming socket
03-24 16:50:17.111  3274  3331 I jxcore-log: 
,03-24 16:50:17.112  3274  3331 I jxcore-log: DEBUG createNativeListener: creating incoming mux
03-24 16:50:17.112  3274  3331 I jxcore-log: 
03-24 16:50:17.114  3274  3331 I jxcore-log: DEBUG createNativeListener: new mux
03-24 16:50:17.114  3274  3331 I jxcore-log: 
,03-24 16:50:17.117  3274  3331 I jxcore-log: ok 475 we should be connected
03-24 16:50:17.117  3274  3331 I jxcore-log: 
03-24 16:50:17.119  3274  3331 I jxcore-log: DEBUG createNativeListener: incoming socket close
03-24 16:50:17.119  3274  3331 I jxcore-log: 
,03-24 16:50:17.120  3274  3331 I jxcore-log: ok 476 now we are disconnected
03-24 16:50:17.120  3274  3331 I jxcore-log: 
,03-24 16:50:17.134  3274  3331 I jxcore-log: # teardown,
03-24 16:50:17.134  3274  3331 I jxcore-log: 
,03-24 16:50:17.343  3274  3331 I jxcore-log: # setup,
03-24 16:50:17.343  3274  3331 I jxcore-log: 
,03-24 16:50:17.508  3274  3331 I jxcore-log: # 137. terminate an Outgoing connection will terminate the server,
03-24 16:50:17.508  3274  3331 I jxcore-log: 
,03-24 16:50:17.701  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:50:17.701  3274  3331 I jxcore-log: 
,03-24 16:50:17.705  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 34801
03-24 16:50:17.705  3274  3331 I jxcore-log: 
,03-24 16:50:17.708  3274  3331 I jxcore-log: # teardown
03-24 16:50:17.708  3274  3331 I jxcore-log: 
,03-24 16:50:17.859  3274  3331 I jxcore-log: # setup
03-24 16:50:17.859  3274  3331 I jxcore-log: 
,03-24 16:50:18.003  3274  3331 I jxcore-log: # 138. terminate an Outgoing connection with wrong arguments is not harmful
03-24 16:50:18.003  3274  3331 I jxcore-log: 
,03-24 16:50:18.148  3274  3331 I jxcore-log: DEBUG createNativeListener: creating native server
03-24 16:50:18.148  3274  3331 I jxcore-log: 
,03-24 16:50:18.151  3274  3331 I jxcore-log: DEBUG createNativeListener: listening 40672
03-24 16:50:18.151  3274  3331 I jxcore-log: 
,03-24 16:50:18.154  3274  3331 I jxcore-log: # teardown
03-24 16:50:18.154  3274  3331 I jxcore-log: 
,03-24 16:50:18.273  3274  3331 I jxcore-log: # setup
03-24 16:50:18.273  3274  3331 I jxcore-log: 
,03-24 16:50:18.422  3274  3331 I jxcore-log: ok 477 should be in started state
03-24 16:50:18.422  3274  3331 I jxcore-log: 
,03-24 16:50:18.425  3274  3331 I jxcore-log: # 139. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
,03-24 16:50:18.425  3274  3331 I jxcore-log: 
,03-24 16:50:18.626  3274  3331 I jxcore-log: ok 478 peer identifier should match
,03-24 16:50:18.626  3274  3331 I jxcore-log: 
03-24 16:50:18.626  3274  3331 I jxcore-log: ok 479 host address should match
03-24 16:50:18.626  3274  3331 I jxcore-log: 
03-24 16:50:18.627  3274  3331 I jxcore-log: ok 480 port should match
03-24 16:50:18.627  3274  3331 I jxcore-log: 
,03-24 16:50:18.633  3274  3331 I jxcore-log: ok 481 host address should be null
,03-24 16:50:18.633  3274  3331 I jxcore-log: 
03-24 16:50:18.634  3274  3331 I jxcore-log: ok 482 port should should be null
03-24 16:50:18.634  3274  3331 I jxcore-log: 
03-24 16:50:18.639  3274  3331 I jxcore-log: # teardown
03-24 16:50:18.639  3274  3331 I jxcore-log: 
,03-24 16:50:18.814  3274  3331 I jxcore-log: ok 483 should not be in started state
03-24 16:50:18.814  3274  3331 I jxcore-log: 
,03-24 16:50:18.821  3274  3331 I jxcore-log: # setup
03-24 16:50:18.821  3274  3331 I jxcore-log: 
,03-24 16:50:18.976  3274  3331 I jxcore-log: ok 484 should be in started state
03-24 16:50:18.976  3274  3331 I jxcore-log: 
,03-24 16:50:18.983  3274  3331 I jxcore-log: # 140. #startUpdateAdvertisingAndListening should use different USN after every invocation
03-24 16:50:18.983  3274  3331 I jxcore-log: 
,03-24 16:50:19.311  3274  3331 I jxcore-log: ok 485 USN should have changed from the first one
03-24 16:50:19.311  3274  3331 I jxcore-log: 
,03-24 16:50:19.321  3274  3331 I jxcore-log: ok 486 when receiving the second byebye, the first USN should be already set,
03-24 16:50:19.321  3274  3331 I jxcore-log: 
,03-24 16:50:19.329  3274  3331 I jxcore-log: # teardown
03-24 16:50:19.329  3274  3331 I jxcore-log: 
,03-24 16:50:19.619  3274  3331 I jxcore-log: ok 487 should not be in started state
03-24 16:50:19.619  3274  3331 I jxcore-log: 
,03-24 16:50:19.623  3274  3331 I jxcore-log: # setup
03-24 16:50:19.623  3274  3331 I jxcore-log: 
,03-24 16:50:19.723  3274  3331 I jxcore-log: ok 488 should be in started state
03-24 16:50:19.723  3274  3331 I jxcore-log: 
,03-24 16:50:19.725  3274  3331 I jxcore-log: # 141. messages with invalid location or USN should be ignored
03-24 16:50:19.725  3274  3331 I jxcore-log: 
,03-24 16:50:19.923  3274  3331 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000,
03-24 16:50:19.923  3274  3331 I jxcore-log: 
03-24 16:50:19.923  3274  3331 I jxcore-log: ok 489 should not have emitted with invalid port
03-24 16:50:19.923  3274  3331 I jxcore-log: 
03-24 16:50:19.925  3274  3331 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
03-24 16:50:19.925  3274  3331 I jxcore-log: 
,03-24 16:50:19.925  3274  3331 I jxcore-log: ok 490 should not have emitted with invalid USN
03-24 16:50:19.925  3274  3331 I jxcore-log: 
03-24 16:50:19.928  3274  3331 I jxcore-log: # teardown
03-24 16:50:19.928  3274  3331 I jxcore-log: 
,03-24 16:50:20.083  3274  3331 I jxcore-log: ok 491 should not be in started state
03-24 16:50:20.083  3274  3331 I jxcore-log: 
,03-24 16:50:20.085  3274  3331 I jxcore-log: # setup
03-24 16:50:20.085  3274  3331 I jxcore-log: 
,03-24 16:50:20.449  3274  3331 I jxcore-log: ok 492 should be in started state
03-24 16:50:20.449  3274  3331 I jxcore-log: 
,03-24 16:50:20.451  3274  3331 I jxcore-log: # 142. verify that Thali-specific messages are filtered correctly
03-24 16:50:20.451  3274  3331 I jxcore-log: 
,03-24 16:50:20.683  3274  3331 I jxcore-log: ok 493 irrelevant messages should be ignored
03-24 16:50:20.683  3274  3331 I jxcore-log: 
,03-24 16:50:20.685  3274  3331 I jxcore-log: ok 494 relevant messages should not be ignored
03-24 16:50:20.685  3274  3331 I jxcore-log: 
,03-24 16:50:20.686  3274  3331 I jxcore-log: ok 495 messages from this device should be ignored
03-24 16:50:20.686  3274  3331 I jxcore-log: 
03-24 16:50:20.692  3274  3331 I jxcore-log: # teardown
03-24 16:50:20.692  3274  3331 I jxcore-log: 
,03-24 16:50:20.829  3274  3331 I jxcore-log: ok 496 should not be in started state
03-24 16:50:20.829  3274  3331 I jxcore-log: 
,03-24 16:50:20.835  3274  3331 I jxcore-log: # setup
03-24 16:50:20.835  3274  3331 I jxcore-log: 
,03-24 16:50:20.943  3274  3331 I jxcore-log: ok 497 should be in started state
03-24 16:50:20.943  3274  3331 I jxcore-log: 
,03-24 16:50:20.945  3274  3331 I jxcore-log: # 143. #startListeningForAdvertisements should fail if start not called
03-24 16:50:20.945  3274  3331 I jxcore-log: 
,03-24 16:50:21.106  3274  3331 I jxcore-log: ok 498 specific error should be returned
,03-24 16:50:21.106  3274  3331 I jxcore-log: 
03-24 16:50:21.108  3274  3331 I jxcore-log: # teardown
03-24 16:50:21.108  3274  3331 I jxcore-log: 
,03-24 16:50:21.314  3274  3331 I jxcore-log: ok 499 should not be in started state
03-24 16:50:21.314  3274  3331 I jxcore-log: 
,03-24 16:50:21.321  3274  3331 I jxcore-log: # setup
03-24 16:50:21.321  3274  3331 I jxcore-log: 
,03-24 16:50:21.462  3274  3331 I jxcore-log: ok 500 should be in started state
,03-24 16:50:21.462  3274  3331 I jxcore-log: 
,03-24 16:50:21.464  3274  3331 I jxcore-log: # 144. #startUpdateAdvertisingAndListening should fail if start not called
03-24 16:50:21.464  3274  3331 I jxcore-log: 
,03-24 16:50:21.662  3274  3331 I jxcore-log: ok 501 specific error should be returned
03-24 16:50:21.662  3274  3331 I jxcore-log: 
,03-24 16:50:21.664  3274  3331 I jxcore-log: # teardown
03-24 16:50:21.664  3274  3331 I jxcore-log: 
,03-24 16:50:21.854  3274  3331 I jxcore-log: ok 502 should not be in started state
03-24 16:50:21.854  3274  3331 I jxcore-log: 
,03-24 16:50:21.861  3274  3331 I jxcore-log: # setup
03-24 16:50:21.861  3274  3331 I jxcore-log: 
,03-24 16:50:21.975  3274  3331 I jxcore-log: ok 503 should be in started state
03-24 16:50:21.975  3274  3331 I jxcore-log: 
,03-24 16:50:21.982  3274  3331 I jxcore-log: # 145. #start should fail if called twice in a row
03-24 16:50:21.982  3274  3331 I jxcore-log: 
,03-24 16:50:22.093  3274  3331 I jxcore-log: ok 504 specific error should be received,
03-24 16:50:22.093  3274  3331 I jxcore-log: 
,03-24 16:50:22.100  3274  3331 I jxcore-log: # teardown
03-24 16:50:22.100  3274  3331 I jxcore-log: 
,03-24 16:50:22.276  3274  3331 I jxcore-log: ok 505 should not be in started state,
03-24 16:50:22.276  3274  3331 I jxcore-log: 
,03-24 16:50:22.282  3274  3331 I jxcore-log: # setup,
03-24 16:50:22.282  3274  3331 I jxcore-log: 
,03-24 16:50:22.460  3274  3331 I jxcore-log: ok 506 should be in started state
03-24 16:50:22.460  3274  3331 I jxcore-log: 
,03-24 16:50:22.464  3274  3331 I jxcore-log: # 146. should not be started after stop is called,
03-24 16:50:22.464  3274  3331 I jxcore-log: 
,03-24 16:50:22.624  3274  3331 I jxcore-log: ok 507 should not be started,
03-24 16:50:22.624  3274  3331 I jxcore-log: 
,03-24 16:50:22.625  3274  3331 I jxcore-log: ok 508 should not be listening
,03-24 16:50:22.625  3274  3331 I jxcore-log: 
03-24 16:50:22.625  3274  3331 I jxcore-log: ok 509 should not target listening
03-24 16:50:22.625  3274  3331 I jxcore-log: 
03-24 16:50:22.626  3274  3331 I jxcore-log: ok 510 should not be advertising
03-24 16:50:22.626  3274  3331 I jxcore-log: 
03-24 16:50:22.626  3274  3331 I jxcore-log: ok 511 should not target advertising
03-24 16:50:22.626  3274  3331 I jxcore-log: 
,03-24 16:50:22.628  3274  3331 I jxcore-log: # teardown
03-24 16:50:22.628  3274  3331 I jxcore-log: 
,03-24 16:50:22.782  3274  3331 I jxcore-log: ok 512 should not be in started state
03-24 16:50:22.782  3274  3331 I jxcore-log: 
,03-24 16:50:22.784  3274  3331 I jxcore-log: # setup
03-24 16:50:22.784  3274  3331 I jxcore-log: 
,03-24 16:50:22.964  3274  3331 I jxcore-log: ok 513 should be in started state
03-24 16:50:22.964  3274  3331 I jxcore-log: 
,03-24 16:50:22.966  3274  3331 I jxcore-log: # 147. #startUpdateAdvertisingAndListening should fail invalid router has been passed
03-24 16:50:22.966  3274  3331 I jxcore-log: 
,03-24 16:50:23.591  3274  3331 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
03-24 16:50:23.591  3274  3331 I jxcore-log: 
,03-24 16:50:23.592  3274  3331 I jxcore-log: ok 514 specific error should be received
03-24 16:50:23.592  3274  3331 I jxcore-log: 
03-24 16:50:23.594  3274  3331 I jxcore-log: # teardown
03-24 16:50:23.594  3274  3331 I jxcore-log: 
,03-24 16:50:23.835  3274  3331 I jxcore-log: ok 515 should not be in started state
,03-24 16:50:23.835  3274  3331 I jxcore-log: 
03-24 16:50:23.842  3274  3331 I jxcore-log: # setup
03-24 16:50:23.842  3274  3331 I jxcore-log: 
,03-24 16:50:25.622  3274  3331 I jxcore-log: ok 516 should be in started state
03-24 16:50:25.622  3274  3331 I jxcore-log: 
,03-24 16:50:25.625  3274  3331 I jxcore-log: # 148. #startUpdateAdvertisingAndListening should fail if router server starting fails
03-24 16:50:25.625  3274  3331 I jxcore-log: 
,03-24 16:50:25.865  3274  3331 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
03-24 16:50:25.865  3274  3331 I jxcore-log: 
,03-24 16:50:25.867  3274  3331 I jxcore-log: ok 517 specific error expected
03-24 16:50:25.867  3274  3331 I jxcore-log: 
,03-24 16:50:25.871  3274  3331 I jxcore-log: # teardown
03-24 16:50:25.871  3274  3331 I jxcore-log: 
,03-24 16:50:25.964  3274  3331 I jxcore-log: ok 518 should not be in started state
03-24 16:50:25.964  3274  3331 I jxcore-log: 
,03-24 16:50:25.966  3274  3331 I jxcore-log: # setup
03-24 16:50:25.966  3274  3331 I jxcore-log: 
,03-24 16:50:26.103  3274  3331 I jxcore-log: ok 519 should be in started state
03-24 16:50:26.103  3274  3331 I jxcore-log: 
,03-24 16:50:26.105  3274  3331 I jxcore-log: # 149. #startUpdateAdvertisingAndListening should start hosting given router object
03-24 16:50:26.105  3274  3331 I jxcore-log: 
,03-24 16:50:26.244  3274  3331 I jxcore-log: ok 520 server should respond with code 200
03-24 16:50:26.244  3274  3331 I jxcore-log: 
,03-24 16:50:26.251  3274  3331 I jxcore-log: # teardown
03-24 16:50:26.251  3274  3331 I jxcore-log: 
,03-24 16:50:26.251  3462  3905 I BooksSync: Starting books sync for 61035162, extras: ade
,03-24 16:50:26.273  3462  3906 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-24 16:50:26.325  1349  1725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 16:50:26.325  1349  1725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-24 16:50:26.325  1349  1725 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-24 16:50:26.325  1349  1725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:50:26.330  1349  1725 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:50:26.411  3274  3331 I jxcore-log: ok 521 should not be in started state
03-24 16:50:26.411  3274  3331 I jxcore-log: 
,03-24 16:50:26.425  3274  3331 I jxcore-log: # setup
03-24 16:50:26.425  3274  3331 I jxcore-log: 
,03-24 16:50:26.456  1349  1723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-24 16:50:26.456  1349  1723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-24 16:50:26.456  1349  1723 I GLSUser : [GLSUser] Extracting token using key: Auth
03-24 16:50:26.456  1349  1723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-24 16:50:26.464  1349  1723 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 16:50:26.490  3462  3906 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-24 16:50:26.492  3462  3905 E BooksSync: Soft error
03-24 16:50:26.492  3462  3905 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:50:26.492  3462  3905 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-24 16:50:26.493  3462  3905 E BooksSync: Sync error
03-24 16:50:26.493  3462  3905 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-24 16:50:26.493  3462  3905 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-24 16:50:26.493  3462  3905 I BooksSync: Finished books sync
,03-24 16:50:26.505  3274  3331 I jxcore-log: ok 522 should be in started state,
03-24 16:50:26.505  3274  3331 I jxcore-log: 
,03-24 16:50:26.508  3274  3331 I jxcore-log: # 150. #stop can be called multiple times in a row,
03-24 16:50:26.508  3274  3331 I jxcore-log: 
,03-24 16:50:26.510   822   855 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 441806, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,03-24 16:50:26.638  3274  3331 I jxcore-log: ok 523 should be in stopped state,
03-24 16:50:26.638  3274  3331 I jxcore-log: 
03-24 16:50:26.642  3274  3331 I jxcore-log: ok 524 should still be in stopped state
03-24 16:50:26.642  3274  3331 I jxcore-log: 
,03-24 16:50:26.644  3274  3331 I jxcore-log: # teardown,
03-24 16:50:26.644  3274  3331 I jxcore-log: 
,03-24 16:50:26.763  3274  3331 I jxcore-log: ok 525 should not be in started state
03-24 16:50:26.763  3274  3331 I jxcore-log: 
03-24 16:50:26.765  3274  3331 I jxcore-log: # setup,
03-24 16:50:26.765  3274  3331 I jxcore-log: 
,03-24 16:50:26.867  3274  3331 I jxcore-log: ok 526 should be in started state
03-24 16:50:26.867  3274  3331 I jxcore-log: 
,03-24 16:50:26.877  3274  3331 I jxcore-log: # 151. #startListeningForAdvertisements can be called multiple times in a row
03-24 16:50:26.877  3274  3331 I jxcore-log: 
,03-24 16:50:27.025  3274  3331 I jxcore-log: ok 527 should be in listening state
03-24 16:50:27.025  3274  3331 I jxcore-log: 
,03-24 16:50:27.027  3274  3331 I jxcore-log: ok 528 should still be in listening state
03-24 16:50:27.027  3274  3331 I jxcore-log: 
,03-24 16:50:27.029  3274  3331 I jxcore-log: # teardown
03-24 16:50:27.029  3274  3331 I jxcore-log: 
,03-24 16:50:27.175  3274  3331 I jxcore-log: ok 529 should not be in started state
03-24 16:50:27.175  3274  3331 I jxcore-log: 
,03-24 16:50:27.182  3274  3331 I jxcore-log: # setup
03-24 16:50:27.182  3274  3331 I jxcore-log: 
,03-24 16:50:27.303  3274  3331 I jxcore-log: ok 530 should be in started state
03-24 16:50:27.303  3274  3331 I jxcore-log: 
,03-24 16:50:27.305  3274  3331 I jxcore-log: # 152. #stopListeningForAdvertisements can be called multiple times in a row
03-24 16:50:27.305  3274  3331 I jxcore-log: 
,03-24 16:50:27.400  3274  3331 I jxcore-log: ok 531 should not be in listening state
03-24 16:50:27.400  3274  3331 I jxcore-log: 
,03-24 16:50:27.403  3274  3331 I jxcore-log: ok 532 should still not be in listening state
03-24 16:50:27.403  3274  3331 I jxcore-log: 
,03-24 16:50:27.405  3274  3331 I jxcore-log: # teardown
03-24 16:50:27.405  3274  3331 I jxcore-log: 
,03-24 16:50:27.573  3274  3331 I jxcore-log: ok 533 should not be in started state
03-24 16:50:27.573  3274  3331 I jxcore-log: 
,03-24 16:50:27.580  3274  3331 I jxcore-log: # setup
03-24 16:50:27.580  3274  3331 I jxcore-log: 
,03-24 16:50:27.722  3274  3331 I jxcore-log: ok 534 should be in started state
03-24 16:50:27.722  3274  3331 I jxcore-log: 
,03-24 16:50:27.724  3274  3331 I jxcore-log: # 153. #stopAdvertisingAndListening can be called multiple times in a row
03-24 16:50:27.724  3274  3331 I jxcore-log: 
,03-24 16:50:27.873  3274  3331 I jxcore-log: ok 535 should not be in advertising state
03-24 16:50:27.873  3274  3331 I jxcore-log: 
,03-24 16:50:27.878  3274  3331 I jxcore-log: ok 536 should still not be in advertising state
03-24 16:50:27.878  3274  3331 I jxcore-log: 
,03-24 16:50:27.883  3274  3331 I jxcore-log: # teardown
03-24 16:50:27.883  3274  3331 I jxcore-log: 
,03-24 16:50:28.051  3274  3331 I jxcore-log: ok 537 should not be in started state
03-24 16:50:28.051  3274  3331 I jxcore-log: 
,03-24 16:50:28.058  3274  3331 I jxcore-log: # setup
03-24 16:50:28.058  3274  3331 I jxcore-log: 
,03-24 16:50:28.275  3274  3331 I jxcore-log: ok 538 should be in started state
03-24 16:50:28.275  3274  3331 I jxcore-log: 
,03-24 16:50:28.284  3274  3331 I jxcore-log: # 154. functions are run from a queue in the right order
03-24 16:50:28.284  3274  3331 I jxcore-log: 
,03-24 16:50:28.586  3274  3331 I jxcore-log: ok 539 call order must match
03-24 16:50:28.586  3274  3331 I jxcore-log: 
,03-24 16:50:28.592  3274  3331 I jxcore-log: # teardown
03-24 16:50:28.592  3274  3331 I jxcore-log: 
,03-24 16:50:29.216  3274  3331 I jxcore-log: ok 540 should not be in started state
03-24 16:50:29.216  3274  3331 I jxcore-log: 
,03-24 16:50:29.222  3274  3331 I jxcore-log: # setup
03-24 16:50:29.222  3274  3331 I jxcore-log: 
,03-24 16:50:29.345  3274  3331 I jxcore-log: # 155. #ThaliPeerPoolDefault - single action
03-24 16:50:29.345  3274  3331 I jxcore-log: 
,03-24 16:50:29.534  3274  3331 I jxcore-log: ok 541 is an agent
03-24 16:50:29.534  3274  3331 I jxcore-log: 
,03-24 16:50:29.537  3274  3331 I jxcore-log: ok 542 enqueue is fine
03-24 16:50:29.537  3274  3331 I jxcore-log: 
,03-24 16:50:29.542  3274  3331 I jxcore-log: ok 543 Everything should be off the queue
03-24 16:50:29.542  3274  3331 I jxcore-log: 
,03-24 16:50:29.544  3274  3331 I jxcore-log: # teardown
03-24 16:50:29.544  3274  3331 I jxcore-log: 
,03-24 16:50:29.723  3274  3331 I jxcore-log: # setup
03-24 16:50:29.723  3274  3331 I jxcore-log: 
,03-24 16:50:29.871  3274  3331 I jxcore-log: # 156. #ThaliPeerPoolDefault - multiple actions
03-24 16:50:29.871  3274  3331 I jxcore-log: 
,03-24 16:50:30.002  3274  3331 I jxcore-log: ok 544 is an agent
03-24 16:50:30.002  3274  3331 I jxcore-log: 
,03-24 16:50:30.003  3274  3331 I jxcore-log: ok 545 first enqueue is fine
03-24 16:50:30.003  3274  3331 I jxcore-log: 
,03-24 16:50:30.004  3274  3331 I jxcore-log: ok 546 is an agent
03-24 16:50:30.004  3274  3331 I jxcore-log: 
03-24 16:50:30.004  3274  3331 I jxcore-log: ok 547 second enqueue is fine
03-24 16:50:30.004  3274  3331 I jxcore-log: 
03-24 16:50:30.006  3274  3331 I jxcore-log: ok 548 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
03-24 16:50:30.006  3274  3331 I jxcore-log: 
,03-24 16:50:30.007  3274  3331 I jxcore-log: ok 549 Queue is empty
03-24 16:50:30.007  3274  3331 I jxcore-log: 
03-24 16:50:30.009  3274  3331 I jxcore-log: # teardown
03-24 16:50:30.009  3274  3331 I jxcore-log: 
,03-24 16:50:30.245  3274  3331 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-24 16:50:30.245  3274  3331 I jxcore-log: 
,03-24 16:50:30.575  3908  3908 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-24 16:50:30.578  3908  3908 D AndroidRuntime: CheckJNI is OFF
,03-24 16:50:30.694  3908  3908 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-24 16:50:30.708   822   856 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
,03-24 16:50:30.708   822   856 I ActivityManager: Killing 3274:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-24 16:50:30.828   822   866 W PackageSettings: Skipping PackageSetting{66ff578 com.example.hello/10273} due to missing metadata
,03-24 16:50:30.903   822   840 I WindowState: WIN DEATH: Window{2b45dff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-24 16:50:30.905   822  1025 D WifiService: Client connection lost with reason: 4
,03-24 16:50:30.920   822   856 E libprocessgroup: failed to kill 1 processes for processgroup 3274
,03-24 16:50:30.921   822   856 W ActivityManager: Force removing ActivityRecord{32698c41 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-24 16:50:30.944   822   822 V ActivityManager: Display changed displayId=0
,03-24 16:50:30.949   822   866 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed,
,03-24 16:50:30.961   822  2545 W ActivityManager: Spurious death for ProcessRecord{11921f37 3274:com.test.thalitest/u0a95}, curProc for 3274: null
,03-24 16:50:30.964  1236  1236 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-24 16:50:30.966  2969  2969 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-24 16:50:30.967  1236  3922 I Keyboard.Facilitator.DecoderInitializer: run()
,03-24 16:50:30.973   822  1003 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-24 16:50:30.976   822  1046 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-24 16:50:30.986  1236  3922 I Decoder : createOrResetDecoder
,03-24 16:50:31.014  1068  1068 I art     : Explicit concurrent mark sweep GC freed 53847(2MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 1.068ms total 56.752ms
,03-24 16:50:31.028   822  1281 I ActivityManager: Start proc 3924:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-24 16:50:31.042   822   841 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3274 uid 10095
,03-24 16:50:31.049  1236  1236 I Keyboard.Facilitator: onFinishInput()
,03-24 16:50:31.062  1349  1349 I ConfigService: onCreate
,03-24 16:50:31.069   822   822 I art     : Explicit concurrent mark sweep GC freed 43807(2MB) AllocSpace objects, 8(316KB) LOS objects, 31% free, 34MB/50MB, paused 2.972ms total 109.207ms
,03-24 16:50:31.071   822   866 I art     : WaitForGcToComplete blocked for 80.616ms for cause Explicit
,03-24 16:50:31.104  1319  1319 I art     : Explicit concurrent mark sweep GC freed 5085(371KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 848us total 20.780ms
,03-24 16:50:31.107  1349  1723 I art     : Explicit concurrent mark sweep GC freed 49708(2MB) AllocSpace objects, 17(1874KB) LOS objects, 36% free, 27MB/43MB, paused 1.132ms total 27.186ms
,03-24 16:50:31.132  1236  3922 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-24 16:50:31.159  3924  3950 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-24 16:50:31.165   822   822 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 16:50:31.165   822   822 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-24 16:50:31.173   822  1154 I ActivityManager: Start proc 3953:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-24 16:50:31.175  1236  3922 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-24 16:50:31.177  1236  3922 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-24 16:50:31.177  1236  3922 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-24 16:50:31.181  1236  3922 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-24 16:50:31.181  1236  3922 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-24 16:50:31.182  1236  3922 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-24 16:50:31.182  1236  3922 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-24 16:50:31.183  1236  3922 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-24 16:50:31.184  1236  3922 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-24 16:50:31.184  1236  3922 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-24 16:50:31.184  1236  3922 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-24 16:50:31.184  1236  3922 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-24 16:50:31.184  1236  3922 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-24 16:50:31.217  3924  3943 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-24 16:50:31.219   822   866 I art     : Explicit concurrent mark sweep GC freed 9195(925KB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 34MB/50MB, paused 1.633ms total 146.644ms
,03-24 16:50:31.230   822  2545 I ActivityManager: Start proc 3974:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-24 16:50:31.236   822  1281 I ActivityManager: Killing 3577:com.android.chrome/u0a40 (adj 15): empty #17
,03-24 16:50:31.246  1319  1319 D Launcher.Workspace: 11683562 - stripEmptyScreens()
03-24 16:50:31.247  1319  1319 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-24 16:50:31.287  3908  3908 I art     : System.exit called, status: 0
03-24 16:50:31.287  3908  3908 I AndroidRuntime: VM exiting with result code 0.
,03-24 16:50:31.486  3974  3974 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
03-24 16:50:31.490  3924  3943 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
03-24 16:50:31.492  3924  3943 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
03-24 16:50:31.492  3924  3943 E AndroidRuntime: Process: android.process.acore, PID: 3924
03-24 16:50:31.492  3924  3943 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 16:50:31.492  3924  3943 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 16:50:31.505   822   866 I ActivityManager: Start proc 3997:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-24 16:50:31.522   822  4007 E DropBoxManagerService: Can't write: system_app_crash
03-24 16:50:31.522   822  4007 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 16:50:31.522   822  4007 E DropBoxManagerService: 	... 5 more
,03-24 16:50:31.524  1349  1349 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-24 16:50:31.525  1349  1349 D AndroidRuntime: Shutting down VM
03-24 16:50:31.526  1349  1349 E AndroidRuntime: FATAL EXCEPTION: main
03-24 16:50:31.526  1349  1349 E AndroidRuntime: Process: com.google.process.gapps, PID: 1349
03-24 16:50:31.526  1349  1349 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-24 16:50:31.526  1349  1349 E AndroidRuntime: 	... 9 more
,03-24 16:50:31.536   822  4017 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-24 16:50:31.537   822   856 D Atlas   : Validating map...
,03-24 16:50:31.537  3974  4016 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-24 16:50:31.537  3974  4016 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-24 16:50:31.538  3974  4016 E AndroidRuntime: Process: com.android.keychain, PID: 3974
03-24 16:50:31.538  3974  4016 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.ja,va:791)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 16:50:31.538  3974  4016 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: Can't write: system_app_crash
03-24 16:50:31.555   822  4018 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 16:50:31.555   822  4018 E DropBoxManagerService: 	... 5 more
03-24 16:50:31.555   822  4020 E DropBoxManagerService: Can't write: system_app_crash
03-24 16:50:31.555   822  4020 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 16:50:31.555   822  4020 E DropBoxManagerService: 	... 5 more
03-24 16:50:31.566  3800  3800 W LocationOracleImpl: Best location was null
03-24 16:50:31.574  3800  4026 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 16:50:31.586  3800  3946 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:50:31.586  3800  3946 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: Couldn't open jar_store.db for writing (will try read-only):
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-24 16:50:31.587  3800  3946 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-24 16:50:31.587  3800  3800 I VS.Container: create_recognizer
03-24 16:50:31.590  3800  3946 W SQLiteOpenHelper: Opened jar_store.db in read-only mode
03-24 16:50:31.597   822  1415 I ActivityManager: Killing 3622:com.qualcomm.timeservice/1000 (adj 15): empty #17
03-24 16:50:31.605   822  4017 I OpenGLRenderer: Initialized EGL, version 1.4
03-24 16:50:31.615   822  4017 D OpenGLRenderer: Enabling debug mode 0
,03-24 16:50:31.684  3800  4033 I HotwordRecognitionRnr: Starting hotword detection.
,03-24 16:50:31.687  3800  4034 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@19e208cb
,03-24 16:50:31.689   359  4036 I AudioFlinger: AudioFlinger's thread 0xb4ca9000 ready to run
,03-24 16:50:31.691   359  1018 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 16:50:31.693  3800  4034 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@19e208cb
,03-24 16:50:31.702   359  4036 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-24 16:50:31.703   359  4036 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,03-24 16:50:31.703   359  4036 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-24 16:50:31.703   359  4036 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-24 16:50:31.727   359  4036 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-24 16:50:31.736  3800  4024 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-24 16:50:31.737  3800  4024 E FileBytesWriter: Failed to write new file: loracle.new
,03-24 16:50:31.740  3800  4042 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 16:50:31.747  3800  4043 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 16:50:31.754  3800  4024 W FileUtils: Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-24 16:50:31.754  3800  4024 E FileBytesWriter: Failed to write new file: loracle.new
,03-24 16:50:31.806  3800  3800 I HotwordWorker: onReady
,03-24 16:50:31.880  3800  4031 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@19e208cb
,03-24 16:50:31.880  3800  3800 I HotwordDetector: Closing mic
,03-24 16:50:31.889  3800  4046 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 16:50:31.895  3800  3842 W TRUiThreadExecutor: Task does not implement UiTask: com.google.common.g.a.p@f84a9a2
,03-24 16:50:31.909   822  1326 I ActivityManager: Killing 3644:com.google.android.deskclock/u0a44 (adj 15): empty #17
,03-24 16:50:31.930   359  4036 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,03-24 16:50:31.931   359  4036 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
,03-24 16:50:31.935   359  1018 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-24 16:50:31.936  3800  4033 I HotwordRecognitionRnr: Hotword detection finished
03-24 16:50:31.936  3800  4032 I HotwordRecognitionRnr: Stopping hotword detection.
,03-24 16:50:32.226  1236  3922 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-24 16:50:32.226  1236  3922 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-24 16:50:32.263  1236  3922 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-24 16:50:32.263  1236  3922 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-24 16:50:32.298  1236  3922 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp,
03-24 16:50:32.298  1236  3922 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-24 16:50:32.299  1236  3922 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-24 16:50:32.299  1236  3922 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-24 16:50:36.609  3800  4053 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-24 16:50:40.600  2150  2214 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-24 16:50:41.883   822  1254 E QMI_FW  : xport_send: Sendto failed for port 3840
,03-24 16:50:41.883   822  1254 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-24 16:50:41.883   822  1254 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1703023891
03-24 16:50:41.883   822  1254 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 16:50:41.884   822  1254 E QMI_FW  : xport_send: Sendto failed for port 3840
03-24 16:50:41.884   822  1254 E LocSvc_api_v02: E/locClientSendReq:2446]: send_msg_sync error: -1
03-24 16:50:41.884   822  1254 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1703023891
03-24 16:50:41.884   822  1254 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-24 16:50:41.886   260   321 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-24 16:50:41.894   878   878 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
03-24 16:50:41.894   878   878 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
,03-24 16:50:41.895   878   878 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
03-24 16:50:41.895   878   878 I kickstart: STATUS: Wrote to /sys/power/wake_unlock

```
